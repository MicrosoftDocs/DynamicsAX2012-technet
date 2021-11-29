---
title: Create loan items
TOCTitle: Create loan items
ms:assetid: 713b8feb-edd3-4a19-9839-f5b34a2a4af3
ms:mtpsurl: https://technet.microsoft.com/library/Aa571315(v=AX.60)
ms:contentKeyID: 36687395
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.HcmLoanListPage
audience: Application User
ms.search.region: Global
---

# Create loan items 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The process for creating loan items depends on whether you want to create a single item or multiple items.

## Create a single loan item

1.  Click **Human resources** \> **Setup** \> **Workers** \> **Loan** \> **Loan items**.

2.  Click **New**.

3.  Enter the name of the loan item.

4.  Enter a description of the loan item.

5.  Select the person who is responsible for the loan item.

6.  Indicate if there is a tax liability associated with the item or if your company is declared liable for the item.

7.  Enter the serial number, or other identification number, for the loan item.

8.  Select the type of the loan item.

9.  Enter the number of days that may pass after the loan item is scheduled to be returned before a reminder is sent to the borrower.

10. Enter the maximum number of consecutive days that a person can borrow the loan item for.

## Create multiple loan items

1.  Click **Human resources** \> **Setup** \> **Workers** \> **Loan** \> **Loan items**. Click **Create loan items**.

2.  In the **Qty.** field, enter the number of loan items to create.

3.  Enter a description of the items.

4.  Select the type of loan items to create.

5.  Select the person who is responsible for the items.

6.  In the **Starting value** field, enter the identification number to assign to the first item created.

7.  Enter an interval for the identification numbers. For example, if you enter 10 for the starting value and 10 for the interval, the numbers assigned to the first three loan items will be 10, 20, and 30.

8.  Enter the format of the identification numbers.
    
    The format must contain one pound (\#) symbol for each digit in the highest identification number. For example, if the highest identification number for a loan item is 10, enter two pound (\#\#) symbols in the **Format** field.

## See also

[About loan items](about-loan-items.md)

[Loan an item to a worker, contact, or applicant](loan-an-item-to-a-worker-contact-or-applicant.md)

[Record a returned loan item](record-a-returned-loan-item.md)

[Loan (form)](https://technet.microsoft.com/library/aa500857\(v=ax.60\))

[Loan types (form)](https://technet.microsoft.com/library/aa574151\(v=ax.60\))

[Loan items (form)](https://technet.microsoft.com/library/aa550442\(v=ax.60\))

  


