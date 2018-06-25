---
title: About print management document types and modules
TOCTitle: About print management document types and modules
ms:assetid: 89c961e8-6e82-49d2-8b9e-2b89ccb1e076
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309745(v=AX.60)
ms:contentKeyID: 36058461
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- print
- print management
- printing
- management
- printer
- printers
---

# About print management document types and modules [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Print management works with several modules. These include Accounts receivable, Accounts payable, and Project management and accounting. You can see the supported documents for each module in the **Print management setup** form. For example, in Accounts receivable, the following documents are supported:

  - **Collection letter note**

  - **Confirmation**

  - **Customer account statement**

  - **Customer invoice**

  - **Free text invoice**

  - **Interest note**

  - **Quotation**

  - **Sales agreement confirmation**

  - **Sales order confirmation**

  - **Sales order packing slip**


> [!NOTE]
> <P>The <STRONG>Confirmation</STRONG> and <STRONG>Quotation</STRONG> document types are also used in Sales and marketing.</P>



You can set up print management original records, copy records, and conditional settings at the module, account, or transaction level.

Setting up print management at the module level requires the least amount of setup and minimizes the maintenance work when you have to change the settings, such as when you install new printers or change your existing printers. However, if your business needs require it, you can override the module settings for specific accounts or individual transactions.


> [!NOTE]
> <P>If you set up print management at the account or transaction level, the setup information will be more complex to manage when you add or change printers because you will have to change the settings for each individual account or transaction.</P>



## Configuration keys

Print management support for documents in the **Print management setup** form is controlled by the following configuration keys.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Module and configuration key</p></th>
<th><p>Document type</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Accounts receivable</strong></p>
<p>Quotations (QuotationBasic)</p>
<p>Trade (LogisticsBasic)</p></td>
<td><p>Confirmation</p>
<p>Quotation</p></td>
</tr>
<tr class="even">
<td><p><strong>Accounts receivable</strong></p>
<p>Trade (LogisticsBasic)</p></td>
<td><p>Customer invoice</p>
<p>Sales order confirmation</p>
<p>Sales order packing slip</p></td>
</tr>
<tr class="odd">
<td><p><strong>Accounts receivable</strong></p>
<p>General ledger (LedgerBasic)</p></td>
<td><p>Customer account statement</p>
<p>Free text invoice</p></td>
</tr>
<tr class="even">
<td><p><strong>Accounts receivable</strong></p>
<p>Collection letter (CustCollectionLetter)</p></td>
<td><p>Collection letter note</p></td>
</tr>
<tr class="odd">
<td><p><strong>Accounts receivable</strong></p>
<p>Interest (CustInterest)</p></td>
<td><p>Interest note</p></td>
</tr>
<tr class="even">
<td><p><strong>Accounts receivable</strong></p>
<p>Purchase and Sales Agreement (TradeBlanketOrder)</p></td>
<td><p>Sales agreement confirmation</p></td>
</tr>
<tr class="odd">
<td><p><strong>Accounts payable</strong></p>
<p>Trade (LogisticsBasic)</p></td>
<td><p>Purchase order</p>
<p>Purchase order product receipt</p>
<p>Purchase order receipts list</p>
<p>Request for quotation</p>
<p>Request for quotation - accept</p>
<p>Request for quotation - reject</p>
<p>Request for quotation - return</p>
<p>Vendor invoice</p></td>
</tr>
<tr class="even">
<td><p><strong>Accounts payable</strong></p>
<p>Purchase and Sales Agreement (TradeBlanketOrder)</p></td>
<td><p>Purchase agreement confirmation</p></td>
</tr>
<tr class="odd">
<td><p><strong>Project management and accounting</strong></p>
<p>Project (ProjBasic)</p></td>
<td><p>Project invoice</p></td>
</tr>
<tr class="even">
<td><p><strong>Inventory and warehouse management</strong></p>
<p>Trade (LogisticsBasic)</p></td>
<td><p>Picking list</p></td>
</tr>
</tbody>
</table>


## See also

[About print management originals, copies, and settings](about-print-management-originals-copies-and-settings.md)

[Set up print management for a module](set-up-print-management-for-a-module.md)

[Set up print management for a customer or vendor](set-up-print-management-for-a-customer-or-vendor.md)

[Set up print management for a transaction](set-up-print-management-for-a-transaction.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

