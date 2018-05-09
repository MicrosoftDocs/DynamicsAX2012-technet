---
title: (POL) Create a NIP record to define VAT register data
TOCTitle: (POL) Create a NIP record to define VAT register data
ms:assetid: 77cd2350-264e-4684-bdd4-57d66e7c26e7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678244(v=AX.60)
ms:contentKeyID: 49386965
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (POL) Create a NIP record to define VAT register data 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The NIP table holds data about vendors or customers that you do business with only one time, and that do not have accounts with your legal entity. This data includes customer or vendor names, identification codes, addresses, and tax exempt numbers. For customers and vendors that you regularly do business with, this data is drawn from account records. You can use the data that is added to the NIP table when you have to post sales tax but do not know the vendor or customer account, or when the data in the value-added tax (VAT) register is different from the data that is assigned to the vendor or customer account.

You can use the **NIP table** form to create a NIP record to define the data that is used to post sales taxes to the VAT register. The code of the NIP table can be assigned to the general journal lines when the sales taxes are posted.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **NIP table**.

2.  In the **Name** field, enter the customer or vendor name.

3.  In the **Code** field, enter a unique number for the customer or vendor.

4.  In the **NIP number** field, enter the tax exempt number.

5.  On the **Address** tab, in the **Address** field, enter the address for the customer or vendor.

## See also

[(POL) NIP table (form)](https://technet.microsoft.com/en-us/library/jj678287\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

