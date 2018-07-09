---
title: (IND) Post credit notes for sales orders
TOCTitle: (IND) Post credit notes for sales orders
ms:assetid: 6458b538-a785-4c8c-9179-539bc4835694
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677873(v=AX.60)
ms:contentKeyID: 49385837
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Post credit notes for sales orders [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



In a business transaction, there is a delay from the time that an order is invoiced to the time that a credit note is raised. During this period, the rate of tax on the sales order might change. You can either levy the applicable tax rate when the order is invoiced or the applicable tax rate when the credit note is raised.

When the credit note is posted, the customer account is credited, and the inventory with taxes and charges is debited.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Select a sales order and on the **Action Pane**, on the **Sell** tab, click **Credit note**.

2.  In the **Create credit note** form, select the **Tax as per original invoice** check box to calculate the tax that is based on the rate that was applicable on the date when the original order was invoiced.
    

    > [!NOTE]
    > <P>If the <STRONG>Tax as per original invoice</STRONG> check box is not selected, the calculation of the sales tax is based on the date when the credit note is raised.</P>



3.  Enter details for the credit note.

4.  Click **OK** in the **Create credit note** form.

5.  In the **Sales orders** form, validate and post the transaction.

## See also

[(IND) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj677998\(v=ax.60\))

[(IND) Customers (modified form)](https://technet.microsoft.com/en-us/library/jj678004\(v=ax.60\))

[(IND) Sales posting (modified form)](https://technet.microsoft.com/en-us/library/jj678044\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

