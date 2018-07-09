---
title: (THA) Set up unrealized VAT
TOCTitle: (THA) Set up unrealized VAT
ms:assetid: b63fc313-0769-46ee-8115-245c66704566
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg232430(v=AX.60)
ms:contentKeyID: 36059090
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (THA) Set up unrealized VAT [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You must enable the unrealized value-added tax (VAT) parameter in the **Sales tax codes** form before you can create a sales transaction containing unrealized VAT that is posted to the unrealized payable account.


> [!NOTE]
> <P>This feature is available only if the <STRONG>Sales tax</STRONG> and <STRONG>Unrealized sales tax</STRONG> configuration keys are selected.</P>



Use this procedure to set up a sales tax code, sales tax group, item sales tax group, and ledger posting group for unrealized VAT.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Create a sales tax code for unrealized VAT. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

3.  Click the **General** FastTab, and then select the **Unrealized tax** check box to allow a selected sales tax code for the calculation of unrealized tax.

4.  Close the form.

5.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

6.  Set up a sales tax group for unrealized VAT. For more information, see [Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md).

7.  Click the **Setup** FastTab to add the sales tax code that you set up in step 2.

8.  Close the form.

9.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.

10. Create an item sales tax group for unrealized VAT. For more information, see [Create item sales tax groups](create-item-sales-tax-groups.md).

11. Click the **Setup** FastTab to add the sales tax code that you set up in step 2.

12. Close the form.

13. Click **General ledger** \> **Setup** \> **Sales tax** \> **Ledger posting groups**.

14. Create a ledger posting group for unrealized VAT. For more information, see [Set up ledger posting groups for sales tax](set-up-ledger-posting-groups-for-sales-tax.md).

15. On the **General** FastTab, select the main account numbers in the **Unrealized tax payable** and **Unrealized tax receivable** fields to post the unrealized sales tax.

16. Close the form.

## See also

[(THA) Sales tax exchange rate adjustments (form)](https://technet.microsoft.com/en-us/library/hh227551\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

