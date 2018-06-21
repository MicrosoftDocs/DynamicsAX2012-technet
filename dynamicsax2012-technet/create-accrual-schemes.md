---
title: Create accrual schemes
TOCTitle: Create accrual schemes
ms:assetid: 363b9469-bcee-4294-937f-80da1918d0ef
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570123(v=AX.60)
ms:contentKeyID: 36810347
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accrual scheme
- accrual schemes
- create accrual schemes
---

# Create accrual schemes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Ledger accruals redistribute the costs or revenues of a journal line so that the costs and revenues are recognized in the appropriate periods.

## Create accrual schemes

The following steps describe how to create an accrual scheme. After you have created an accrual scheme, you can complete allocation key accrual schemes and calendar key or fiscal key accrual schemes. For more information, see the next sections.

1.  Click **General ledger** \> **Setup** \> **Posting** \> **Accrual schemes**.

2.  Click **New** to create an accrual scheme.

3.  Enter an accrual identification and a description of the scheme.

4.  On the **General** FastTab, select account numbers in the **Debit** and **Credit** fields.
    
    The account numbers are used for posting the accrued debit amounts to an asset account, and for posting the accrued credit amounts to a liability account.

5.  In the **Voucher** field, select how to handle voucher numbers on the accrual transactions:
    
      - **Base** – The main voucher number should be used for all generated transactions.
    
      - **Single** – A new voucher number should be used for each transaction date.
    
      - **Multiple** – A new voucher number should be used for all accrued transactions.

6.  If you selected **Single** or **Multiple** in step 5, select a number sequence code for the voucher numbers. If you selected **Base**, the **Number sequence code** field is not available, because the main voucher number is used.

7.  Enter a description that you can use on all the accrued transactions. If there is no description in this field, the description from the main voucher is used.

8.  If you select **Calendar** or **Fiscal** in the **Calendar type** field, and select an option other than **Day** in the **Posting frequency** field, select when the accrued transactions should be posted in the **Posting date** field.

## Finish creating calendar key and fiscal key accrual schemes

1.  Complete the previous procedure.

2.  In the **Calendar type** field, select the basis for the duration of the accrual:
    
      - **Calendar** – Accruals are made according to the calendar year.
    
      - **Fiscal** – Accruals are made according to the fiscal year that is defined in the **Fiscal calendars** form for the fiscal calendar that is selected in the **Ledger** form.

3.  Select the period frequency, such as **Monthly** or **Quarterly**.

4.  In the **Length** field, enter the number of occurrences for the selected period frequency, such as 4 quarters.

5.  If you selected **Calendar** in the **Calendar type** field, select a posting frequency.
    

    > [!NOTE]
    > <P>Period frequency and posting frequency are not necessarily the same. For example, a duration of 2 years typically requires postings every month.</P>

    
      - If you selected **Monthly** or **Quarterly** in the **Posting frequency** field, you can indicate if the same amount should be posted all months, or if the amount posted each month should be based on the number of days in the month, relative to the total number of days. Select **Even** in the **Value posting** field if all months or quarters should be debited the same amount. Select **Scale** if each month should be debited based on the number of days in the month, relative to the total numbers of days.
    
      - If you selected **Fiscal** in the **Calendar type** field, the **Posting frequency** field is not available. The posting frequency then is equal to the number of periods in the fiscal year, as defined in the **Fiscal calendars** form for the fiscal calendar that is selected in the **Ledger** form.

## Finish creating allocation key accrual schemes

1.  Complete the procedure in the “Create accrual schemes” section.

2.  In the **Calendar type** field, select **Allocation key** as the basis for the duration of the accrual.
    
    Accruals are made according to a period key that is defined in the **Period allocation categories** form.

3.  Select a period key in the **Period key** field.

## See also

[Ledger accruals (form)](https://technet.microsoft.com/en-us/library/aa574924\(v=ax.60\))

[Create ledger accrual transactions](create-ledger-accrual-transactions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

