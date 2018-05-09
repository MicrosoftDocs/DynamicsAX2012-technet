---
title: (RUS) Payments to foreign bank accounts
TOCTitle: (RUS) Payments to foreign bank accounts
ms:assetid: eba77033-3465-4489-be85-807d8814c44c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678587(v=AX.60)
ms:contentKeyID: 49388069
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Payments to foreign bank accounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Payments that are made to vendors by using payment orders or payment requests must include additional information about the vendor bank account if the vendor uses a foreign bank to receive payments. This bank account can include the bank code, the bank name, the Society for Worldwide Interbank Financial Telecommunication (SWIFT) code of the foreign bank, the foreign bank account number of the vendor, and the address of the payer.

When you make payments to the foreign bank account of a vendor, the vendor must register a bank account with a Russian bank. This bank account can be assigned as an intermediate bank account between the payer and the vendor. You can generate a payment order for the payments, and then enter the details of the vendor bank account and the vendor account that the payments are made to.

For transactions that involve payment returns to a foreign customer, you can set up a customer bank account to receive the returned payments, and then generate a customer payment order that includes the bank and address of the payer.

## Setting up payments to foreign bank accounts

You must complete the following tasks if you want to generate a payment order for payments to a foreign vendor bank account, or to send a payment return to a foreign customer bank account:

  - Set up a bank account in the **Bank accounts** form. For more information, see [Bank accounts (form)](https://technet.microsoft.com/en-us/library/aa587660\(v=ax.60\)).

  - Set up a vendor account in the **Vendors** form.

  - Set up a customer account in the **Customer** form. For more information, see[(RUS) Customers (modified form)](https://technet.microsoft.com/en-us/library/jj853212\(v=ax.60\))

  - Set up payment journals for a vendor account and a customer account in the **Ledger journal** form.

## See also

[(RUS) Set up an intermediate bank account for a foreign vendor](rus-set-up-an-intermediate-bank-account-for-a-foreign-vendor.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

