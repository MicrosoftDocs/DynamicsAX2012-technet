---
title: (RUS) Configure staff administration information for workers
TOCTitle: (RUS) Configure staff administration information for workers
ms:assetid: 57d8f537-6c14-4a65-b737-81f825a1c57f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn452007(v=AX.60)
ms:contentKeyID: 56713173
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- class
- payroll
- employee
- rank
- category
- Forms.DirPartyTable
- Forms.RHRMDocArg
- Forms.RHRMDocArgType
- Forms.RHRMMaritalStatus
- Forms.RHRMNationality
- Forms.RHRMPersonnelCategory
- Forms.RHRMPosition
- Forms.RHRMTradeCategory
- category type
- document arguments
- employee categories
- job title
- marital
- marital status
- nationality
- nationality status
- 57d8f537-6c14-4a65-b737-81f825a1c57f
- MsDynAx060.Forms.DirPartyTable
- MsDynAx060.Forms.RHRMDocArg
- MsDynAx060.Forms.RHRMDocArgType
- MsDynAx060.Forms.RHRMMaritalStatus
- MsDynAx060.Forms.RHRMPosition
- MsDynAx060.Forms.RHRMNationality
- MsDynAx060.Forms.RHRMPersonnelCategory
- MsDynAx060.Forms.RHRMTradeCategory
audience: Application User
ms.search.region: Russia
---

# (RUS) Configure staff administration information for workers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX 2012 R2 Payroll for Russia Feature Pack requires an established company structure, staff administration codes, and parameters to function efficiently. This topic describes the basic setup of staff administration codes for the nationality, marital status, document arguments, and the creation of job details for a worker.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisites</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R2 Payroll for Russia Feature Pack</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p>Related tasks</p></td>
<td><p>In the <strong>Party</strong> form, create a party as a person and make the person a core worker. For more information, see <a href="create-a-party-record.md">Create a party record</a> and <a href="global-address-books-and-address-reference-data.md">Global address books and address reference data</a>.</p>
<p>Make sure that a core worker is created as an employee. For more information, see <a href="rus-create-a-worker.md">(RUS) Create a worker</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Creating nationality and marital status codes

The nationality and marital status of a worker are represented using classification codes. A nationality code corresponds with the nation where the employee is employed. A marital code indicates the present marital status of the employee. Use the **Nationality** and **Marital status** forms to enter the identification code for the nationality and marital status for a worker. You can also enter a description for the identification codes. The information in these forms is used throughout the payroll process.

## 2\. Create employee categories

You can use the **Employee categories** form to categorize employees as executives, specialists, service staff, workers, and other classes. The category identification codes can be used later for job titles.

To create employee categories, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Structure** \> **Employee categories**.

2.  Click **New** to create a code for an employee category.

3.  You can use the fields on the **Parameters** tab to specify the report configuration for printing. Use the information in the following table to decide how the statutory report will be generated.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Fields</p></th>
    <th><p>Purpose</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Quantity on structures</strong></p></td>
    <td><p>Select this check box to include the number of workers for this rank, category, or class on the report.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Differentiation on categories</strong></p></td>
    <td><p>Select this check box to include rank, category, or classes of qualification on the report.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Up to</strong></p></td>
    <td><p>Enter the number of divisions by rank, category, or class.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The <STRONG>Up to</STRONG> field is available only if the <STRONG>Differentiation on categories</STRONG> check box is selected.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Category type</strong></p></td>
    <td><p>Select <strong>rank</strong>, <strong>category</strong>, or <strong>class</strong> as the category type.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The <STRONG>Category type</STRONG> field is available only if the <STRONG>Differentiation on categories</STRONG> check box is selected.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


## 3\. Create job titles, ranks, categories, and classes

You can create job titles in an organization, use them to establish either full-time or contractual positions, and employ workers to the positions.

To define job qualifications you can create the desired grades or levels for the following type of classifications: **rank**, **category**, or **class**. When a new position, either full-time or contractual is introduced in the organization, in addition to the selected job title, the desired type of classifications and the appropriate grades or levels can also be defined. This information is used to classify the requirements for the qualification of a person who is to be assigned to such a position.

Categories, classes, and ranks are sub levels that indicate different job grades. For example, if you have hired an employee for the newly created position of first class driver, you can print an employment order by stating that the employee is hired for the position of Driver, and that his class level is 01.

To create a job title, follow these steps:

## Create a job title

You can use the **Positions** form to create a job title for the company. To create a job title, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Structure** \> **Positions**.
    
    –or–
    
    Click **Payroll (Russia)** \> **Setup** \> **Department** \> **Positions**.

2.  Click **New** to create a job title.

3.  On the **Overview** tab, in the **Title** field, enter the job title code.

4.  In the **Code of a category** field, select the employee category code from the created in advance hierarchical structure of categories.
    

    > [!NOTE]
    > <P>In the <STRONG>Employee categories</STRONG> form, you can select parameters for staff administration reports. For more information, see 2. Create employee categories.</P>



