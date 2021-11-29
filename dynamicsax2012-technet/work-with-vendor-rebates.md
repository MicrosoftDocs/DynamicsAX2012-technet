---
title: Work with vendor rebates
TOCTitle: Work with vendor rebates
ms:assetid: a5360df4-960d-489e-9738-92df9d08f91e
ms:mtpsurl: https://technet.microsoft.com/library/Dn497809(v=AX.60)
ms:contentKeyID: 62200128
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TAMVendRebateTable
- Forms.TAMVendRebateTableListPage
- MsDynAx060.Forms.TAMVendRebateTableListPage
- MsDynAx060.Forms.TAMVendRebateTable
- Forms.TAMVendRebateTrans
- MsDynAx060.Forms.TAMVendRebateTrans
- cumulate
- purchase order rebate
- vendor rebate
- vendor rebates
audience: Application User
ms.search.region: Global
---

# Work with vendor rebates 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A business can set up an agreement with one of its vendors in which the vendor provides a rebate for purchases. This topic describes how to create purchase orders that generate vendor rebate claims, and how to cumulate, approve, and process those rebate claims. For information about how to set up a vendor rebate agreement, see [Set up vendor rebate agreements](set-up-vendor-rebate-agreements.md).

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
<td><p>Required setup steps</p></td>
<td><p><a href="set-up-vendor-rebate-agreements.md">Set up vendor rebate agreements</a></p></td>
</tr>
</tbody>
</table>


## 1\. Create and invoice a purchase order

Create a purchase order that includes products that are eligible for a vendor rebate, and verify the rebate amount in the price details of the purchase order. When you invoice the purchase order and post the invoice, Microsoft Dynamics AX checks whether a vendor rebate agreement applies. If a vendor rebate agreement applies, the system generates a rebate claim.

To create and invoice a purchase order, follow these steps.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, in the **New** group, click **Purchase order**.

3.  Select the vendor account in the list, and then click **Yes** in the message box to confirm that you want to transfer vendor information.

4.  In the **Create purchase order** form, click **OK**.

5.  On the **Purchase order lines** FastTab, click **Add line**, and then enter the item number of a product that is eligible for a rebate from the vendor. Enter any additional line details that are required.

6.  Click **Purchase order line**, and then, under **View**, click **Price details**.
    

    > [!NOTE]
    > <P>If margin alerts have been set up in the parameters, the <STRONG>Margin estimation</STRONG> section at the top of the <STRONG>Price details</STRONG> form shows how the rebate affects the margin. For more information, see Set up margin alerts.</P>



7.  Click the **Vendor rebates** FastTab. If the purchase order line qualifies for a rebate, the vendor account is displayed here, together with the starting rebate amount.

8.  Close the **Price details** form.

9.  Continue to add lines to the purchase order as you require. Complete the purchase order, and then invoice it.

10. Post the invoice. The rebate claim is then generated.

## 2\. Process rebate claims

After rebate claims are created, you can cumulate the claims, if cumulation is required, and then review, approve, and process the claims. After claims are processed, the system creates and posts a vendor invoice that includes a negative value for the rebate amount.

To process rebate claims, follow these steps.

1.  Click **Procurement and sourcing** \> **Common** \> **Rebates** \> **Rebates**.

2.  The **Rebates** form displays the list of pending rebates. The system creates one rebate claim for each vendor invoice line. For each rebate claim, follow one of these steps, depending on how the rebates are cumulated for the vendor:
    
      - If the rebate agreement specifies that rebates are cumulated by invoice and approval is not required, no additional action is required. The system has processed the rebate claim and created a vendor invoice that includes a negative value for the rebate amount.
    
      - If the rebate agreement specifies that rebates are cumulated by invoice and approval is required, you must approve and process claims as follows:
        
        1.  On the **Action Pane**, in the **Functions** group, click **Approve**.
        
        2.  Select a vendor or a vendor rebate group, and then click **OK**. All rebate claims for the vendor or vendor rebate group are approved.
        
        3.  When you're ready to process the approved rebate claims, on the **Action Pane**, in the **Functions** group, click **Process**.
        
        4.  Select a vendor or a vendor rebate group, and then click **OK**. All rebate claims for the vendor or vendor rebate group are processed.
    
      - If the rebate agreement specifies that the rebates are cumulated by period, you must cumulate, approve, and process claims as follows:
        
        1.  On the **Action Pane**, in the **Functions** group, click **Cumulate**.
        
        2.  In the **Cumulate** form, select a vendor, and then click **OK**. The amount or quantity criteria in the vendor rebate agreement are applied to all the claims for that vendor, and the rebate amount is calculated for the group of claims.
        
        3.  Press F5 to update the list, and then double-click one of the rebate claims to open it. You can see the rebate amount that was applied to that invoice line.
            

            > [!NOTE]
            > <P>You can repeat steps a-c if more claims must be added to the group that is being cumulated. Each time that you cumulate, the system recalculates the rebate for the group of claims.</P>

        
        4.  When you're ready to approve claims, on the **Action Pane**, in the **Functions** group, click **Approve**. Select a vendor or a vendor rebate group, and then click **OK**. All rebate claims for the vendor or vendor rebate group are approved.
            

            > [!NOTE]
            > <P>After you approve claims for a vendor, you can add a new claim to the list and then cumulate that claim together with the claims that have already been approved. This process might change the rebate amount for each claim. Because rebate amounts for approved claims cannot be changed, any difference in the rebate amounts for the approved claims is added to a new line entry that you must approve separately.</P>

        
        5.  When you're ready to process claims, on the **Action Pane**, in the **Functions** group, click **Process**. Select a vendor or a vendor rebate group, and then click **OK**. All rebate claims for the vendor or vendor rebate group are processed.
        
        6.  At any stage in the process, you can view the accounting transactions that have occurred. On the **Action Pane**, in the **Inquiries** group, click **Rebate transactions** to view details of the transactions.

The **Status** field in the **Rebates** list shows the status of the rebate claims for each step in the process:

  - After claims have been cumulated, the status of each claim changes to **Calculated**.

  - After claims have been approved, the status changes to **Approved**. At this stage, the rebate accrual account has been debited, and the rebate expense account has been credited. These accounts temporarily hold the debits and credits, until final processing of the claims is performed.

  - After claims have been processed, the status changes to **Completed**. At this stage, the following events occur:
    
      - The rebate accrual postings that were created upon approval are reverted.
    
      - The sum of the rebate amounts is credited to the procurement expense account.
    
      - The sum of the rebate amounts is debited to the vendor balance that is shown in the vendor invoice.

You can optionally set up a workflow to approve and process vendor rebates.

## Next step

After rebate claims have been processed, you can invoice the vendor for the amount of the rebate.

## Related tasks

[Set up vendor rebate agreements](set-up-vendor-rebate-agreements.md)

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
<td><p><strong>Trade agreements</strong> configuration key</p>
<p><strong>Vendor rebates</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>Purchasing agent (to create purchase orders)</p>
<p>Accounts payable clerk (to invoice orders)</p>
<p>Accounts payable manager (to process rebate claims)</p></td>
</tr>
</tbody>
</table>


## See also

[Setting up and maintaining customer rebates](setting-up-and-maintaining-customer-rebates.md)

Set up margin alerts

  


