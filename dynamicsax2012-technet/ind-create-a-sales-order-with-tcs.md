---
title: (IND) Create a sales order with TCS
TOCTitle: (IND) Create a sales order with TCS
ms:assetid: 371805f5-0af8-434a-9a7c-43aeb1e8b4fc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664618(v=AX.60)
ms:contentKeyID: 49385695
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Create a sales order with TCS [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a sales order and calculate the TCS by attaching a TCS group to the sales order.

After posting the sales order, you can view the following details:

  - The invoice or payment amount and the TCS amount in the current currency in the **Amount origin** and **TCS** fields in the **Customer transactions** form. (Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. On the **Action Pane**, click **Transactions**.)

  - The posted voucher details in the **Voucher transactions** form. (Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Click **Transactions** \> **Voucher**.)

  - The TCS rate applied in the **Percent** field in the **Withholding tax transactions** form. (Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Click **Transactions**\>**Vouchers** \> **Posted withholding tax**.)

<!-- end list -->

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Click **Sales order** to open the **Create sales order** form.

3.  In the **Customer account** field, select a customer.
    

    > [!NOTE]
    > <P>The <STRONG>Calculate withholding tax</STRONG> check box should be selected on the <STRONG>Invoice and delivery</STRONG> FastTab in the <STRONG>Customers</STRONG> form for the selected customer.</P>



4.  In the **Sales order** form, on **Sales order lines** FastTab, in the **Item number** field, select or type the **Item number**, **Quantity**, and the **Unit price**

5.  Click the **Line details** tab, and then click the **Setup** tab.

6.  In the **TCS group** field, select the TCS group for the calculation of withholding tax.

7.  On **Sales order lines**, click **Product and supply**, and then click **Withholding tax** to open the **Temporary withholding tax transactions** form.

8.  In the **Adjusted withholding tax amount in total** field, verify the calculated TCS amount, and then close the form.

9.  In the **Sales order** form, on the **Invoice** FastTab, in the **Generate** group, click **Invoice**.

10. In the **Posting invoice** form, click **OK** to post the sales invoice.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