5.  Optional: In the **Type of structure** field, select any one of the staff types:
    
      - **Air** - Indicates job titles of flight crew.
    
      - **Floating** - Indicates job titles of ships’ crew.

6.  On the **Description of a position** tab, in the **Note** field, enter additional information for the specified position.

## Create class, category, or rank of an employee

You can use the **Classes\\categories** form to create a class, category, or rank of an employee. To select the class, category, or rank of an employee, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Structure** \> **Classes\\categories**.

2.  Click **New** to create a class, category, or rank.

3.  On the **Overview** tab, in the **Number** field, enter a number for the selected category type.

4.  In the **Category type** field, select **rank**, **category**, or **class**.

5.  In the **Description** field, enter a description for the selected category type.

## 4\. Create document arguments

Document argument components include the source document code, which specifies the arguments of the employee due to which he is dismissed. You can define the lists of types of document arguments like application and memorandum. You can select any of these documents as an argument for a desired action when you register the document received from the employee. The document arguments may be created for one of the following events:

  - An employee applies to leave the company voluntarily.

  - The company introduces a new internal memorandum for organization restructure.

To create document arguments, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Setup** \> **Document-argument names**. You can set up codes for the original documents that are used in the **Document-arguments** form. Click **New** to create a new line.

2.  In the **Document type** field, enter a code for the document argument type.
    

    > [!NOTE]
    > <P>The values entered in the <STRONG>Document type</STRONG> field are user-defined. It could be any type of form like an application form or a company memorandum.</P>



3.  In the **Document name** field, enter the original document name, and then close the form.

4.  Click **Payroll (Russia)** \> **Staff administration** \> **Setup** \> **Document-arguments**. Click **New** to create a line, and specify the following field details.
    
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
    <td><p><strong>Document code</strong></p></td>
    <td><p>Retain or modify the code for the document argument.</p>
    <div class="alert">

    > [!NOTE]
    > <P>A document code is automatically displayed according to the number series that is assigned to the document code in the <STRONG>Parameters</STRONG> form.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document type</strong></p></td>
    <td><p>Select the document argument type code.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Document number</strong></p></td>
    <td><p>Enter the document argument number.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document date</strong></p></td>
    <td><p>Select the ending date for the completion of the original document.</p></td>
    </tr>
    </tbody>
    </table>


## Next step

[(RUS) Create a worker](rus-create-a-worker.md)

[(RUS) Hire, transfer, and dismiss a worker](rus-hire-transfer-and-dismiss-a-worker.md)

## Related tasks

[(RUS) Configure organizational information](rus-configure-organizational-information.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Select the <strong>CIS Payroll</strong> and <strong>CIS Staff administration</strong> configuration keys.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must have the following roles:</p>
<ul>
<li><p><strong>Human resource assistant</strong></p></li>
<li><p><strong>Human resource manager</strong></p></li>
</ul>
<p>To configure staff administration information for workers, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable human resource process</strong> (HcmHREnable)</p></li>
<li><p><strong>Inquire into human resources process</strong> (RPayHumanResourcesProcessInquire)</p></li>
<li><p><strong>Enable workforce management process</strong> (HcmWorkforceProcessEnable)</p></li>
<li><p><strong>Enable organizational process</strong> (HcmOrganizationalProcessEnable)</p></li>
<li><p><strong>Inquire into organizational process</strong> (HcmOrganizationalProcessInquire)</p></li>
<li><p><strong>Inquire into time management process</strong> (RPayTimeProcessInquire)</p></li>
<li><p><strong>Inquire into workforce management process</strong> (HcmWorkforceProcessInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To configure staff administration information for workers, you must be a member of a security role that includes the privileges that are described in the following table.</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privileges</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Maintain titles for jobs and positions</strong></p></td>
<td><p>HCMTitleMaintain</p></td>
<td><p>Create job titles, ranks, categories, and classes.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain job titles classes\ranks\categories list</strong></p></td>
<td><p>RPayJobTitlesMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain hierarchy of categories of employees</strong></p></td>
<td><p>RPayEmplHierarchyMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>View hierarchy of categories of employees</strong></p></td>
<td><p>RPayHierarchyView</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>View job titles' classes\ranks\categories list</strong></p></td>
<td><p>RPayJobTitilesView</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>View titles for jobs and positions</strong></p></td>
<td><p>HcmTitleView</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Create worker employment</strong></p></td>
<td><p>HCMEmploymentNewCreate</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain list of documents-arguments</strong></p></td>
<td><p>RPayDocListMaintain</p></td>
<td><p>Create document arguments.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain names of documents-arguments</strong></p></td>
<td><p>RPayDocNamesMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>View list of documents-arguments</strong></p></td>
<td><p>RPayDocArgListView</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>View names of documents-arguments</strong></p></td>
<td><p>RPayDocArgNameView</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Terminate a worker</strong></p></td>
<td><p>HCMWorkerTerminationMaintain</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


