---
title: Create a custom configuration project and specify base information in RapidStart Services
TOCTitle: Create a custom configuration project and specify base information in RapidStart Services
ms:assetid: 0f3ea23e-056c-4045-b230-2a854bcf03a9
ms:mtpsurl: https://technet.microsoft.com/library/Dn193983(v=AX.60)
ms:contentKeyID: 52348238
author: tonyafehr
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- base information, rapidstart, create project, custom project
- templates, functional area, question group, question
---

# Create a custom configuration project and specify base information in RapidStart Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

When you configure Microsoft Dynamics AX 2012 by using Microsoft Dynamics ERP RapidStart Services, you can use just use just a basic set of default settings that are provided by Microsoft to set some basic financial options. Alternatively, you can start with a more robust deployment of Microsoft Dynamics AX 2012 that uses options and data that are specific to your organization. In this case, you can use the full capabilities of RapidStart Services to customize the configuration data that you load into Microsoft Dynamics AX. You use this option when you want to configure settings for one or more business processes or modules. You also use this option when you have added solutions to Microsoft Dynamics AX 2012 that were developed by partners or independent software vendors (ISVs), and you want to additional content to support these solutions.

As the Customer administrator for your organization, when you use customized settings, you choose questions that business experts in your company must answer. The input from these business experts is then included in a configuration file that you load into your implementation of Microsoft Dynamics AX 2012.

Use the procedures in this topic to create a custom configuration project for your company.


> [!NOTE]
> <P>For information that can help you decide whether to use a default configuration project or a custom configuration project, see <A href="learn-about-configuration-projects-in-rapidstart-services.md">Learn about configuration projects in RapidStart Services</A>.</P>



**In this topic**

Create a custom configuration project

Enter base information for a custom configuration project

## Create a custom configuration project

