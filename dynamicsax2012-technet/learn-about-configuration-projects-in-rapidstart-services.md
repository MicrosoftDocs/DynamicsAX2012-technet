---
title: Learn about configuration projects in RapidStart Services
TOCTitle: Learn about configuration projects in RapidStart Services
ms:assetid: 2b3bc542-74b9-4b39-8a94-b8340c3d8c31
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn193989(v=AX.60)
ms:contentKeyID: 52348269
ms.date: 09/23/2015
mtps_version: v=AX.60
f1_keywords:
- rapidstart designer, create questions, custom project
---

# Learn about configuration projects in RapidStart Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

In Microsoft Dynamics ERP RapidStart Services, a configuration project consists of the whole set of options and data that you can use to configure the original set of parameter options and records for an implementation of any version of Microsoft Dynamics AX 2012. The metadata for a configuration project includes information about the organization that the configuration project is for. This information includes the country or region, industry, and target version of Microsoft Dynamics AX 2012.

The configuration project is also used to specify the content and parameter settings that are loaded into Microsoft Dynamics AX 2012. As the Customer administrator, you must complete several tasks when you create a configuration project:

  - Decide how the configuration data is specified.

  - Assign business experts in the organization to answer groups of questions that are related to their areas of expertise.

  - Establish a connection to the target implementation of Microsoft Dynamics AX 2012.

  - Load the completed configuration data into that implementation.

All these tasks are performed in the context of a configuration project.

The rest of this topic provides information to help you understand more about configuration projects, and to help you create and manage configuration projects.

**In this topic**

  - Should I choose a default configuration or a custom configuration?

  - Should I create a new project or copy an existing project?

  - Which of the three configuration methods should I choose?

## Should I choose a default configuration or a custom configuration?

All configuration projects start with basic information about the company, such as where it is located, what industry it is in, and what version of Microsoft Dynamics AX 2012 it is using.

The remaining requirements for a configuration project depend on whether you are creating a project for a default configuration or a custom configuration.

The following two sections explain the difference between these configuration types.

## When to choose a default configuration project

If you want to quickly configure an implementation of Microsoft Dynamics AX 2012 to use settings and options that Microsoft has identified as the most common for your industry, you can use RapidStart Services to load these default settings into Microsoft Dynamics AX 2012. In this case, you do not have to select a configuration method or answer configuration questions.

For example, if you are a Partner implementation expert, you can create a default configuration project to demonstrate RapidStart Services to an existing or potential customer. This lets you provide a demo of the tool’s capabilities without having to spending time creating a template and answering configuration questions in the tool.

By using a default configuration project, you can load the following kinds of data, and other kinds, into Microsoft Dynamics AX 2012 in a few minutes:

  - Default data for more than 100 tables that are related to Financials, such as payment terms, aging periods, main accounts, journal names, and number sequences

  - Sample data for master records, such as customer lists, vendor lists, and product lists

To load the data for a default configuration project into a Microsoft Dynamics ERP implementation, you must first establish a connection between RapidStart Services and the target implementation of Microsoft Dynamics AX 2012..

For information about how to use a default configuration project, see [Create and load a configuration project that uses default settings in RapidStart Services](create-and-load-a-configuration-project-that-uses-default-settings-in-rapidstart-services.md).

## When to choose a custom configuration project

You can use the full capabilities of RapidStart Services to customize the configuration data that you load into Microsoft Dynamics AX 2012. When you use customized settings, you choose functional areas, each of which contains particular sets of questions that business experts in your company must answer. The configuration data that is loaded into your implementation of Microsoft Dynamics AX 2012 is based on the input that these business experts provide.

A custom configuration lets you start with a more robust original deployment of Microsoft Dynamics AX 2012 than you have if you use a default configuration. This deployment includes lots of information that is specific to your company.

You choose this option when you want to configure settings for more than just Financials. For example, you may want to configure Microsoft Dynamics AX 2012 to support one or more specific business processes or modules. Alternatively, if solutions that were developed by partners have been added to your implementation of Microsoft Dynamics AX 2012, you may want to create your own custom questions to support these solutions.


> [!NOTE]
> <P>You can include custom content when you choose to configure for a business process or module if the Designer for your organization has modified a business process or module template to include new content. The more common approach, however, would be for the Designer to create new functional areas that your organization needs, which you can then add to a custom template when you create a new project.</P>



When you use RapidStart Services to configure Microsoft Dynamics AX for business use, you work with a more extensive set of tools to create a custom configuration. For a custom configuration project, you must follow these steps:

1.  Choose a configuration method.

2.  Assign business experts in your company to answer groups of questions.

3.  Optional: Create additional questions to support solutions that were developed by partners. Before you do this, you must establish a connection to a Microsoft Dynamics AX 2012 implementation so that you can import the metatdata that is associated with the custom solution.

