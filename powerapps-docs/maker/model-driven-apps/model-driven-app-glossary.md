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

The tool that is used in order to create model-driven apps.

It allows us to configure the site map, the tables required and the forms and views relevant to the app.

## Business Process Flow

Logic built into a given table to ensure that users complete records by updating fields in the correct order.  Authored initially using the Power Automate Experience.

A business process flow is arranged into Stages and each stage defines the fields that need to be completed at that time.
Business Process Flows express themselves as dots spread across the screen and each dot represents themselves as the relevant stage.

[Using screen readers within model-driven apps](https://docs.microsoft.com/en-us/power-automate/business-process-flows-overview)

## Business Rule Business

rules are server-side logic that is used with canvas or model-driven apps to set or clear values in one or many columns in a table. They can also be used to validate stored data or show error messages. Model-driven apps can use business rules to show or hide columns, enable or disable columns, and create recommendations based on business intelligence.

[Find out more about business rules here](https://docs.microsoft.com/en-us/learn/modules/define-create-business-rules/1-rules)  

## Chart

A visual representation of a table of data.  These can take the form of line, bar, pie chart or donut chart.

## Classic App Designer

Modern apps allow for the creation of both Canvas apps and model-driven apps.

In due course all model-driven apps will be authored as modern apps.

The ability to create model-driven apps usin g the app designer remains.  We call this the classic app designer authoring experience.

## Column

A field within a dataverse table (or entity).  Columns are similar to fields in databases and have different data types such as Text, Number, Date as well as data types less familiar to databases such as Phone, Email, File and Image.

The nature of the field type defines the type of data required by the column and also the controls (such as date picker or text box) that will be made available when using the control.

## Component

Components are element relevant to the creation of a model driven app.

Very often these will relate to the method of creation of the tables that make up the model driven app.

Components can be split into Data (tables, relationships, columns) UI (Site Map,forms,views) Logic (Business process flows, rules ..) and Visualization (Charts, dashboards, Power BI Tiles)

[Find out more about components](../../maker/model-driven-apps/model-driven-app-components.md)

## Connection

A model driven app is only ever connected to the data tables that reside in the same environment.  This connection can be considered as being native, as it never need to be set up within an environment.

Connections exist within the environment to enable other elements of the Power Platform to operate correctly.  Notably, canvas Power Apps and Power Automate flows do have the ability to make use of multiple connections.

Dashboard A method of presenting data relating to users in a graphic or chart form.

[Find out more about how to use Power BI within a model driven app](../../maker/model-driven-apps/use-power-bi.md)

## Data Model

A collection of related tables within Dataverse.

Where these are included in a solution these are a set of related tables built with the purpose of delivering the overall application.

## Database

The collective term for all the tables in Dataverse.

## Dataverse

The collective term for the tables, workflows, business process flows and related functionality that is provisioned within an environment when a database is created.  

Model-driven apps are tied to the Microsoft Dataverse database.

A Dataverse database contains data structures most closely associated with databases in addition to being able to hold model-driven apps, canvas apps, power automate flows.

[Find out more about Dataverse here](../../maker/data-platform/data-platform-intro.md)

## Dynamics

Microsoft Dynamics is a line of enterprise resource planning (ERP) and customer relationship management (CRM) software applications. Microsoft markets Dynamics applications through a network of reselling partners who provide specialized services.

Dynamics manifests itself as model-driven apps that make use of the Dataverse database within your environment.
Dataverse table and the two terms can and are used interchangeably.

In most areas of Dataverse we use the term

## Entity

An entity is another way of describing a  table.  However you will see elements of this terminology within the product and elsewhere on the internet.

## Environment

An environment is a space to store, manage, and share your organization's business data, data structures, apps, chatbots, and flows.

You can package up the various elements as solutions, and these solutions can be exported from one environment to another.

An environment can only ever have 1 Dataverse database and all your model-driven apps are tied to this database.

Often multiple environments are used to enable application life-cycle management.  For example you might have a development, test and production environment.

Environments are tied to a geographical region and can be a means of ensuring that the data physically stays in the correct geographical region.

[Find out more about environments here](https://docs.microsoft.com/en-us/power-platform/admin/environments-overview)

## Publish

The process by which we make the latest iteration of the app available to users within the environment.

## Relationship

The way in which fields between tables relate to each other.  There are 3 types of relationship 1 to many (1 Author to many Novels), many to 1 (many pages to 1 book) and Many to Many (many books borrowed by many people).

Model driven apps often contain tables with relationships between them.

## Security Role

A security role defines what people can see and do with a record.  

This relates to create, read, write, delete, update and append actions.

Security roles are created and users are put into security roles either as individual user names or by using active directory security groups.

[Find out more about security roles here](https://docs.microsoft.com/en-us/power-platform/admin/security-roles-privileges##%20security-roles)

Map

Site maps define the tables that are included within a model-driven app and the navigation experience by which users will have when moving between those apps.

A model-driven app is essentially a collection of tables, dashboards and views and these are described via the site map.

Both modern and classic methods of creating a model-driven app include site maps, however with a modern app you design the site map with a drag and drop experience whereas with the classic method you build the site map by hand.

To get to the site map from the modern app building experience you need to click switch to classic.

## Solution

A solution is a wrapper for a very wide range of components including tables (entities), cloud flows, security roles.

The exist in 2 forms.  Managed Solutions permit only a small amount of customisation whereas Unmanaged Solutions give desginers full control over the product that they are creating.

Unmanaged Solutions would be used by developers and these would be exported as managed solutions for use in production environments.

This allows for a high level of control around our application management life-cycle.

[Find out more about solutions here](../maker/data-platform/solutions-overview.md)

## Table

A table is a method of storing data in columns (or fields) within Dataverse.  We sometimes refer to them entities.

Every model-driven app must contain at least one table.  Much of the process of creating a model driven app is selecting the tables most relevant to solving the business problem.

Tables have views, forms and business rules associated with them.

Tables can relate to other tables and these are defined via the relationships that have been set up between them.

[Find out more about configuring tables here](../maker/data-platform/entity-overview.md)

## Unified Interface

The Unified Interface for model-driven apps provides a consistent and accessible user experience across devices—whether on a desktop, laptop, tablet, or phone.  The predecessor the the unified interface was know as the web interface.

[Find out more about the unified interface here](../user/unified-interface.md)

## Validate

The process by which we confirm if the model driven app has all the components required for it to function properly.

## View

A tabular representation of a dataverse table.  Table can have multiple views.

Views can be pre-filtered and it is possible to define the specific views that a model driven app will make available to users. 

[Find out more about views here](../developer/model-driven-apps/customize-entity-views.md)

## Workflow

A workflow is a series of functions or methods, called steps, that are performed sequentially and apply to data contained within our tables. The workflow can change the processing direction by using conditionals, referred to as conditional branches.

In many cases workflows can be replaced by Power Automate flows, and vice versa.

[!INCLUDE[footer-include](../../includes/footer-banner.md)]
