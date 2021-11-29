---
title: (ITA) Generate and print a vendor payment remittance file
TOCTitle: (ITA) Generate and print a vendor payment remittance file
ms:assetid: ed151652-b4a8-47e9-8cec-32e9da1b9c6a
ms:mtpsurl: https://technet.microsoft.com/library/Hh227498(v=AX.60)
ms:contentKeyID: 36059899
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Generate
- Italy
- remittance file
audience: Application User
ms.search.region: Italy
---

# (ITA) Generate and print a vendor payment remittance file 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you generate a vendor payment remittance file, the default value date is displayed in the **Recipient value date** column in the **Bank remittance** report. If the default value date is blank, the document date is used.

Before you can generate a vendor payment remittance file with the default value date, you must first create an invoice journal and payment journal for the vendor.

## Post an invoice journal

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Press CTRL+N to create a new journal.

3.  In the **Name** field, select the journal name.

4.  Click **Lines** to open the **Journal voucher** form. For more information, see [Journal voucher - Invoice journal (form)](https://technet.microsoft.com/library/aa616218\(v=ax.60\)).

5.  In the **Account type** and **Account** fields, select **Vendor** and the vendor account number.

6.  In the **Invoice** field, enter the invoice number.

7.  In the **Credit** field, enter the transaction amount.

8.  In the **Offset account type** and **Offset account** fields, select **Bank** and the bank account number.

9.  In the **Currency** field, select the transaction currency.

10. On the **Invoice** tab, in the **Method of payment** field, select the method of payment that you have created for payment remittances.

11. Click **Validate** \> **Validate** to validate the journal.

12. Click **Post** \> **Post and transfer** to post and transfer the transaction amounts to the respective ledger accounts.

13. Close the forms to save your changes.

## Generate a text file and print the vendor payment remittance file

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new journal.

3.  In the **Name** field, select the journal name and then click **Lines** to open the **Journal voucher** form. For more information, see [Journal voucher - Vendor payment journal (form)](https://technet.microsoft.com/library/aa599011\(v=ax.60\)).

4.  Press CTRL+N to create a new line.

5.  Click the **Overview** tab and enter the required information.

6.  Click the **Payment** tab, and in the **Method of payment** field, select the payment method.

7.  In the **Document date** field, enter the date when the document was created.

8.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form and mark the transactions for settlement. For more information, see [Settle open transactions - vendor (form)](https://technet.microsoft.com/library/aa619609\(v=ax.60\)).

9.  Close the form to save your changes.

10. In the **Journal voucher** form, click **Functions** \> **Generate payments** to open the **Generate payments** form. For more information, see [Generate payments - vendor (class form)](https://technet.microsoft.com/library/aa586980\(v=ax.60\)).

11. In the **Method of payment** field, select the payment method.

12. In the **Export format** field, select **Pagamento Fornitori (IT)**.

13. In the **Bank account** field, select the bank account to receive the payment.

14. Select the **Show format dialog** check box to display the export format dialog box when you click **OK**.

15. Click **Dialog** to open the **Pagamento Fornitori (IT)** form.

16. In the **File name** field, enter the file path and name, or browse to locate the folder where the text file is to be created.

17. In the **Creation date** field, select the payment file creation date.

18. In the **Default date** field, select the default value date of the payment file. The default value date is displayed in the **Recipient value date** column in the **Bank remittance** report. If the default value date is blank, the document date is used.

19. Select the **Control report** check box to print the bank remittance control report. Click **Control report** to open the **Print destination settings** form and specify the printer settings.

20. Click **OK** to generate the vendor payment remittance file in the specified file format and print the bank remittance control report.

## See also

[(ITA) Set up a method of payment for payment remittance files](ita-set-up-a-method-of-payment-for-payment-remittance-files.md)

  


