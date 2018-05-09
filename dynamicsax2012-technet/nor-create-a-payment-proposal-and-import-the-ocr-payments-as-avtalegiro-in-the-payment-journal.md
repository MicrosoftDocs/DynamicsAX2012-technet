---
title: (NOR) Create a payment proposal and import the OCR payments as Avtalegiro in the payment journal
TOCTitle: (NOR) Create a payment proposal and import the OCR payments as Avtalegiro in the payment journal
ms:assetid: 79dd6f82-2f68-489c-8959-b63b1ccfc46c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213019(v=AX.60)
ms:contentKeyID: 36058243
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (NOR) Create a payment proposal and import the OCR payments as Avtalegiro in the payment journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Journal voucher** form to create a payment proposal and import the optical character recognition (OCR) payments as Avtalegiro in the payment journal.

## Create a customer payment proposal and generate a payment file

Use the **Customer payment proposal** form to create a customer payment proposal and generate a payment file.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new payment journal, and then click **Lines** to open the **Journal voucher** form.

3.  Click **Payment proposal** \> **Create payment proposal** to create a new payment proposal.

4.  In the **Proposal type** field, select **Per due date**.

5.  Click **Select** to define the filter and sort payments by using **Avtalegiro** as the method of payment.

6.  Click **OK** to create the proposal.

7.  In the **Customer payment proposal** form, enter additional details, and then click **OK**. You can view all the transactions in the **Edit payment proposal** form based on the criteria that you set in the **Customer payment proposal** form.

8.  Delete any transactions that should not be included in the payment.

9.  In the **Journal voucher** form, click **Functions** \> **Generate payments** to export the transaction and create the payment file that is sent to the bank.

10. In the **Export format** field, select the **Avtalegiro (NO)** export file format.

11. Click **Dialog** to open the **Direct debit** form, and then in the **File name** field, enter the name and location of the payment file that is sent to the bank.

12. Click **OK** to save the details of the payment file.

13. Close the forms.

## Import the OCR payments as Avtalegiro in the payment journal

Use the **OCR and AvtaleGiro import** form to import the OCR payments as Avtalegiro in the payment journal.

In the **Payment mode change** form, in the **Warning** field, select **Yes** to notify the customer when the payment mode is changed. For more information, see [(NOR) Payment mode change (form)](https://technet.microsoft.com/en-us/library/hh209700\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new payment journal, and then click **Lines** to open the **Journal voucher** form.

3.  In the **Journal voucher** form, click **Functions** \> **Import payments**.

4.  In the **Method of payment** field, select **AVG** as the method of payment.

5.  Click **OK** to open the **OCR and AvtaleGiro import** form.

6.  In the **File name** field, specify the name and location to save the import file sent by the bank.

7.  Select the **Summing of bank transactions** check box to total all the balances for transactions in the ledger for a specific date.

8.  In the **Error account customer** field, select a customer account. If there is no customer account specified in the OCR payment file that is imported, the customer account specified in this field is used to import the OCR payments as Avtalegiro.
    

    > [!NOTE]
    > <P>If there is a difference between the paid amount and the invoiced amount, the <STRONG>Rejected</STRONG> status is displayed for the payment line if you have selected the <STRONG>Amount control</STRONG> check box.</P>



9.  In the **Method of payment** field, specify the method of payment that is used for new or changed Avtalegiro.

10. Select the **Archive the file** check box to archive the import file to the database. You can view the archived file in the **File archive** form.

11. Select the **Analyze the file** check box to analyze the imported payment lines.

12. Select the **Customer bank account test.** check box to save the bank account information in the import file as the default bank account information for the customer.
    

    > [!NOTE]
    > <P>The bank account information is saved as the default information only if the customer bank details are not entered in the <STRONG>Bank account trap</STRONG> form.</P>



13. Click **OK**.

14. In the **Journal voucher** form, click **Validate** \> **Validate** to validate the journal line.

15. Click **Post** \> **Post** to post the journal.

16. Close the form.

## See also

[(NOR) Set up the Avtalegiro method of payment](nor-set-up-the-avtalegiro-method-of-payment.md)

[(NOR) File archive (form)](https://technet.microsoft.com/en-us/library/hh242881\(v=ax.60\))

[(NOR) Bank account trap (form)](https://technet.microsoft.com/en-us/library/hh227378\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

