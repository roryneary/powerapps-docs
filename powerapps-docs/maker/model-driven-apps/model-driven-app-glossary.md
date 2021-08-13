---
title: Model-driven app glossary of terms | Microsoft Docs
description: Simple descriptions of commonly used terms when building model-driven apps
ms.custom: intro-internal
author: Mattp123
ms.service: powerapps
ms.topic: overview
ms.component: model
ms.date: 07/20/2021
ms.subservice: mda-maker
ms.author: matp
search.audienceType: 
  - maker
search.app: 
  - PowerApps
  - D365CE
searchScope:
  - "Power Apps"
---
# Model-driven app glossary of common terms

## Accessibility

Accessibility is a term that is used to refer to the extent to which people with disabilities can use digital products.  In the case of model-driven apps consideration has been paid to matters such as responsive design, how user navigate between fields, how the app behaves in high contrast mode and how screen readers help users to understand the nature of the application.

[Using screen readers within model-driven apps](../../user/screen-reader.md)

## App Designer

The tool that is used in order to create model-driven apps.  Given that the model-driven and canvas app building experience are starting to converge the new app designer experience (which delivers the app experience during the build process) will begin to replace the classic experience.

It allows us to configure the navigation site map, the tables required and the forms and views relevant to the app.

[We can use the classic app designer when we build or edit our apps](../../maker/model-driven-apps/build-first-model-driven-app.md)

[A preview of the new app designer experience](../../maker/model-driven-apps/app-designer-overview.md)

## App Navigation Experience

