---
title: (IND) Post transaction reversals for purchase orders
TOCTitle: (IND) Post transaction reversals for purchase orders
ms:assetid: 021152e6-b3f1-4ed5-8e6c-503a9f4baeee
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664431(v=AX.60)
ms:contentKeyID: 49385521
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Post transaction reversals for purchase orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



In a business transaction, there is a delay from the time an order is invoiced to the time that a credit note is raised. During this period, the rate of tax on the purchase order might change. You can either levy the tax rate applicable when the order was invoiced or the tax rate applicable when the credit note is raised.

When the credit note is posted, the vendor account is debited, and the inventory with taxes and charges is credited.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order, and on the **Action Pane**, in the **Purchase** group, click **Credit note**.

2.  In the **Create credit note** form, select the **Tax as per original invoice** check box to calculate the tax that is based on the rate applicable on the date when the original order was invoiced.
    

    > [!NOTE]
    > <P>If the <STRONG>Tax as per original invoice</STRONG> check box is not selected, the calculation of the sales tax is based on the date when the credit note was raised.</P>



3.  Enter details for the credit note.

4.  Click **OK** in the **Create credit note** form.

5.  In the **Purchase orders** form, validate and post the transaction.

## See also

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj664798\(v=ax.60\))

[(IND) Copy purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj664580\(v=ax.60\))

[(IND) Chart of accounts (modified form)](https://technet.microsoft.com/en-us/library/jj677830\(v=ax.60\))

[(IND) Vendors (modified form)](https://technet.microsoft.com/en-us/library/jj664890\(v=ax.60\))

  


