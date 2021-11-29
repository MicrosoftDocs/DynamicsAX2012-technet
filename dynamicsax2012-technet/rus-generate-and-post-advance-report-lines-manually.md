---
title: (RUS) Generate and post advance report lines manually
TOCTitle: (RUS) Generate and post advance report lines manually
ms:assetid: aeb4ce89-eb4d-4d00-b4b3-6e068d6b9c9f
ms:mtpsurl: https://technet.microsoft.com/library/JJ711513(v=AX.60)
ms:contentKeyID: 49387838
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Generate and post advance report lines manually
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate and post advance report lines manually 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

An advance report is used to report travel expenses that are incurred by an employee during a business trip. Use this procedure to generate and post advance report lines manually.

You can distribute the expense amount between different ledger dimensions. You can then view the ledger entries and verify the distribution of the expense amount.

1.  Click **Accounts payable** \> **Common** \> **Advance holders** \> **Advance reports**.

2.  Press CTRL+N to create a new advance report. For more information, see.

3.  Click the **Advance report lines** FastTab, and then click **Add line** to create a new line.

4.  In the **Disbursement date** field, enter the date of the document that describes the expense.

5.  In the **Document number** field, enter the number of the confirming document.

6.  In the **Document name** field, enter the name of the confirming document.

7.  In the **Currency** field, select the currency that is used for the transaction.

8.  In the **Amount** field, enter the amount that is spent for the transaction.

9.  In the **Confirmed amount of advance report** field, enter the confirmed expense for the advance report.

10. In the **Ledger account** field, select the general ledger account that the expense belongs to.

11. Click **Distribute amounts**.

12. In the **Distributed by** field, select whether to distribute amounts by extended price or discount percentage.

13. You can create distributions in the following ways:
    
      - To create multiple distributions that have the same quantity, percentage, or amount distribution, click **Split** for each distribution. Select a ledger account for each distribution, and then click **Distribute equally**.
    
      - To create one distribution at a time, click **Split**. Select the ledger account to distribute the invoice line to, and then enter the quantity, percentage, or amount to distribute. For example, if you selected **Percent** in the **Distributed by** field, enter a percentage in the **Percent** field.
    
    Repeat until you have finished creating distributions.

14. Close the form.

15. Click the **Setup** tab.

16. In the **Sales tax group** field, select the code for the sales tax group for the advance report.

17. In the **Item sales tax group** field, select the code for the item sales tax group for the advance report.

18. Select the **Prices include sales tax** check box to indicate that the amount on the advance report includes sales tax.

19. On the **Action Pane**, click **Post** to post the advance report. The status of the advance report changes to **Posted**.

## See also

[(RUS) Generate an expense account line using the Copy from sources function](rus-generate-an-expense-account-line-using-the-copy-from-sources-function.md)

[(RUS) Advance reports (form)](https://technet.microsoft.com/library/jj733237\(v=ax.60\))

  


