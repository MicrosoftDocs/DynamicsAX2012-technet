---
title: (CZE) Revalue foreign currency amounts for customers and vendors
TOCTitle: (CZE) Revalue foreign currency amounts for customers and vendors
ms:assetid: 20189f76-adc6-48bb-a001-2a06b55001ff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn126113(v=AX.60)
ms:contentKeyID: 52075290
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CZE) Revalue foreign currency amounts for customers and vendors [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you reverse the exchange rate adjustments for a customer or a vendor, the transactions are posted to the general ledger as corrections or reverse transactions. You must select the same general ledger account and transaction type for consecutive unrealized transactions.

Before adjusting exchange rates, you must perform the following tasks:

  - Set up the local currency and exchange rates. For more information, see [Currencies (form)](https://technet.microsoft.com/en-us/library/aa582902\(v=ax.60\)) and [Currency exchange rates (form)](https://technet.microsoft.com/en-us/library/hh209477\(v=ax.60\)).

  - Create a customer or vendor. For more information, see [Create a customer record](create-a-customer-record.md), [Customers (form)](https://technet.microsoft.com/en-us/library/aa590606\(v=ax.60\)), [Create a vendor account](create-a-vendor-account.md) and [Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\)).

## Create a journal transaction for a customer or a vendor

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N or create a journal for the customer or the vendor.

3.  Click the **General** tab, and then select the **Reversing entry** check box to mark the transaction as a reverse transaction.

4.  In the **Reversing date** field, enter the date to post the reverse transaction.

5.  Click **Lines** to open the **Journal voucher** form to create a debit transaction or a credit transaction.

6.  In the **Account** field, enter the account number of the current account type.

7.  In the **Offset account** field, enter the offset account for the transaction.

8.  Click the **General** tab, and then in the **Date** field, enter the posting date.

9.  In the **Currency** field, enter the currency code.

10. Click **Functions** \> **Settlement** to settle the payment and invoice. For more information, see [Settle open transactions - customer (form)](https://technet.microsoft.com/en-us/library/aa558602\(v=ax.60\)) and [Settle open transactions - vendor (form)](https://technet.microsoft.com/en-us/library/aa619609\(v=ax.60\)).

11. Click **Post** \> **Post** to post the transaction.

## Perform an exchange rate adjustment

1.  Click **Accounts receivable** \> **Periodic** \> **Foreign currency revaluation**.
    
    –or–
    
    Click **Accounts payable** \> **Periodic** \> **Foreign currency revaluation**.

2.  Click **Foreign currency revaluation**.

3.  In the **Method** field, select the method for the exchange rate adjustment. If you select **Incremental** in the **Calculation method** field in the **General ledger parameters** form, the reversal of exchange rate adjustments are not posted as corrections.

4.  In the **Considered date** field, enter the date on which the transaction is adjusted and posted.

5.  In the **Date of rate** field, enter the date of the foreign currency revaluation.

6.  In the **Use posting profile from** field, select the profile that is used for exchange rate adjustments.

7.  Enter values in the other fields, if required.

8.  Select the **Print** check box to print a report that shows the balances before and after the foreign currency revaluation. This printout also shows the summary of all changes, by currency.

9.  Click **OK** to revalue the foreign currency amounts and print the report. Any exchange rate gain is posted to the profit ledger account, and the exchange rate loss is posted to the loss ledger account.

You can view the exchange rate adjustments with corrections for a customer in the **Customer transactions** form, or for a vendor in the **Vendor transactions** form.

## See also

[Customer foreign currency revaluation (form)](https://technet.microsoft.com/en-us/library/aa586009\(v=ax.60\))

[Vendor foreign currency revaluation (form)](https://technet.microsoft.com/en-us/library/aa500833\(v=ax.60\))

[(EEUR) Customer transactions (modified form)](https://technet.microsoft.com/en-us/library/jj730993\(v=ax.60\))

[(EEUR) Vendor transactions (modified form)](https://technet.microsoft.com/en-us/library/jj730985\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

