---
title: Register serial numbers for a sales order
TOCTitle: Register serial numbers for a sales order
ms:assetid: 282f5705-b1d3-43fd-a86a-58f030937448
ms:mtpsurl: https://technet.microsoft.com/library/Dn497734(v=AX.60)
ms:contentKeyID: 62200046
author: Khairunj
ms.date: 01/08/2016
mtps_version: v=AX.60
f1_keywords:
- Classes.SalesFormLetter_Invoice
- Classes.SalesFormLetter_PackingSlip
- invoice
- Forms.EcoResTrackingDimensionGroup
- packing slip
- sales process
- sale
- serial number
- serial
audience: Application User
ms.search.region: Global
---

# Register serial numbers for a sales order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to enable serial numbers for use only in the sales process.

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
<td><p><strong>Tracking dimension groups</strong></p></td>
<td><p>Enable serial number registration in the sales process by selecting the <strong>Active in sales process</strong> check box. For more information, see the section titled “Enable serial number registration in the sales process” in this topic.</p></td>
</tr>
<tr class="even">
<td><p><strong>Form setup</strong></p></td>
<td><p>Specify that serial numbers are printed on packing slips and invoices by selecting the <strong>Serial number</strong> check box on the <strong>Invoice</strong> and <strong>Packing slip</strong> tabs.</p></td>
</tr>
</tbody>
</table>


## Enable serial number registration in the sales process

Before you can register serial numbers for products in the sales process, you must enable serial numbers for the sales process on the tracking dimension group, and assign the tracking dimension group to the product. You can enable serial numbers in the sales process for a tracking dimension group only if the tracking dimension group has not been used to create transactions.

When you enable serial numbers for the sales process in the tracking dimension group, all other selections for serial numbers are cleared except the **Blank issue allowed** check box. You can select the check box to allow products to be packed or invoiced without registering serial numbers.

To enable serial numbers for the sales process, follow these steps:

1.  Click **Product information management** \> **Setup** \> **Dimension groups** \> **Tracking dimension groups**.

2.  In the **Serial number** row, select the **Active in sales process** check box.

3.  Optional: To allow products to be issued without registering serial numbers, select the **Blank issue allowed** check box.
    

    > [!NOTE]
    > <P>Normally, the <STRONG>Capture serial</STRONG> field and the <STRONG>Active</STRONG> check box are not used when you register serial numbers in the sales process. However, if you have Microsoft Dynamics AX 2012 R3 CU10 or KB 3072929 installed, you can use the <STRONG>Capture serial</STRONG> field to specify the following:</P>
    > <OL>
    > <LI>
    > <P><STRONG>None</STRONG> – Use this option if you want let the user manually select where to capture sales serial number. This could be from the packing slip, invoice, picking list registration, or load lines.</P>
    > <LI>
    > <P><STRONG>Picking</STRONG> – Capture the sales serial number when picking more than one serial number controlled item, using the mobile device.</P>
    > <LI>
    > <P><STRONG>Packing</STRONG> – Capture sales serial numbers when closing a container using the packing station.</P></LI></OL>
    > <P>For more information on how to use these options, see the <A href="https://blogs.msdn.com/b/dynamicsaxscm/archive/2015/12/07/enable-picking-of-sales-serial-number-items-with-r3-warehouse-management-processes.aspx">Dynamics AX SCM R&amp;D Team blog</A></P>



## Register serial numbers on a packing slip or invoice

To register serial numbers on the packing slip or invoice for a sales order, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create or select the sales order. For more information, see [Sales orders overview](sales-orders-overview.md).

3.  To register serial numbers on the packing slip or invoice, do one of the following:
    
      - Packing slip - On the **Action Pane**, on the **Pick and pack** tab, in the **Generate** group, click **Packing slip**.
    
      - Invoice - On the **Action Pane**, on the **Invoice** tab, in the **Generate** group, click **Invoice**.

4.  In the **Posting invoice** or **Packing slip posting** form, click the **Lines** tab, and then click **Update line**. Select **Register serial numbers**.

5.  Register serial numbers by using one of the following methods:
    
      - If you are using a scanner, on the **Action Pane**, in the **Set scan mode** group, click **Add**. When you scan the serial number, the number appears in the list of serial numbers.
        

        > [!TIP]
        > <P>To remove a serial number, select <STRONG>Remove</STRONG>, and then scan the serial number again.</P>

    
      - If you are typing the serial number, enter the number in the **Serial number** field, and then click **Add**.
        

        > [!NOTE]
        > <P>If blank issues are not allowed and a serial number cannot be read or scanned, you can add a blank registration for the item by clicking <STRONG>Not readable</STRONG>. If needed, you can update the serial number later. For more information, see the section titled “Change a registered serial number” in this topic.</P>



## Register serial numbers on a return order

To register serial numbers on a return order, create or select the return order, and then follow the steps for registering serial numbers for packing slips. The steps are described in the section titled “Register serial numbers on a packing slip or invoice” in this topic.

## Change a registered serial number

You can change the serial numbers for packing slips or invoices only if the invoice is not posted.

To change a registered serial number, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select the sales order, and then use the following steps to update the packing slip or invoice:
    
      - Packing slip - On the **Action Pane**, on the **Pick and pack** tab, in the **Generate** group, click **Packing slip**.
    
      - Invoice - On the **Action Pane**, on the **Invoice** tab, in the **Generate** group, click **Invoice**.

3.  Click the **Lines** tab, and then click **Update line**. Select **Register serial numbers**.

4.  On the **Serial numbers** form, select the serial number to change. Click **Change serial number**, and then enter or select the new serial number in the **New serial number** field.

## View the serial numbers that were registered for a packing slip or invoice

To view the serial numbers that were registered for a packing slip or invoice, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select the sales order, and then do one of the following:
    
      - To view the serial numbers that were registered on the packing slip, on the **Action Pane**, on the **Pick and pack** tab, in the **Journals** group, click **Packing slip**.
    
      - To view the serial numbers that were registered on the invoice, on the **Action Pane**, on the **Invoice** tab, in the **Journals** group, click **Invoice**.

3.  Click the **Lines** tab, and then click **Inquiries**. Select **Serial numbers**.

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
<td><p><strong>Security roles</strong></p></td>
<td><p>This functionality is available to all roles that can maintain packing slips and invoices. The following duties enable workers to correct serial numbers, and register blank entries for serial numbers that cannot be read or scanned:</p>
<ul>
<li><p><strong>Maintain serial number corrections</strong></p></li>
<li><p><strong>Maintain registration of non-readable serial numbers</strong></p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[About registering serial numbers in the sales process](about-registering-serial-numbers-in-the-sales-process.md)

  


