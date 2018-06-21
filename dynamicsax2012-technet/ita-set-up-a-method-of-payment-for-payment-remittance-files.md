---
title: (ITA) Set up a method of payment for payment remittance files
TOCTitle: (ITA) Set up a method of payment for payment remittance files
ms:assetid: de7e833c-2ce9-42e3-85e3-4bfa685bfcc4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227412(v=AX.60)
ms:contentKeyID: 36059688
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Italy
- method of payment
- payment remittance file
---

# (ITA) Set up a method of payment for payment remittance files [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can generate a vendor payment remittance file, you must first specify the Italian validation method for bank accounts and then set up the **Pagamento Fornitori IT** export file format for the method of payment to the vendor.

## Set up a bank account

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Click **Bank account** to create a new bank account. For more information, see [Bank accounts (form)](https://technet.microsoft.com/en-us/library/aa587660\(v=ax.60\)).

3.  In the **Bank account** and **Name** fields, enter a unique bank account number and the name of the bank.

4.  In the **IBAN** field, enter the bank's 27-character International Bank Account Number (IBAN).
    

    > [!NOTE]
    > <P>The format of the IBAN number is as follows: IT&lt;3 digits&gt; &lt;10 digits&gt; &lt;12 characters&gt;. The three digits after the two-letter ISO code represent the check digits that are calculated from the rest of the IBAN characters. The next 10 digits represent the National Bank code and the branch number, and the characters represent the account ID of the bank.</P>



5.  Click the **Setup** FastTab, and in the **Main account** field, select the ledger account for the bank.

6.  Enter or modify information on the other tabs in the form, as required.

7.  Close the form to save your changes.

## Set up a bank account for a vendor

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select the vendor, and then click **Edit in grid** in the **Maintain** action group to view the vendor details. For more information, see [Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\)).

3.  Click **Bank accounts** in the **Setup** action group to open the **Vendor bank accounts** form.

4.  Click **New** to create a new bank account for the vendor.

5.  In the **Bank account** and **Name** fields, enter the unique bank account number and name of the bank.

6.  Close the form to save your changes.

## Set up a method of payment for payment remittance files

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Click **New** to create a method of payment. For more information, see [Methods of payment - vendors (form)](https://technet.microsoft.com/en-us/library/aa618565\(v=ax.60\)).

3.  In the **Method of payment** field, enter the unique identification code for the vendor method of payment.

4.  Click the **File formats** FastTab, and then click **Setup** to open the **File formats for methods of payment** form.

5.  Click the **Export** tab, and in the **Available** list, select **Pagamento Fornitori (IT)**.

6.  Click **\<** to move the file format to the **Selected** list.

7.  Click the **Remittance** tab, and in the **Available** list, select **Pagamento Fornitori (IT)**.

8.  Click **\<** to move the file format to the **Selected** list.

9.  Close the form to return to the **Methods of payment** form.

10. In the **Methods of payment** form, in the **Export format** and **Remittance format** fields, select **Pagamento Fornitori (IT)**.

11. Close the form to save your changes.

## See also

[(ITA) Generate and print a vendor payment remittance file](ita-generate-and-print-a-vendor-payment-remittance-file.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

