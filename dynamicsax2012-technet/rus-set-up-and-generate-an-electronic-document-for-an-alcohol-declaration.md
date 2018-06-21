---
title: (RUS) Set up and generate an electronic document for an alcohol declaration
TOCTitle: (RUS) Set up and generate an electronic document for an alcohol declaration
ms:assetid: 9cf6a920-bbf9-4260-a859-72f15743c3c3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn494961(v=AX.60)
ms:contentKeyID: 60513660
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- queries
- query
- electronic documents
- Russia
- Forms.LedgerRRGEDocuments_W
- electronic reporting
- Forms.LedgerRRGEQueries_W
- electronic report
- electronic document
- alocohol declaration
- alocohol declarations
- RU - 00126
- electronic reports
- Russian federation
- RU - 00055
- MsDynAx060.Forms.LedgerRRGEDocuments_W
- MsDynAx060.Forms.LedgerRRGEQueries_W
---

# (RUS) Set up and generate an electronic document for an alcohol declaration [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you create and post invoices for alcohol transactions and generate the alcohol declaration, you can generate an electronic document for the alcohol declaration. This electronic document is submitted to the regional regulatory authority for processing.

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
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 7 or later</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Set up an extended data type for alcohol declaration fixed requisites. For more information, see <a href="rus-set-up-data-types-for-requisites.md">(RUS) Set up data types for requisites</a>.</p></li>
<li><p>Set up a fixed requisite for an alcohol declaration. For more information, see <a href="rus-set-up-a-fixed-requisite.md">(RUS) Set up a fixed requisite</a>.</p></li>
<li><p>Set up the periods of formats application directory that specifies the format to use for electronic reporting and the additional settings to correct, configure, and load the reports. For more information, see <a href="rus-set-up-the-periods-of-formats-application-directory.md">(RUS) Set up the periods of formats application directory</a>.</p></li>
<li><p>Set up templates for electronic reports. For more information, see <a href="rus-set-up-templates-for-electronic-reporting.md">(RUS) Set up templates for electronic reporting</a>.</p></li>
<li><p>Set up parameters for alcohol declarations and journals. For more information, see <a href="rus-set-up-parameters-for-alcohol-declarations-and-journals.md">(RUS) Set up parameters for alcohol declarations and journals</a>.</p></li>
<li><p>Create and post customer and vendor transactions for alcoholic items, and then create an alcohol declaration and a journal. For more information, see <a href="rus-generate-alcohol-declarations-and-journals.md">(RUS) Generate alcohol declarations and journals</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Create a query for alcohol declaration electronic reporting

Use the **Queries** form to create a query to retrieve values from database tables for alcohol declaration electronic reporting.

To create the query for alcohol declaration electronic reporting, follow these steps

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Queries**.

2.  Click **New** to create a query.

3.  In the **Query** field, enter an identification code for the query.

4.  In the **Query type** field, select one of the following query types:
    
      - **Simple**
    
      - **Alcohol declaration wholesale 5**
    
      - **Alcohol declaration wholesale 6**
    
      - **Alcohol declaration wholesale 7**
    
      - **Alcohol declaration retail 11**
    
      - **Alcohol declaration retail 12**

5.  Select the **Create requisites** check box to create parameters in the query directory when you create the query.

6.  Enter additional information for the query, if applicable, and then click **OK**. For more information, see [(RUS) Create a query for electronic reporting](rus-create-a-query-for-electronic-reporting.md).

7.  In the **Queries** form, click **Create requisites**.

8.  In the **Table name** field, select the database table to use to retrieve values for electronic documents, and then click **OK**.

You can click **Fixed requisites** to view the requisites that are set up for electronic reporting.

## 2\. Generate an electronic document for an alcohol declaration

Use the **Documents** form to generate and export an electronic reporting document for an alcohol declaration.

To generate the electronic document, follow these steps.

1.  Click **General ledger** \> **Reports** \> **External** \> **Electronic documents list**.

2.  Click **New** to create an electronic document, and enter the required details. For more information, see [(RUS) Documents (form)](https://technet.microsoft.com/en-us/library/jj852139\(v=ax.60\)).

3.  Click **Load** \> **Data**.

4.  In the **Journal number** field, select the journal number of the alcohol declaration journal.

5.  In the **Separate division ID** field, select the separate company division to include in the electronic document.

6.  Click **OK**.

7.  In the **Documents** form, click **Status** \> **Approved** to approve the document.

8.  Click **Export to** to specify the location to save the electronic document to.

9.  In the **Directory** and **File name** fields, enter the directory and path to save the electronic document to, and then click **OK**.

10. Click **Regional status** \> **Sent** to generate and send the electronic document to the regional authority for processing.

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
<td><p>Ensure that you select the <strong>Trade</strong> (LogisticsBasic) configuration key.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the <strong>Inquire about electronic documents</strong> (LedgerRRGEInquire) duty.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the privileges that are described in the following table.</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege</p></th>
<th><p>Name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Maintain alcohol declaration data</strong></p></td>
<td><p>AlcoholDeclarationMaintain_RU</p></td>
</tr>
<tr class="even">
<td><p><strong>View alcohol declaration data</strong></p></td>
<td><p>AlcoholDeclarationView_RU</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