1.  In your browser, open online services for Microsoft Dynamics ERP at [http://www.dynamicsonline.com](https://go.microsoft.com/fwlink/p/?linkid=141031).

2.  Click **For Customers**, and then click **Sign in**.

3.  Sign in by using the Microsoft account (formerly Windows Live ID) that is associated with your customer account in online services.

4.  If your logon credentials are associated with more than one organization in RapidStart Services, on the **Choose your organization** page, click the name of the organization to work with.

5.  On the Customer Portal dashboard, click **Microsoft Dynamics® RapidStart**.

6.  In the main area of the **Getting started** page, click **Create a new project**.

7.  In the **Organization information** area, enter your organization’s name, address, and country or region. Then, in the **Industry** list, select the name of the industry that your organization works in.

8.  In the **Select a configuration option** area, select the **Customize my configuration settings** option.

9.  Click **Next** to open the **New project** page.

10. In the **Project name** field, enter a name to identify the configuration project in RapidStart Services.

11. In the **Method of configuration** field, select one of the following options:
    
      - **The Business process configuration method** – You can select from three end-to-end business processes: Procure-to-pay, Order-to-cash, and Acquire-to-retire. Each option provides a set of questions that is based on functional areas and question groups that support that business process.
    
      - **The Module configuration method** – The questions that your business experts answer are based on one or more modules in Microsoft Dynamics AX 2012, such as **Accounts receivable**, **General ledger**, **Human resources**, **Retail**, and **Inventory and warehouse management**. You select which module or modules to include in your configuration project. Each option provides a set of questions that is based on the functional areas and question groups that are associated with that module.
    
      - **The Custom template configuration method** – You select from all the available functional areas and question groups to determine which questions your business experts answer. This method is the best option when you want to exercise more precise control over the process of configuring Microsoft Dynamics AX 2012.

12. Click **Create project**.
    
    The **Base information** page opens.
    
    Base information is used to define the company information, fiscal calendars, and other information that is fundamental to your RapidStart Services configuration project. You should answer the questions on the **Base information** page before you answer any other questions in the project.
    
    Use the next procedure, [Create a custom configuration project and specify base information in RapidStart Services](create-a-custom-configuration-project-and-specify-base-information-in-rapidstart-services.md), to enter your organization’s base information.

## Enter base information for a custom configuration project

After you create a custom configuration project as described in the previous procedure, [Create a custom configuration project and specify base information in RapidStart Services](create-a-custom-configuration-project-and-specify-base-information-in-rapidstart-services.md), use this procedure to enter your organization’s base information on the **Base information** page. This procedure is the first step in customizing your implementation of Microsoft Dynamics AX 2012.

1.  In the **Organization information** question group, enter information about your organization in the fields.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>Enter the name of your company. This name is used in forms, on documents, and on reports throughout Microsoft Dynamics AX.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Code</strong></p></td>
    <td><p>Enter any three-letter or four-letter code to represent your legal entity in Microsoft Dynamics AX.</p>
    <p>A single Microsoft Dynamics AX database can hold many individual legal entities. The code that you enter here makes it easy to identify and switch between legal entities in the Microsoft Dynamics AX interface.</p>
    <p>If you specified a code for this legal entity when you installed Microsoft Dynamics AX, you must enter that same code here.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Address</strong></p></td>
    <td><p>Enter the primary street address of your legal entity.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Zip</strong></p></td>
    <td><p>Enter the ZIP Code or Postal Code where your legal entity is located.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>City</strong></p></td>
    <td><p>Enter the city or locality where your legal entity is located.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>State</strong></p></td>
    <td><p>Enter the state or province where your legal entity is located.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Country</strong></p></td>
    <td><p>Enter the country or region where your legal entity is located.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Address format</strong></p></td>
    <td><p>Enter the format to use for addresses in your Microsoft Dynamics AX environment. For example, for the United States, enter US.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Registration number</strong></p></td>
    <td><p>Enter the registration number that the government authority has on file for your legal entity.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Language</strong></p></td>
    <td><p>Enter the language to use in your Microsoft Dynamics AX interface. For example, for the United States, enter en-us.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Fiscal year start date</strong> and <strong>Fiscal year end date</strong></p></td>
    <td><p>Enter the start and end dates of the organization’s fiscal year.<strong>Period unit</strong> and <strong>Period quantity</strong> – Select the type of unit that your fiscal year is divided into, and specify how many fiscal units make up a fiscal period.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Number of fiscal years</strong></p></td>
    <td><p>Enter the number of fiscal years to include in your fiscal calendar.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Currency</strong></p></td>
    <td><p>Enter the standard three-letter code for your legal entity’s accounting currency. For example, for US dollars, enter <strong>USD</strong>.</p></td>
    </tr>
    </tbody>
    </table>


2.  Click the **Mark as complete** button for the **Organization information** question group.

3.  Answer the questions in the **Ledger** question group, and then click the **Mark as complete** button for this question group.

4.  Answer the questions in the **Currency** question group, and then click the **Mark as complete** button for this question group.
    

    > [!TIP]
    > <P>For information about how to answer the various kinds of questions in RapidStart Services, see <A href="answer-questions-in-a-configuration-project-in-rapidstart-services.md">Answer questions in a configuration project in RapidStart Services</A>.</P>



After you provide this base information, you can continue with other tasks that are related to the management of a custom configuration project:

  - [Assign question groups to business experts in RapidStart Services](assign-question-groups-to-business-experts-in-rapidstart-services.md)

  - [Assign target completion dates to question groups in RapidStart Services](assign-target-completion-dates-to-question-groups-in-rapidstart-services.md)

  - [Answer questions in a configuration project in RapidStart Services](answer-questions-in-a-configuration-project-in-rapidstart-services.md)

  - [Review the progress on questions in a configuration project in Microsoft Dynamics ERP RapidStart Services](review-the-progress-on-questions-in-a-configuration-project-in-microsoft-dynamics-erp-rapidstart-services.md)

  - [Load configuration data into a Microsoft Dynamics ERP implementation from Microsoft Dynamics ERP RapidStart Services](load-configuration-data-into-a-microsoft-dynamics-erp-implementation-from-microsoft-dynamics-erp-rapidstart-services.md)

## See also

[Learn about configuration projects in RapidStart Services](learn-about-configuration-projects-in-rapidstart-services.md)

[Create and load a configuration project that uses default settings in RapidStart Services](create-and-load-a-configuration-project-that-uses-default-settings-in-rapidstart-services.md)

[Create a configuration project by copying another project in RapidStart Services](create-a-configuration-project-by-copying-another-project-in-rapidstart-services.md)

  


