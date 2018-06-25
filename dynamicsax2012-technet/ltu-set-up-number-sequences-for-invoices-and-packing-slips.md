---
title: (LTU) Set up number sequences for invoices and packing slips
TOCTitle: (LTU) Set up number sequences for invoices and packing slips
ms:assetid: 58b2d7d1-b370-4daf-aa78-cccbe0a2c616
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn133078(v=AX.60)
ms:contentKeyID: 53348353
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Set up
- (LTU)
- invoices and packing slips
---

# (LTU) Set up number sequences for invoices and packing slips [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX, you can set up unique document number sequences for master data records and transaction records. If the tax authorities for your country or region assign a specific document number sequence or format to your organization, you can associate the number sequence to a document type in Microsoft Dynamics AX.

Use this procedure to set up a series of document numbers that are provided by the tax authority for numbering invoices and packing slips. When a new document is generated, one of the numbers in the series is assigned to the document. Each document number series is assigned to a user or user group. Only the designated user or user group can assign the numbers in the series to a document.

The numbers that are assigned to invoices and packing slips are included on printed documents. This includes the invoice register report and the packing slip registration journal report that you can send to the tax authority.

1.  Click **Organization administration** \> **Common** \> **Number sequences** \> **Registers** \> **Invoice numbering setup**.

2.  Click **New**.

3.  In the **Numbering** field, enter the prefix for the document number sequence.

4.  In the **Module** field, select the module in Microsoft Dynamics AX that uses the numbering series. The module that you select determines what options are available for you to select in the **Type** field. For customer invoices and customer packing slips, select the **Sales** option.

5.  In the **Account code** field, select whether the numbering series is available to all users, to only a specific user group, or to only a specific user.

6.  If you selected **Group** in the **Account code** field, select a user group in the **Code** field.
    
    If you selected **Table** in the **Account code** field, select a user in the **Code** field.

7.  Select the **Continue** check box to search for number series that are assigned to the selected user or user group.

## See also

[(LTU) Counters management (form)](https://technet.microsoft.com/en-us/library/jj911249\(v=ax.60\))

[(LTU) Invoice numbering setup (form)](https://technet.microsoft.com/en-us/library/jj911060\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

