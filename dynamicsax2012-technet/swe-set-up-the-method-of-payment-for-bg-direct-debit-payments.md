---
title: (SWE) Set up the method of payment for BG direct debit payments
TOCTitle: (SWE) Set up the method of payment for BG direct debit payments
ms:assetid: eee442b8-6878-4b87-a424-1d83e5fc8258
ms:mtpsurl: https://technet.microsoft.com/library/Hh227504(v=AX.60)
ms:contentKeyID: 36059916
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Sweden
- Bankgirot
- direct debit
audience: Application User
ms.search.region: Sweden
---

# (SWE) Set up the method of payment for BG direct debit payments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can request a refund on a processed direct debit payment transaction using the Bank giro (BG) direct debit payment format. Use the **Methods of payment - customers** form to set up the method of payment for BG direct debit payments.


> [!NOTE]
> <P>The BG direct debit payment format has replaced the Postgirot Autogiro (SE) payment format and the BG Max format has replaced the Bank giro Automatisk avprickning (SE) customer payment format.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Press CTRL+N to create a new method of payment.

3.  In the **Method of payment** field, enter a unique identifier for BG direct debit payments.

4.  Click the **File formats** FastTab.

5.  In the **Export format** and **Return format** fields, select **Bank giro Autogiro (SE)**.
    

    > [!NOTE]
    > <P>If the Bank giro Autogiro (SE) format is not available in the field list, click <STRONG>Setup</STRONG> and select <STRONG>Bank giro Autogiro (SE)</STRONG> from the available formats.</P>



6.  Close the form to save your changes.

## See also

[(SWE) Import BG direct debit payment returns to a general journal](swe-import-bg-direct-debit-payment-returns-to-a-general-journal.md)

  


