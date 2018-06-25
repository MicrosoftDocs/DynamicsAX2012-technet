---
title: (RUS) Create and post a payment journal for an exchanged currency
TOCTitle: (RUS) Create and post a payment journal for an exchanged currency
ms:assetid: b7e97c74-bbda-49c1-b24c-08468bec1c3e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ856176(v=AX.60)
ms:contentKeyID: 50407015
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and post a payment journal for an exchanged currency [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you have sent a payment to the bank and received a bank statement, you can create and post a payment journal for the currency transfer.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. Click **Lines** to open the **Journal voucher** form.

2.  Press CTRL+N to create a new payment journal line, and then enter the required fields. For more information, see [Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\)).

3.  In the **Account** field, select the vendor account number.

4.  In the **Credit** field, enter the transaction amount.

5.  In the **Offset account type** field, select **Bank**. In the **Offset account** field, select the offset account number.

6.  In the **Currency** field, select the currency code for the currency transaction. In the **Method of payment** field, select the method of payment for the currency transaction. The currency that you select must match the currency that is specified in the **Legal entities** form.

7.  On the **Payment** tab, in the **Order for currency sale/purchase/transfer** field, select the order number for a currency sale. The vendor posting profile is displayed in the **Posting profile** field.

8.  On the **Bank** tab, in the **Bank transaction type** field, select the type of transaction.

9.  In the **Transit account** field, select the unique account number of the currency conversion account. In the **Currency** field, select the currency that is used in the transfer.

10. In the **Bank exchange rate** field, enter the bank exchange rate.

11. Click **Validate** \> **Validate** to validate the payment journal.

12. Click **Post** \> **Post** to post the payment journal.

## See also

[Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md)

[(RUS) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/en-us/library/jj733511\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

