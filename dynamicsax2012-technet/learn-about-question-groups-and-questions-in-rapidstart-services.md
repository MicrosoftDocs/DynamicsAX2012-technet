---
title: Learn about question groups and questions in RapidStart Services
TOCTitle: Learn about question groups and questions in RapidStart Services
ms:assetid: e4f51b2a-5c3f-4175-bdf6-7de7fef0f9ab
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh413253(v=AX.60)
ms:contentKeyID: 36918944
ms.date: 09/23/2015
mtps_version: v=AX.60
f1_keywords:
- questions
- RapidStart Services
---

# Learn about question groups and questions in RapidStart Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

In Microsoft Dynamics ERP RapidStart Services, the responses to questions that are contained in the **Configure** area of RapidStart Services are used to create application configuration data. This configuration data is then loaded into an implementation of Microsoft Dynamics ERP.

Questions can be simple or complex. For example, a person who answers a simple question might have to enter the value for a single field in a Microsoft Dynamics ERP implementation, such as the accounting currency for a company. By contrast, a person who answers a complex question might have to populate a Microsoft Excel workbook with values for multiple fields in multiple tables, and then upload the completed workbook.

The current version of RapidStart Services includes questions that can be used to configure many business processes in numerous markets. However, you can extend the scope of RapidStart Services beyond the content that is provided by Microsoft by creating questions that are used to configure parameters in other business processes. These business processes can include business processes that are related to solutions that partners develop.


> [!NOTE]
> <P>To build questions that are based on partner-developed solutions, you must first import the required metadata from a target Microsoft Dynamics ERP implementation. For information about how to import metadata, see <A href="import-metadata-into-microsoft-dynamics-erp-rapidstart-services-from-a-microsoft-dynamics-erp-implementation.md">Import metadata into Microsoft Dynamics ERP RapidStart Services from a Microsoft Dynamics ERP implementation</A>.</P>



## Question types in RapidStart Services

When you create a question in the **Design** area of RapidStart Services, you can choose from five questions types. The type of question that you choose depends on the purpose of the question.

The following list describes the purpose of each question type:

  - **Field** – Update a single field in a table in a Microsoft Dynamics ERP implementation.

  - **Table** – Create multiple records in one or more Microsoft Dynamics ERP application tables by using Excel workbooks.

  - **Class** – Run code when the configuration project is loaded into a Microsoft Dynamics ERP implementation.

  - **Service** – Create multiple records in one or more tables in a Microsoft Dynamics ERP implementation by using Excel templates and any Application Integration Framework (AIF) service that is exposed by the Microsoft Dynamics ERP implementation. In the question content that is provided by Microsoft, questions of this type are used for master data records when multiple tables must be updated.

  - **Data Import/Export** – Create multiple records in one or more tables in a Microsoft Dynamics ERP implementation by using comma-separated value (CSV) templates and the Data Import/Export Framework. Questions of this type are typically used for more complex entities such as customers, vendors, and dimensions. However, the management of any area that has complex data can be simplified by defining a Data Import/Export Framework entity for it and then exposing this entity in a RapidStart Services question. Only one Data Import/Export Framework-based entity can be used in each question.
    
    All Data Import/Export Framework entities that are provided by Microsoft are automatically available in the RapidStart Services tool for you use with Data Import/Export Framework-based questions.

  - **Non-actionable** – Non-actionable questions do not update fields or tables in a Microsoft Dynamics ERP implementation. Instead, questions of this type are used to control the workflow when questions are being answered. You can enable or disable questions, based on the answer that is provided for a non-actionable question in the **Configure** area.
    
    For example, in a question group about the general ledger, the respondent answers “Yes” to the non-actionable question “Do you have to generate financial statements in multiple currencies?” In this case, questions that are used to enter a reporting currency and a maximum currency rounding difference are enabled and appear. If the respondent answers “No,” these questions do not appear.

