---
title: "What's new: Address book"
TOCTitle: Address book
ms:assetid: 2e7fc997-9cd3-4cb0-94f7-f4a3d17702d6
ms:mtpsurl: https://technet.microsoft.com/library/Dn507095(v=AX.60)
ms:contentKeyID: 59623185
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Address book 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2012, the address book functionality has been enhanced. You can now create multiple address books instead of creating virtual companies. You can also control access to address books by granting privileges based on teams or legal entities. Additionally, your Human resources department can now create applicant records directly from the **Applicant** form.

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
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>Accounts payable</p>
<p>Accounts receivable</p>
<p>Human resources</p>
<p>Sales and marketing</p>
<p>Procurement and sourcing</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

In AX 2012, you can define any number of address books, and assign teams or legal entities to those address books. In this manner, you can control which workers have access to specific address books. You can also select whether policies are enforced for a specific address book or for all address books in a legal entity in your organization.

Additionally, Human resource applicant records can be created from the **Applicant** form and stored in the address book.

## Comparison with Microsoft Dynamics AX 2009

The global address book has changed considerably since AX 2009. AX 2012 includes changes to the following areas:

  - Functionality

  - Security

  - Applicant records

## Functionality

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
<td><p>Set effective dates for information.</p></td>
<td><p>No information about effective dates was provided for names or locations.</p></td>
<td><p>Users can set ranges of effective dates for names and locations. Users can also set communication information for vendors, employees, and transactions.</p></td>
<td><p>Information is kept up to date.</p></td>
</tr>
<tr class="even">
<td><p>Have multiple address books.</p></td>
<td><p>Only one address book could be created per virtual company.</p></td>
<td><p>An organization can create multiple address books to store common party records in the same place.</p></td>
<td><p>Party records can be organized by record type, and specific party records can be made available only to specific teams or legal entities.</p></td>
</tr>
<tr class="odd">
<td><p>Synchronize with Microsoft Outlook.</p></td>
<td><p>Only minimal address information was synchronized.</p></td>
<td><p>Contact synchronization with Outlook is enhanced, and multiple address purposes can be defined for multiple addresses.</p></td>
<td><p>Party records can contain address records that are used by the party for more than one reason.</p></td>
</tr>
</tbody>
</table>


## Security

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
<td><p>Secure party data according to user roles.</p></td>
<td><p>Security information was based on the companies that the user had access to.</p></td>
<td><p>Permissions to address books are granted based on the user’s teams or legal entities.</p></td>
<td><p>Security settings for address book permissions are tighter and more specialized.</p></td>
</tr>
<tr class="even">
<td><p>Import address reference data.</p></td>
<td><p>Table import was used to import address reference data.</p></td>
<td><p>Data is validated when it is entered, and users can set a default address based on ZIP/postal codes.</p></td>
<td><p>Data is validated when it is entered and can be used to set default addresses.</p></td>
</tr>
</tbody>
</table>


## Applicant records

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
<td><p>Create records for new applicants, existing applicants, and existing workers.</p></td>
<td><p>Not supported</p></td>
<td><p>Users can enter information about applications and new applicants, and modify records for existing applicants and existing workers.</p></td>
<td><p>Processing of applications is streamlined.</p></td>
</tr>
<tr class="even">
<td><p>Create an application for an existing applicant.</p></td>
<td><p>Applications were associated with applicants, employees, and contacts.</p></td>
<td><p>Applications are associated only with applicants, and applicant records can be created directly from the <strong>Applicant</strong> form.</p>
<p></p></td>
<td><p>The process for creating applications is streamlined.</p></td>
</tr>
<tr class="odd">
<td><p>Create an applicant record by using information from an existing address book record.</p></td>
<td><p>Applicant information could only be entered manually.</p></td>
<td><p>Applicant records can be created for an existing party record in the address book.</p></td>
<td><p>Manual data entry is reduced for applicants whose information is already stored in the address book.</p></td>
</tr>
</tbody>
</table>


## More information

For more information about the address book framework, see the white paper [Implementing the address book framework for Microsoft Dynamics AX 2012 applications](https://go.microsoft.com/fwlink/?linkid=213127).

  


