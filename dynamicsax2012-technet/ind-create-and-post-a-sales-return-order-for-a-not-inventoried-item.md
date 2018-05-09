---
title: (IND) Create and post a sales return order for a not inventoried item
TOCTitle: (IND) Create and post a sales return order for a not inventoried item
ms:assetid: c01ca6d3-1445-4aec-9ea5-b8bce85b414e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664861(v=AX.60)
ms:contentKeyID: 49386190
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- return
- sales
- India
- IND
- noninventoried
---

# (IND) Create and post a sales return order for a not inventoried item 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

All indirect taxes in India must be calculated and posted for negative stocked sales order lines, just as for negative inventoried lines. Indirect taxes include sales tax, value-added tax (VAT), excise tax, service tax, and customs tax. The calculation of indirect taxes also applies to negative inventoried sales order lines. Direct taxes, such as the calculation codes for Tax Deducted at Source (TDS) and Tax Collected at Source (TCS), restrict negative inventoried lines. These codes also apply to negative inventoried sales order lines.

Information about indirect taxes must be specified for a purchase order line before the purchase order line is posted.

1.  Click **Sales and marketing** \> **Common** \> **Return orders** \> **All return orders**. Open the return order that is ready for posting. On the **Action Pane**, on the **Return order** tab, in the **Return** group, click **Find sales order**.

2.  In the **Find sales order** form, enter the search criteria for the sales order that you are trying to locate, or locate the sales order in the list on the **Invoice** tab.

3.  Select the **Select all** check box to select all the sales order lines that are attached to the sales order, and then click **OK**.

4.  In the **Return order** form, on the **Action Pane**, click **Edit**.

5.  On the **Line details** FastTab, on the **General** tab, in the **Disposition code** field, select **Credit only**, and then close the form.
    
    If you select **Credit only** in the **Disposition code** field, the excise registers are not updated when the sales return order is posted.

6.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Open the sales order to work with.

7.  On the **Action Pane**, on the **Pick and pack** tab, click **Packing slip**.

8.  In the **Packing slip posting** form, specify the parameters to post and print the documents that are related to the sales order. For more information about this form, see [Sales posting (form)](https://technet.microsoft.com/en-us/library/aa550287\(v=ax.60\)).

9.  Click **OK** to post the packing slip.

10. In the **All sales orders** form, on the **Action Pane**, on the **Invoice** tab, in the **Generate** group, click **Invoice** to open the **Invoice posting** form. Click **OK** to post the invoice.
    
    When you post a purchase order that has a negative quantity, the indirect taxes are calculated.

11. To view the posted invoice in the **Voucher transactions** form, click **Invoice journal** \> **Voucher**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

