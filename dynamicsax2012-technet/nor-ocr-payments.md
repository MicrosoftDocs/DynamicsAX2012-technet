---
title: (NOR) OCR payments
TOCTitle: (NOR) OCR payments
ms:assetid: c85badb5-8497-4723-8911-86017040f421
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213649(v=AX.60)
ms:contentKeyID: 36059318
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (NOR) OCR payments [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Optical character recognition (OCR) payment is a process of receiving payments electronically from customers. Each OCR payment has a customer identification (KID) reference.

You must install the electronic banking software on your computer and make an agreement with the bank to use the OCR payment process.

## Set up bank accounts and currency

You must define the bank accounts for the company to use electronic payment transactions.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**. Double-click a bank account to open the **Bank accounts** form.

2.  Select the identification for the bank account in the **Bank account** field.

3.  Select the bank account number specified by your bank in the **Bank account number** field.

4.  Click the **Setup** fast tab, and then enter the ledger account in the **Main account** field to which all transactions for the bank are posted.

5.  Select the **More currencies** check box to have the option to use multiple currencies for the account..

6.  Specify the currency code for the bank account in the **Currency** field.

7.  Close the form to save the changes.

8.  Click **General ledger** \> **Setup** \> **Currency** \> **Currency exchange rates**.

9.  Enter the ISO currency code for each currency in the **ISO currency code** field. The ISO code is used in the file that is sent to the bank. This code consists of three characters.

10. Close the form to save the changes.

11. Click **Organization administration** \> **Setup** \> **Addresses** \> **Address setup**. In the **Address setup** form, in the **Country/region** field, enter the ISO country code for the country/region. The code consists of two characters, and is used in the file that is sent to the bank. The ISO currency code and the ISO country/region code are used for transactions with customers who are in other countries or regions.

12. Close the form to save the changes.

## Define bank accounts for customers

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click a customer name to open the **Customers** form. Click **Setup** \> **Bank accounts** to open the **Customer bank accounts** form.

3.  Enter the number that identifies the customer bank account in the **Bank account** field, and the account number assigned by the bank to the customer in the **Bank account number** field.

4.  Click the **General** tab and enter the Society for Worldwide Inter-bank Financial Telecommunication **SWIFT code** for customers from other countries/regions. If the SWIFT code is not available, you must provide the country/region code for the receiver’s bank.
    

    > [!NOTE]
    > <P>For banks that are not a part of the SWIFT, complete steps 5 through 10 specified in the <STRONG>Set up bank accounts and currency</STRONG> procedure.</P>



5.  Select the routing number code in the **Routing number type** field. The code identifies the type of routing number for making international payments.

6.  Enter the routing number for the bank in the **Routing number** field.

7.  Close the form to save the changes.

## Import OCR payments

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Click CTRL+N to create a new payment journal, and then click the **Lines** tab to open the **Journal voucher** form.

3.  Click **Functions** \> **Import payments**.

4.  Select **OCR** as the method of payment in the **Method of payment** field.

5.  Specify the location and the name of the file to save the import file sent by the bank. Enter other required details in the form, and then click **OK**. You can view the paid customer transactions that have been imported in the **Journal voucher** form.

6.  Validate and post the journal.

7.  Close the form to save your changes.

## See also

[(NOR) Set up the OCR method of payment](nor-set-up-the-ocr-method-of-payment.md)

[(NOR) Create a payment proposal and import the OCR payments as Avtalegiro in the payment journal](nor-create-a-payment-proposal-and-import-the-ocr-payments-as-avtalegiro-in-the-payment-journal.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

