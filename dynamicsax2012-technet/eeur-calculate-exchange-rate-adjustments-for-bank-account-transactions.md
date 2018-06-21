---
title: (EEUR) Calculate exchange rate adjustments for bank account transactions
TOCTitle: (EEUR) Calculate exchange rate adjustments for bank account transactions
ms:assetid: 8f3ac3c6-f8a8-4e2f-af6e-9edb5608ae3f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ917354(v=AX.60)
ms:contentKeyID: 50952843
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (EEUR) Calculate exchange rate adjustments for bank account transactions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must revalue and adjust bank accounts if there is a difference in the exchange rate between the accounting currency and the reporting currency. This helps you to calculate the correct balance in the accounting currency and the reporting currency for the bank accounts.


> [!NOTE]
> <P>This process is applicable for Latvia, Lithuania, and the Czech Republic.</P>



1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  In the left pane, click **Number sequences**.

3.  In the **Number sequences** area, in the **Reference** field, select a number sequence for the **Bank - Exchange adjustment** parameter.

4.  Close the form.

5.  Click **General ledger** \> **Setup** \> **Currency** \> **Currency exchange rates**. In the **Currency exchange rates** form, you can define the exchange rate between two currencies or a currency pair. For more information, see [Currency exchange rates (form)](https://technet.microsoft.com/en-us/library/hh209477\(v=ax.60\)) and [Exchange rate types (form)](https://technet.microsoft.com/en-us/library/hh242857\(v=ax.60\)).

6.  Close the form.

7.  Click **General ledger** \> **Setup** \> **Ledger**. Select the main account in the **Unrealized gain** and the **Unrealized loss** fields that the exchange rates are posted for.

8.  Close the form.

9.  Click **Cash and bank management** \> **Periodic** \> **Bank** \> **Foreign currency revaluation**.

10. In the **On date** field, select the revaluation or the adjustment date.

11. In the **From currency** and the **To currency** fields, select the current currency code and the currency to which the adjustment is made.

12. Click **Select** to set up the bank account, and then click **OK**.

13. In the **Foreign currency revaluation** form, click **OK**. The adjustment for the bank account transactions on the selected date is calculated.
    

    > [!NOTE]
    > <P>You can view two separate transactions for the accounting currency and the reporting currency in the general ledger. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa556899(v=ax.60)">Bank transactions (form)</A> and <A href="https://technet.microsoft.com/en-us/library/aa583215(v=ax.60)">Voucher transactions (form)</A>.</P>



## See also

[(EEUR) Cash and bank management parameters (modified form)](https://technet.microsoft.com/en-us/library/jj710711\(v=ax.60\))

[Ledger (form)](https://technet.microsoft.com/en-us/library/hh209331\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

