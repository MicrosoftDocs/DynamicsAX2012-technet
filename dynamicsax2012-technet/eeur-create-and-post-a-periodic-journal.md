---
title: (EEUR) Create and post a periodic journal
TOCTitle: (EEUR) Create and post a periodic journal
ms:assetid: d50f0cae-9495-4e4f-b5c5-aae6e2233608
ms:mtpsurl: https://technet.microsoft.com/library/JJ853389(v=AX.60)
ms:contentKeyID: 50396759
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- periodic journal
- recurring journal
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Create and post a periodic journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use these procedures to create and post a periodic journal. Periodic journals are sometimes called recurring journals because the amount, text, and other information are repeated each time that the journal is posted. When you create the journal, you specify the period interval for the recurrence, such as days or months. You also specify the number of periods for which the journal will be posted.

For example, an insurance company offers your organization a discount for prepaying the insurance policy for an entire year. The payment is posted to an asset account such as prepaid insurance. You then amortize your monthly insurance expense throughout the year by creating a periodic journal that contains a credit to the prepaid insurance account and a debit to an insurance expense account.

You can also create a periodic journal from an existing general journal.

## Create a standard periodic journal

A standard periodic journal contains only journal lines that are generated from the lines that you enter. Other than the **Date** field, each line contains the same information and the intervals are evenly spaced.

1.  Click **General ledger** \> **Periodic** \> **Journals** \> **Periodic journals**.

2.  Click **New**. Select a name, enter any additional information, and then click **Lines**.

3.  In the **Journal voucher** form, create the journal lines. In the **Debit** and **Credit** fields for each line, enter the total amount for all recurrences of the journal. The amount is automatically divided by the number of periods when the periodic journal lines are created.

4.  Click **Split for periods**.

5.  In the **Save journal as periodic journal** form, select the start date for the periodic journal lines.

6.  In the **Number of periods** field, enter the number of periods across which to split the journal line. This value determines how many new transactions are generated. The transaction amount is distributed evenly across the new transactions.

7.  In the **Unit** field, select the unit of measure for the period.

8.  In the **Period interval** field, enter the interval between posting periods.
    
    For example, to generate quarterly postings, enter **4** in the **Number of periods** field, select **Months** in the **Unit** field, and enter **3** in the **Period interval** field. The program generates 4 journal lines, each for one fourth of the journal line amount that you entered, at 3-month intervals.

9.  Click **OK**. The **Save journal as periodic journal** form closes, and the periodic journal lines are generated in the **Journal voucher** form.

## Create a periodic journal from a general journal

You can convert an existing general journal into a periodic journal. For example, each month, you create a journal that contains similar entries. You can open one of the journals and make it a periodic journal, and then maintain individual journal lines.

1.  Click **General ledger** \> **Journals** \> **General journal**. Create a new journal or open an existing journal. For more information about how to create a general journal, see [Journal voucher - General journal (form)](https://technet.microsoft.com/library/aa591466\(v=ax.60\)).

2.  In the **Journal voucher** form, click **Period journal** \> **Save journal**.

3.  In the **Save journal as periodic journal** form, to save the journal lines in an existing periodic journal, select the journal number in the **Periodic journal number** field.

4.  To save the journal lines in a new periodic journal, do the following:
    
    1.  Select a journal in the **Period journal** field, and enter a descriptive name in the **Name** field.
    
    2.  Click **Split for periods**.
    
    3.  Select the **Auto splitting on periods** check box to enable the program to split the journal lines automatically.
    
    4.  In the **Start date** field, select the date for the first periodic journal line.
    
    5.  In the **Number of periods** field, enter the number of periods across which to split the journal line. This value determines how many new transactions are generated. The transaction amount is distributed evenly among the new transactions.
    
    6.  In the **Unit** field, select the unit of measure for the period.
    
    7.  In the **Period interval** field, enter the interval between posting periods.

## Post a periodic journal

After you create a periodic journal, use this procedure to post it. The procedure is the same for all periodic journals, regardless of how you create them.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Click **New**. Select a name, enter any additional information, and then click **Lines**.

3.  In the **Journal voucher** form, click **Period journal** \> **Retrieve journal**.

4.  In the **Period journal** form, in the **To date** field, enter the posting date for the transactions. This date also serves as a cutoff date for the periodic journal lines that are eligible to be transferred and posted.

5.  If the line in the periodic journal does not have a transaction date, you can select one in the **Empty date** field. If you do not select a date in this field, the date in the **To date** field becomes the transaction date.

6.  In the **Periodic journal number** field, select the periodic journal to post.

7.  In the **Copy or move journal** field, select whether to copy the periodic journal to the journal voucher or to move it. If you move it, the periodic journal lines are removed from the periodic journal after they appear in the general journal.

8.  Click **OK** to close the **Period journal** form.

9.  The copied or moved journal lines appear in the **Journal voucher** form. You can maintain the journal lines if you have to. After you finish maintaining the journal, click **Post** \> **Post**.

## See also

[Periodic journal lines (form)](https://technet.microsoft.com/library/aa557282\(v=ax.60\))

[(EEUR) Periodic journal lines (modified form)](https://technet.microsoft.com/library/jj714475\(v=ax.60\))

[Save journal as periodic journal (form)](https://technet.microsoft.com/library/aa585700\(v=ax.60\))

  


