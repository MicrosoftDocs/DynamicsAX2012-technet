---
title: "What's new: Financial dimensions framework"
TOCTitle: Financial dimensions framework
ms:assetid: 9fe71c7a-f872-41dd-bd98-93ea26946c51
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527192(v=AX.60)
ms:contentKeyID: 59623321
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Financial dimensions framework 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Financial dimensions are data classifiers that are used for financial reporting. Financial dimensions identify information such as the purpose, cost center, and department. Financial dimensions have changed considerably since Microsoft Dynamics AX 2009.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>Conditionally required. If you are using this feature in an earlier version, significant changes have been made and you must review this topic.</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Technical decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

Financial dimensions are now more easily adapted to fit your requirements. Many aspects of data entry have been streamlined and simplified, and you can view more detailed financial information and information about transactions.

## Special considerations

You must complete certain steps in the Pre-upgrade checklist before you can upgrade to Microsoft Dynamics AX 2012. In AX 2009, you could create ledger account categories and financial dimensions for each company. In AX 2012, the main account categories and financial dimensions that you create are shared and can be used by any of the legal entities that are set up in Microsoft Dynamics AX. Therefore, you must select the main account categories and financial dimension sets that can be shared between the legal entities.


> [!NOTE]
> <P>Financial dimension sets were known as dimension focuses in earlier releases. Financial dimension sets are shared by all the legal entities that are set up in the <STRONG>Legal entities</STRONG> form. Financial dimension sets in AX 2012 are not the same as the dimension sets in earlier versions of Microsoft Dynamics AX.</P>



## Comparison with AX 2009

Financial dimensions have changed considerably since AX 2009. The dimensions framework from earlier versions has been removed, and the financial dimensions framework in AX 2012 is new. AX 2012 also includes changes to the following areas:

  - Financial dimensions

  - Charts of accounts

  - Account structures

  - Account dimension values on transactions

  - Financial statements and reporting

  - Analyzing ledger cubes

## Financial dimensions

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Add an unlimited number of financial dimensions.</p></td>
<td><p>Users could create a limited number of financial dimensions:</p>
<ul>
<li><p>Three default dimensions</p></li>
<li><p>Seven user-defined dimensions</p></li>
</ul></td>
<td><p>Users can create an unlimited number of financial dimensions.</p></td>
<td><p>Accounting tracking and reporting can be more complex.</p></td>
</tr>
<tr class="even">
<td><p>Create financial dimensions more easily.</p></td>
<td><p>Financial dimensions were created one at a time by using a wizard. This wizard required that the user compile and synchronize before the dimension changes took effect.</p></td>
<td><p>Financial dimensions can be created by using a form. The process resembles the setup tasks for other base data.</p></td>
<td><p>Financial dimensions are easier to create and use.</p></td>
</tr>
<tr class="odd">
<td><p>Rename default financial dimensions.</p></td>
<td><p>You could rename the default financial dimensions, but the process was complex and often required IT assistance.</p></td>
<td><p>Users can create and rename any financial dimension without assistance from IT.</p></td>
<td><p>You can easily modify the default financial dimensions. Customizations are not required.</p></td>
</tr>
<tr class="even">
<td><p>Link financial dimensions to an entity.</p></td>
<td><p>A user could track an existing entity, such as a customer, vendor, or site, as a dimension. However, the user had to manually define every instance of the entity as a financial dimension value.</p></td>
<td><p>Users can link a financial dimension to an entity in the system and use the values of the entities as the financial dimension themselves.</p></td>
<td><p>Financial dimensions are easier to use.</p></td>
</tr>
<tr class="odd">
<td><p>Define a date range for financial dimension values.</p></td>
<td><p>Users could not define a date range to specify when financial dimension values could be entered or posted on transactions.</p></td>
<td><p>A date range can be entered on each financial dimension value.</p></td>
<td><p>There are additional controls for date-sensitive activities.</p></td>
</tr>
</tbody>
</table>


## Charts of accounts

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up a chart of accounts, and use it for all legal entities in your organization.</p></td>
<td><p>Charts of accounts were specific to one legal entity.</p></td>
<td><p>You can use the same chart of accounts for multiple legal entities.</p></td>
<td><p>Charts of accounts are easier to create and use.</p></td>
</tr>
</tbody>
</table>


## Account structures

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Include a financial dimension as a segment in one or more account structures.</p></td>
<td><p>Users could not assign a dimension to one or more dimension sets.</p></td>
<td><p>A financial dimension can be included in one or more account structures.</p></td>
<td><p>Financial dimensions are easier to use.</p></td>
</tr>
<tr class="even">
<td><p>Set up an account structure more easily.</p></td>
<td><p>The process of setting up an account structure was complex and required several steps.</p></td>
<td><p>The process of setting up an account structure is easier, and fewer steps are required.</p></td>
<td><p>Account structures are easier to configure.</p></td>
</tr>
<tr class="odd">
<td><p>View a valid date range for a combination of dimension values.</p></td>
<td><p>No date range was available to tell users when a dimension value combination could be used on a transaction.</p></td>
<td><p>An active date range can be entered on a node of an account structure.</p></td>
<td><p>There are additional controls for date-sensitive activities.</p></td>
</tr>
<tr class="even">
<td><p>View required dimensions.</p></td>
<td><p>All dimensions were displayed to the user at all times, and there was no visual indication of the dimensions that had to be filled in.</p></td>
<td><p>Users can define an unlimited number of account structures. Although a user can assign a range of main account numbers to an account structure, each instance of a main account number can be assigned to only one account structure.</p></td>
<td><p>The data entry process is improved.</p></td>
</tr>
</tbody>
</table>


## Account dimension values on transactions

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Enter the main account numbers and dimensions in the same location.</p></td>
<td><p>The dimensions were displayed and entered on a separate tab. Therefore, the flow of data entry was interrupted.</p></td>
<td><p>You can use the new account number entry control to enter a main account and dimension in the same location.</p></td>
<td><p>The data entry process is improved.</p></td>
</tr>
</tbody>
</table>


## Financial statements and reporting

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Print financial statements to Microsoft Excel.</p></td>
<td><p>Users could not print financial statements to Excel.</p></td>
<td><p>Users can print financial statements to Excel.</p></td>
<td><p>Users can use all the features in Excel.</p></td>
</tr>
</tbody>
</table>


## Analyzing ledger cubes

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View detailed financial dimensions.</p></td>
<td><p>Only three default dimensions were available for analysis in the cubes.</p></td>
<td><p>All dimensions that are created in Microsoft Dynamics AX are available in the financial cubes.</p></td>
<td><p>Financial analysis can be more detailed.</p></td>
</tr>
</tbody>
</table>


## More information

For more information about financial dimensions, see the white paper [Implementing the Account and Financial Dimensions Framework for Microsoft Dynamics AX 2012 Applications](http://go.microsoft.com/fwlink/?linkid=213133%26clcid=0x409).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

