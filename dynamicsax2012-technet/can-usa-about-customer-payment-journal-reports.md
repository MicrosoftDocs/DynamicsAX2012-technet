---
title: (CAN, USA) About customer payment journal reports
TOCTitle: (CAN, USA) About customer payment journal reports
ms:assetid: 03aa8e3a-bbf9-4ea8-b809-848f346c3077
ms:mtpsurl: https://technet.microsoft.com/library/Aa569704(v=AX.60)
ms:contentKeyID: 36966678
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Canada
---

# (CAN, USA) About customer payment journal reports 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Customer payment journal** report and the **Customer posted payment journal** report to view account and payment details for individual customers. Amounts on the reports are displayed in both the currency of the payment and the original currency of the transaction. Payments that are not yet settled are included, but payment details are not included. These reports are generated so that you can check the status of customer payments, and review the invoice and cash processes. These reports are typically used by accountants, accounting managers, accounting supervisors, accounts receivable clerks, chief executive officers, chief financial officers, collections agents, collections managers, compliance managers, and financial controllers.


> [!NOTE]
> <P>(CAN, USA) These reports are available only to legal entities whose primary address is in Canada or the United States.</P>



The payment currency amount might differ from the payment amount in the following situations:

  - The payment amount exceeds the payment details. For example, a payment of 10,000 is received from a customer, but only 7,000 is settled with the customer invoices. In this case, the remaining amount is not settled.

  - The payment amount is less than the payment details, and a correction amount was not specified when the information was entered. For example, an amount is entered on the journal line, but the total amount of marked transactions does not equal the payment amount. In this case, a warning message is displayed. If you ignore the warning, the imbalance is reported when the **Customer payment journal** report is generated. However, the amounts in the payment details are corrected so that they balance with the payment amount when the journal is posted.

When you create a **Customer payment journal** report for a journal that has not been posted, the report includes an opening balance. The ending balance is calculated as the open balance minus the payment and the discount that was taken. Some of the amounts on this report are estimates, because data such as exchange rates, write-off amounts, and maximum overpayments and underpayments might change between the time that the **Customer payment journal** report is generated and the time that the payment is posted.

When you create a **Customer posted payment journal** report, the report does not include an opening balance. Instead of an ending balance, the report includes a current balance, which is the balance of the invoice when the report is generated.

## See also

[(CAN, USA) Customer payment journal report (CustPaymentJournal\_NA)](can-usa-customer-payment-journal-report-custpaymentjournal-na.md)

[(CAN, USA) Customer posted payment journal report (CustPostPaymJournal\_NA)](can-usa-customer-posted-payment-journal-report-custpostpaymjournal-na.md)

  


