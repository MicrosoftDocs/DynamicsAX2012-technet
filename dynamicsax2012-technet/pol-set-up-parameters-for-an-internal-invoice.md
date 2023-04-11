---
title: (POL) Set up parameters for an internal invoice
TOCTitle: (POL) Set up parameters for an internal invoice
ms:assetid: 7572e085-64bd-4812-9c5e-dcfdee054273
ms:mtpsurl: https://technet.microsoft.com/library/JJ678242(v=AX.60)
ms:contentKeyID: 49386964
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set up parameters for an internal invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Polish Fiscal Act of Goods and Services requires that all companies generate and submit internal invoices for EU purchases.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  On the **Number sequences** tab, select a number sequence for the **Internal invoice** reference type.

3.  Press CTRL+S or close the form.

4.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**.

5.  Press CTRL+N to create a ledger account. You can create ledger accounts for sales tax payable and receivable, and for use tax payable and receivable.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/hh209695(v=ax.60)">Main accounts - chart of accounts (form)</A>.</P>



6.  Press CTRL+S or close the form.

7.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Ledger posting groups**.

8.  On the **General** tab, in the **Sales tax payable** field, select the ledger account number for sales tax payable.

9.  In the **Sales tax receivable** field, select the ledger account number for sales tax receivable.

10. In the **Use tax expense** field, select the ledger account number for use tax receivable.

11. In the **Use tax payable** field, select the ledger account number for use tax payable.

12. Press CTRL+S or close the form.

13. Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

14. Press CTRL+N to create a sales tax code, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa553257(v=ax.60)">Sales tax codes (form)</A>.</P>



15. Press CTRL+S or close the form.

16. Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

17. Press CTRL+N to create a sales tax group, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa498345(v=ax.60)">Sales tax groups (form)</A>"Set up and use a sales tax group" in the Applications and Business Processes Help.</P>



18. On the **General** tab, select the **EU trade** check box to specify whether the tax group belongs to the European Union.

19. On the **Setup** tab, in the **Sales tax code** field, select the sales tax code created in steps 14 through 16.

20. Press CTRL+S or close the form.

## See also

[(POL) Post an internal invoice](pol-post-an-internal-invoice.md)

  