The way in which we areas, groups and sub-groups are presented in a model-driven app.  It is often know as the [site map](../model-driven-apps/model-driven-app-glossary.md#site-map)

## Application Lifecycle Management

The way in which we manage the life cycle of an application from conception to end of life.  From a technical perspective much of this is managed via solutions when delivering model-driven app products.

## Area

 A part of the [model-driven app navigation experience](../../maker/model-driven-apps/app-navigation.md).  Apps can have multiple groups and groups can have multiple sub-areas.  The sub-area contains the tables relevant to the application. For apps with more than one area, a switch control is displayed in the lower left navigation pane.

## Business Process Flow

Logic built into a given table to ensure that users complete records by updating fields in the correct order.  Authored initially using the Power Automate Experience.

A business process flow is arranged into Stages and each stage defines the fields that need to be completed at that time.
Business Process Flows express themselves as dots spread across the screen and each dot represents themselves as the relevant stage.

[Using screen readers within model-driven apps](https://docs.microsoft.com/en-us/power-automate/business-process-flows-overview)

## Business Rule

Business rules are server-side logic that is used with canvas or model-driven apps to set or clear values in one or many columns in a table. They can also be used to validate stored data or show error messages. Model-driven apps can use business rules to show or hide columns, enable or disable columns, and create recommendations based on business intelligence.

[Find out more about business rules here](https://docs.microsoft.com/en-us/learn/modules/define-create-business-rules/1-rules)  

## Canvas app

An app which is generated using drag and drop controls configured using Power Fx.  Canvas apps offer the designer significant control over the user experience and can be connected to a very wide range of data sources and data services.  Canvas apps are arranged into screens and controls such as galleries, text boxes and dropdowns are placed onto the screens and configured so that they connect to the data sources and to each other correctly.

[Find out more about canvas apps here](../canvas-apps/getting-started.md).

## Chart

A visual representation of a table of data.  These can take the form of line, bar, pie chart or donut chart.

[Find out more about creating a system chart here](../../maker/model-driven-apps/create-edit-system-chart.md).

## Classic App Designer

Modern apps allow for the creation of both Canvas apps and model-driven apps.

In due course all model-driven apps will be authored as modern apps.

The ability to create model-driven apps using the app designer remains.  We call this the classic app designer authoring experience.

## Column

A field within a dataverse table (or entity).  Columns are similar to fields in databases and have different data types such as Text, Number, Date as well as data types less familiar to databases such as Phone, Email, File and Image.

The nature of the field type defines the type of data required by the column and also the controls (such as date picker or text box) that will be made available when using the control.

[How to create and edit columns](../../maker/data-platform/create-edit-fields.md)

[Add, configure, move, or delete columns on a form](../../maker/model-driven-apps/add-move-or-delete-fields-on-form.md)

## Component

Components are elements used when creating the elements that make up a model-driven app.

Very often these will relate to the method of creation of the tables that make up the model driven app.

Components can be split into Data (tables, relationships, columns) UI (Site Map,forms,views) Logic (Business process flows, rules ..) and Visualization (Charts, dashboards, Power BI Tiles)

[Find out more about components](../../maker/model-driven-apps/model-driven-app-components.md)

## Connection

A model driven app is only ever connected to the data tables that reside in the same environment.  This connection can be considered as being native, as it never need to be set up within an environment.

Connections exist within the environment to enable other elements of the Power Platform to operate correctly.  Notably, canvas Power Apps and Power Automate flows do have the ability to make use of multiple connections.

## Control

Controls allow us to interact with information contained within our records.  They typically manifest themselves within forms, where we have the opportunity to update data.  Examples of controls are calendar, toggle, choices, slider and editable grids.  In some cases we may wish to use different controls depending upon the device employed by the user.

[Find out more about controls](../../maker/model-driven-apps/additional-controls-for-dynamics-365-for-phones-and-tablets.md)

## Dashboard

A method of presenting data relating to users in a graphic or chart form.

[Find out more about dashboards here](../../maker/model-driven-apps/create-edit-dashboards.md)

A dashboard allows charts, Power BI reports and views of tables to be presented to the app user.

[Find out more about how to use Power BI within a model driven app](../../maker/model-driven-apps/use-power-bi.md)

## Data Model

A collection of related tables.  In the context of model-driven apps these are held within the Dataverse database.

Where these are included in a solution these are often a set of related tables built with the purpose of delivering the overall business application.

## Database

The collective term for all the tables in Dataverse.

## Dataverse

Microsoft Dataverse is the collective term for the tables, workflows, business process flows and related functionality that is provisioned within an environment when a database is created.  

Model-driven apps are tied to the Microsoft Dataverse database.

A Dataverse database contains data structures most closely associated with databases in addition to being able to hold model-driven apps, canvas apps, power automate flows.

[Find out more about Dataverse here](../../maker/data-platform/data-platform-intro.md)

## Dynamics

Microsoft Dynamics is a line of enterprise resource planning (ERP) and customer relationship management (CRM) software applications. Microsoft markets Dynamics applications through a network of reselling partners who provide specialized services.

Dynamics manifests itself as model-driven apps that make use of the Dataverse database within your environment.
Dataverse table and the two terms can and are used interchangeably.

In most areas of Dataverse we use the term

## Entity

An entity is another way of describing a [table](../model-driven-apps/model-driven-app-glossary.md#table).  However you will see elements of this terminology within the product and elsewhere on the internet.

## Environment

An environment is a space to store, manage, and share your organization's business data, data structures, apps, chatbots, and flows.

You can package up the various elements as solutions, and these solutions can be exported from one environment to another.

An environment can only ever have 1 Dataverse database and all your model-driven apps are tied to this database.

Often multiple environments are used to enable application life-cycle management.  For example you might have a development, test and production environment.

Environments are tied to a geographical region and can be a means of ensuring that the data physically stays in the correct geographical region.

[Find out more about environments here](https://docs.microsoft.com/en-us/power-platform/admin/environments-overview)

## Form

Forms provide the user interface (UI) that people use to create, view, or edit table records. Use the form designer in the customization tools to create and edit forms. More information: [Create and design forms](../../maker/model-driven-apps/create-design-forms.md) for information about tasks related to working with forms in the application.

## Group

A part of the [model-driven app navigation experience](../../maker/model-driven-apps/app-navigation.md).
Group names appear as a navigation element in an app with the subarea names (tables) within the group listed beneath it.

## Monitor

Also know as the App Monitor.  It allows us to understand aspects of the performance of our model-driven app, but can an also be used for canvas apps.

[Learn how to use the app monitor](../../maker/monitor-modelapps.md) 

## Publish

The process by which we make the latest iteration of the app available to users within an environment.

## Record

A record contains one or more categories of information about a person, a place, or a thing. For example, a record might contain the name, the email address, and the phone number of a single customer. Other tools refer to a record as a "row" or an "item".  Records exist within dataverse tables.

## Relationship

The way in which fields between tables relate to each other.  There are 3 types of relationship:

- 1 to many (1 Author to many Novels)
- many to 1 (many pages to 1 book)
- Many to Many (many books borrowed by many people).

Model driven apps often contain tables with relationships between them.  Where relationships exist we have the ability to navigate to the record within the related table.  For example, when looking at a sale we might navigate to the account table to investigate details relating to the account.

## Responsive Apps

An app that is **responsive** will render itself in a way that depends on the nature of the device that is accessing the app.  This may even mean that depending on the device there may even be different controls (e.g. a date picker) whether the user is consuming the app on a computer, tablet or mobile. Additionally, tables and fields will render themselves according to size of the device being used.

## Section

Tabs within forms are arranged into sections.  Sections can be arranged into 1 to 4 columns, and they allow us to arrange the record metadata in a way that it is most relevant to the current tab and the current section.

[Learn more about working with sections](../../maker/model-driven-apps/add-move-or-delete-sections-on-form.md)

## Security Role

A security role defines what people can see and do with a record.  

This relates to create, read, write, delete, update and append actions.

Security roles are created and users are put into security roles either as individual user names or by using active directory security groups.

[Find out more about security roles here](https://docs.microsoft.com/en-us/power-platform/admin/security-roles-privileges##%20security-roles)

## Site Map

Site maps define the tables that are included within a model-driven app and the navigation experience by which users will have when moving between those apps.

A model-driven app is essentially a collection of tables, dashboards and views and these are described via the site map.

When configuring the navigation experience we are editing the Areas, Groups and Subgroup navigation elements.  Tables exist at the level of the subgroup, and are arranged into groups.  Groups are effectively collections of tables and are visible in the navigation pane.  Areas allow you to toggle between visible groups.

Both modern and classic methods of creating a model-driven app include site maps, however with a modern app you design the site map with a drag and drop experience whereas with the classic method you build the site map by hand.

To get to the site map from the modern app building experience you need to click switch to classic.

[Find out more about app navigation here](../../user/navigation.md)

## Solution

A solution is a wrapper for a very wide range of components including tables (entities), cloud flows, security roles.

The exist in 2 forms.  **Managed Solutions** permit only a small amount of customisation whereas **Unmanaged Solutions** give designers full control over the product that they are creating.

Unmanaged Solutions would be used by developers and these would be exported as managed solutions for use in production environments.

This allows for a high level of control around our application lifecycle management.

[Find out more about solutions here](../maker/data-platform/solutions-overview.md)

## Subarea

A part of the [model driven app navigation experience](../../user/navigation.md).
Subareas (tables) and pages appear under the group that they're configured within in the app designer.

## Tab

Every form has at least 1 tab.  They allow us to present a range of sections.  A form can have multiple tabs and this allows us to offer the user a range of ways of looking at the same record.  This is often a better user experience, or a more logical way of presenting the data in the record.

[Learn more about working with tabs](../../maker/model-driven-apps/add-move-or-delete-tabs-on-form.md)

## Table

A table is a method of storing data in columns (or fields) within Dataverse.  We sometimes refer to them [entities](../model-driven-apps/model-driven-app-glossary.md#entity).

A single entry within a table is know as a record, for example a single customer, and the columns describe metadata associated with the customer such as the name, telephone number or credit limit.

Every model-driven app must contain at least one table.  Much of the process of creating a model driven app is selecting the tables most relevant to solving the business problem.

Tables have views, forms and business rules associated with them.

Tables can relate to other tables and these are defined via the relationships that have been set up between them.

[Find out more about configuring tables here](../../maker/data-platform/entity-overview.md)

## Unified Interface

The Unified Interface for model-driven apps provides a consistent and accessible user experience across devices—whether on a desktop, laptop, tablet, or phone.  The predecessor the the unified interface was know as the web interface.

[Find out more about the unified interface here](../../user/unified-interface.md)

## Validate

The process by which we confirm if the model driven app has all the components required for it to function properly.

## View

A tabular representation of records in a dataverse table.  Table can have multiple views.

Views can be pre-filtered and it is possible to define the specific views that a model driven app will make available to users.

Tables can have multiple views associated with them and we can define the table views relevant to our model-driven apps at the time that we create them.

[Find out more about views here](../../developer/model-driven-apps/customize-entity-views.md)

## Workflow

A workflow is a series of functions or methods, called steps, that are performed sequentially and apply to data contained within our tables. The workflow can change the processing direction by using conditionals, referred to as conditional branches.

In many cases workflows can be replaced by Power Automate flows, and vice versa.

[!INCLUDE[footer-include](../../includes/footer-banner.md)]
