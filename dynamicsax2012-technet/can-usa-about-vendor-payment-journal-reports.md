---
title: (CAN, USA) About vendor payment journal reports
TOCTitle: (CAN, USA) About vendor payment journal reports
ms:assetid: 53e2b3b0-1017-43cb-9363-ad4d1638142f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa548929(v=AX.60)
ms:contentKeyID: 36057301
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CAN, USA) About vendor payment journal reports [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Vendor payment journal** and the **Vendor posted payment journal** reports to view account and payment details for individual vendors. Amounts on the reports are displayed in the currency of the payment and in the original currency for the transaction. Unapplied payments are included, but payment details are not included.

The payment currency amount might be different from the payment amount in the following situations:

  - The payment amount is greater than the payment details. For example, if a payment of 10,000 is made and only 7,000 is settled with the vendor invoices, the remaining amount is not settled. This could be a prepayment or prepayment journal voucher that you are sending to the vendor.

  - The payment amount is less than the payment details and a correction amount was not specified when the information was entered. For example, an amount can be entered in the journal line and the total amount of marked transactions does not equal the payment amount. A message will be displayed. If you ignore the warning, an imbalance will occur and will be reported when the unposted report is generated. The payment detail amount will be corrected to balance with the payment amount when the journal is posted.

When you print a **Vendor payment journal** report for a journal that has not been posted, the report includes an opening balance. The ending balance is calculated as the open balance minus the payment and the discount taken. Some of the amounts on this report are estimates because data, such as exchange rates, write-off amounts, or maximum overpayments and underpayments might change from the time that the unposted report is generated to the time when the payment is posted.

When you print a **Vendor posted payment journal** report, it does not include an opening balance. Instead of an ending balance, the report contains a current balance, which is the balance of the invoice at the time the report was generated.


> [!TIP]
> <P>To view vendor payment information as you work with vendor account records in the <STRONG>Vendors</STRONG> form, on the Action Pane, on the <STRONG>Invoice</STRONG> tab, click <STRONG>Payment history</STRONG>. For more information, see <A href="view-payments-made-to-a-vendor.md">View payments made to a vendor</A>.</P>



## See also

[(CAN, USA) Vendor payment journal report (VendPaymentJournal\_NA)](can-usa-vendor-payment-journal-report-vendpaymentjournal-na.md)

[(CAN, USA) Vendor posted payment journal report (VendPostPaymJournal\_NA)](can-usa-vendor-posted-payment-journal-report-vendpostpaymjournal-na.md)

[About prepayments and prepayment journal vouchers](about-prepayments-and-prepayment-journal-vouchers.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

