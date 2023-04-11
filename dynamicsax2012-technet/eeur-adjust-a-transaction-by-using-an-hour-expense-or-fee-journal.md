---
title: (EEUR) Adjust a transaction by using an hour, expense, or fee journal
TOCTitle: (EEUR) Adjust a transaction by using an hour, expense, or fee journal
ms:assetid: 8d04e024-14ac-4adc-8f43-c76216ba0a96
ms:mtpsurl: https://technet.microsoft.com/library/JJ730994(v=AX.60)
ms:contentKeyID: 49675236
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Adjust a transaction by using an hour, expense, or fee journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use these procedures to adjust project transactions by using journals. In journals, you create an adjusting journal entry to reverse all or part of the original incorrect transaction, and then add a new transaction that contains the correct information. When you adjust project transactions by using an hour, expense, or fee journal, the reversing transactions are posted as corrections in the general ledger.

**Prerequisites**

Before you can complete the procedures in this topic, you must take the following steps:

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**. In the **Ledger** area, on the **Accounting rules** FastTab, select the **Correction** check box, so that transactions that have negative amounts can be posted as corrections in the general ledger.

2.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**. In the left pane, click **Journals**, and then, in the **Ledger posting** field group, select the **Negative transactions - corrections** check box, so that journal transactions that have negative amounts can be posted as corrections.

## Adjust transactions in an hour journal

You can adjust hours worked on projects by entering an adjusting journal. Alternatively, if the hours were originally recorded in an hour journal, you adjust them by reversing the entire journal. Whichever method you use, negative amounts can be posted as corrections.

**Adjust an hour transaction by creating a new adjusting journal**

1.  Click **Project management and accounting** \> **Journals** \> **Hour**.

2.  Click **New**, and then, in the **Name** field, select the journal name that your organization uses for hour journals.

3.  Enter any additional information, and then click **Lines**.

4.  In the **Journal lines for hours** form, enter the adjusting transactions. If you enter negative hours that generate transactions that have negative amounts, the amounts are posted as corrections.

5.  After you finish entering journal lines, click **Post** to post the journal.

**Adjust an hour transaction by reversing a posted journal**

1.  Click **Project management and accounting** \> **Journals** \> **Hour**.

2.  Select the journal to reverse, and then click **Reverse**.

3.  In the **Copy lines to a new journal** form, click **OK**.

4.  In the **Hour journal** form, select the new journal. Then, to view or maintain the journal, click **Lines**. To post the reversing journal, click **Post**.

## Adjust transactions in an expense journal

You can adjust expenses that were charged to projects by entering an adjusting journal. When you post the journal, transactions that have negative amounts are posted as corrections.

1.  Click **Project management and accounting** \> **Journals** \> **Expense**.

2.  Click **New**, and then, in the **Name** field, select the journal name that your organization uses for expense journals.

3.  Enter any additional information, and then click **Lines**.

4.  In the **Journal voucher** form, enter the adjusting transactions. If you enter transactions that have negative amounts, they are posted as corrections.

5.  After you finish entering journal lines, click **Post** to post the journal.

## Adjust transactions in a fee journal

You can adjust fee amounts that are recorded to projects by entering an adjusting journal. Alternatively, if the fees were originally recorded in a fee journal, you can adjust the amounts by reversing the entire journal. Whichever method you use, negative amounts are posted as corrections.

**Adjust a fee transaction by creating a new adjusting journal**

1.  Click **Project management and accounting** \> **Journals** \> **Fee**.

2.  Click **New**, and then, in the **Name** field, select the journal name that your organization uses for fee journals.

3.  Enter any additional information, and then click **Lines**.

4.  In the **Journal lines** form, enter the adjusting transactions. If you enter transactions that have negative amounts, they are posted as corrections.

5.  After you finish entering journal lines, click **Post** to post the journal.

**Adjust a fee transaction by reversing a posted journal**

1.  Click **Project management and accounting** \> **Journals** \> **Fee**.

2.  Select the journal to reverse, and then click **Reverse**.

3.  In the **Copy lines to a new journal** form, click **OK**.

4.  In the **Journal lines** form, select the new journal. Then, to view or maintain the journal, click **Lines**. To post the reversing journal, click **Post**.

## See also

[Hour journal (form)](https://technet.microsoft.com/library/aa598983\(v=ax.60\))

[Journal lines for hours (form)](https://technet.microsoft.com/library/aa571787\(v=ax.60\))

[Expense journal (form)](https://technet.microsoft.com/library/aa600976\(v=ax.60\))

[Fee journal (form)](https://technet.microsoft.com/library/hh209390\(v=ax.60\))

[Journal lines for fees (form)](https://technet.microsoft.com/library/aa498986\(v=ax.60\))

[(EEUR) Adjust a transaction that has been posted to a project](eeur-adjust-a-transaction-that-has-been-posted-to-a-project.md)

[(EEUR) Project management and accounting parameters (modified form)](https://technet.microsoft.com/library/jj710688\(v=ax.60\))

  


