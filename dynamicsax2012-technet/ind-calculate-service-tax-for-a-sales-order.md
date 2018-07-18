---
title: (IND) Calculate service tax for a sales order
TOCTitle: (IND) Calculate service tax for a sales order
ms:assetid: 3aba304d-3068-47e5-8e3a-9b565e547df2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664633(v=AX.60)
ms:contentKeyID: 49385710
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SalesTable
- Forms.TaxTmpWorkTrans
audience: Application User
ms.search.region: India
---

# (IND) Calculate service tax for a sales order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the **Sales order** form to create and post a sales order for which service tax is calculated. You can specify the service code for each sales order line before you post the sales order.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select or create a sales order.

3.  In the **Sales order** form, in the **Sales order lines** area, select or create a sales order line for an item of type **Service**.

4.  On the **Line details** FastTab, on the **Setup** tab, modify the sales tax group and the item sales tax group for the sales order line, if necessary. The sales tax group and the item sales tax group must contain tax codes that have a tax type of **Service tax**.

5.  On the **Tax information** tab, in the **Service code** field, select a service code for the sales order line. If the service code for an item of type **Service** is selected in the **Release products** form, the service code is selected as default for all sales order lines.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: The accounting code for the service is updated in the <STRONG>Accounting code</STRONG> field based on the service code that you select. For more information, see <A href="ind-set-up-service-codes-for-service-goods.md">(IND) Set up service codes for service goods</A>.</P>



6.  On the **Action Pane**, on the **Sell** tab, in the **Tax** group, click **Sales tax**. The **Temporary sales tax transactions** form opens, where you can view the calculated service tax.

7.  Close the form, and then post the invoice.
    

    > [!NOTE]
    > <P>The tax amount is not added to the inventory cost if the <STRONG>Load on inventory</STRONG> check box in the <STRONG>Item sales tax groups</STRONG> form is selected for a tax code. The tax amount is posted individually to the tax ledger accounts.</P>



## See also

[(IND) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj677998\(v=ax.60\))

[(IND) Service codes (form)](https://technet.microsoft.com/en-us/library/jj664830\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\))

  