4.  Review the progress that is being made on answering questions.

5.  Establish a connection with a target implementation of AX 2012, if one was not already established to import metadata.

6.  Load data into Microsoft Dynamics AX 2012.

For information about how to create a custom configuration project, see [Create a custom configuration project and specify base information in RapidStart Services](create-a-custom-configuration-project-and-specify-base-information-in-rapidstart-services.md).

## Should I create a new project or copy an existing project?

When you are assigned to the Customer administrator role and begin working with RapidStart Services, you must create your first project from the beginning. However, after you create a project, you can make a copy of that project and use it as the basis for other projects. You can make a copy of an existing project either before or after the questions in the source configuration project have been answered.

When you create projects by copying existing projects, much of the final configuration data for the two implementations is the same. Therefore, by copying existing projects instead of creating projects from the beginning, you can save time.

You might choose to copy an existing project in situations such as these:

  - Related companies, such as subsidiaries or different business locations, run their own implementations of Microsoft Dynamics AX 2012. In these cases, you may have to modify only the basic company details and some configuration data before you can load the data from the copied project into the Microsoft Dynamics AX 2012 targets.

  - A partner is using RapidStart Services to launch multiple customers in the same industry. In these cases, the partner can create one industry-specific configuration project that is copied for every company. The partner then has to change only settings that must be unique for each customer.

For information about how to copy a project, see [Create a configuration project by copying another project in RapidStart Services](create-a-configuration-project-by-copying-another-project-in-rapidstart-services.md).

## Which of the three configuration methods should I choose?

RapidStart Services provides three configuration methods that you can use to create a custom configuration for your implementation of Microsoft Dynamics AX 2012:

  - Business process

  - Module

  - Custom template


> [!NOTE]
> <P>If you create a default configuration project, you do not have to choose a configuration method.</P>



The configuration method that you choose helps determine the range of questions that the business experts in your legal entity answer. The answers to these questions are used to compile the configuration data that is loaded into your implementation of Microsoft Dynamics AX 2012.

**The Business process configuration method**

You can choose from three end-to-end business processes. Each option provides a preselected set of questions that is based on functional areas and questions groups that support that business process.

  - Procure-to-pay

  - Order-to-cash

  - Acquire-to-retire

For example, both the Procure-to-pay and Acquire-to-retire business processes include question content for Base information, General ledger setup, Bank account management, and Tax and inventory management. The Procure-to-pay business process includes additional questions that are related to vendors and vendor interactions, whereas the Acquire-to-retire business process includes additional questions about customers and customer interactions.

**The Module configuration method**

The questions that your business experts answer are based on one or more modules in Microsoft Dynamics AX 2012, such as **Accounts receivable**, **General ledger**, **Human resources**, **Retail**, and **Inventory and warehouse management**. You choose which module or modules to include in your configuration project. Each option provides a set of questions that is based on the functional areas and questions groups that are associated with that module.

**The Custom template configuration method**

You select from all the available functional areas and question groups to determine which questions your business experts answer.

This method is best when you want to exercise more precise control over the process of configuring Microsoft Dynamics AX 2012. For example, you could first complete a configuration project for **Base information** and **General ledger**, load their data into Microsoft Dynamics AX, review the results, and make any adjustments that you need. Next, you might run another configuration project for **Accounts payable** and **Accounts receivable**, and continue with this approach until your modules or functional areas are configured.

This iterative approach provides the flexibility for an organization to configure one part of the system so it can be tested by business users while the Administrator or Designer for RapidStart Services continues preparing other modules or business processes for configuration.

## See also

[Create and load a configuration project that uses default settings in RapidStart Services](create-and-load-a-configuration-project-that-uses-default-settings-in-rapidstart-services.md)

[Create a custom configuration project and specify base information in RapidStart Services](create-a-custom-configuration-project-and-specify-base-information-in-rapidstart-services.md)

[Create a configuration project by copying another project in RapidStart Services](create-a-configuration-project-by-copying-another-project-in-rapidstart-services.md)

[Assign question groups to business experts in RapidStart Services](assign-question-groups-to-business-experts-in-rapidstart-services.md)

[Assign target completion dates to question groups in RapidStart Services](assign-target-completion-dates-to-question-groups-in-rapidstart-services.md)

[Answer questions in a configuration project in RapidStart Services](answer-questions-in-a-configuration-project-in-rapidstart-services.md)

[Review the progress on questions in a configuration project in Microsoft Dynamics ERP RapidStart Services](review-the-progress-on-questions-in-a-configuration-project-in-microsoft-dynamics-erp-rapidstart-services.md)

[Load configuration data into a Microsoft Dynamics ERP implementation from Microsoft Dynamics ERP RapidStart Services](load-configuration-data-into-a-microsoft-dynamics-erp-implementation-from-microsoft-dynamics-erp-rapidstart-services.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