## Control types for creating questions

Each question type has specific groups of controls that you use to create the questions. These control groups are displayed on a series of FastTabs. All five question types have controls for basic information and dependency information. The other control groups depend on the question type. The following table describes the control groups.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Control group</p></th>
<th><p>Description</p></th>
<th><p>Question type</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Basic information</strong></p></td>
<td><p>Enter data such as the name, text, description, and question type of a question. In this group, you can also specify whether a question is required, and whether it is visible in the <strong>Configure</strong> area.</p>
<div>

> [!NOTE]
> <P>In some cases, you might want to configure a parameter in a Microsoft Dynamics ERP implementation by using specific values, but without displaying the question to the person who is working in the <STRONG>Configure</STRONG> area. In these cases, you can choose not to display the question, and then specify the values that are loaded into the Microsoft Dynamics ERP implementation.</P>


</div></td>
<td><p>All</p></td>
</tr>
<tr class="even">
<td><p><strong>Dependency information</strong></p></td>
<td><p>Keep a question hidden unless the person who is answering configuration questions has selected a particular answer to a parent question.</p></td>
<td><p>All</p></td>
</tr>
<tr class="odd">
<td><p><strong>Action information</strong></p></td>
<td><p>Specify which field is updated in which table, and choose the type of control that is presented to the person who is answering the question, such as a text box or list.</p></td>
<td><p><strong>Field</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Validation information</strong></p></td>
<td><p>Specify how RapidStart Services makes sure that a valid response is entered for the question.</p></td>
<td><p><strong>Field</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Lookup information</strong></p></td>
<td><p>Specify whether the answer should be prepopulated in the <strong>Configure</strong> area, and where the prepopulated data should come from. If you prepopulate an answer, you can choose whether the answer is derived from an application table in Microsoft Dynamics ERP or from the answer to another question.</p></td>
<td><p><strong>Field</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Generate and upload workbook templates</strong></p></td>
<td><p>Create an Excel template that can be used to provide values for multiple fields in multiple tables. To respond to a question of the <strong>Table</strong> type, the person who is answering questions in the <strong>Configure</strong> area downloads the template to create a new workbook, enters values for the requested fields, and then saves and uploads the completed workbook.</p></td>
<td><p><strong>Table</strong>, <strong>Data Import/Export</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Class information</strong></p></td>
<td><p>Select a Microsoft Dynamics ERP class and method, and then use <strong>Validation information</strong> and <strong>Lookup information</strong> controls to finish configuring the question.</p></td>
<td><p><strong>Class</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Service information</strong></p></td>
<td><p>Select a Microsoft Dynamics ERP service and service operation, and then generate a template that can be downloaded and used to create a workbook in the <strong>Configure</strong> area.</p></td>
<td><p><strong>Service</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Enum information</strong></p></td>
<td><p>Provide alternate text for the enum values that are associated with the enum type that you selected in the <strong>Select the enum type to control question visibility</strong> field in the <strong>Basic information</strong> control group.</p></td>
<td><p><strong>Non-actionable</strong></p></td>
</tr>
</tbody>
</table>


## See also

[Learn about templates, functional areas, question groups, and questions in RapidStart Services](learn-about-templates-functional-areas-question-groups-and-questions-in-rapidstart-services.md)

[Create questions and question actions in RapidStart Services](create-questions-and-question-actions-in-rapidstart-services.md)

[Move a question in RapidStart Services](move-a-question-in-rapidstart-services.md)

[Create a question group in RapidStart Services](create-a-question-group-in-rapidstart-services.md)

[Data Migration Framework User Guide](data-import-export-framework-user-guide-dixf-dmf.md)

[Data Migration for Microsoft Dynamics AX 2012](https://informationsource.dynamics.com//rfpservicesonline/rfpservicesonline.aspx?docname=data+migration+dynamics+ax+2012%7cqj4jem76642v-8-857)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

