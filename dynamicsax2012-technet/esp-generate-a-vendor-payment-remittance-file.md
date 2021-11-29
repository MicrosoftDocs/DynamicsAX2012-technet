---
title: (ESP) Generate a vendor payment remittance file
TOCTitle: (ESP) Generate a vendor payment remittance file
ms:assetid: 94e7bb9e-774a-4768-a518-a2ac908bee79
ms:mtpsurl: https://technet.microsoft.com/library/Gg232207(v=AX.60)
ms:contentKeyID: 36058606
author: Khairunj
ms.date: 05/28/2014
mtps_version: v=AX.60
f1_keywords:
- vendor payments
- SEPA
- promissory note
- LedgerJournalTable_VendPaymRemittance
- remittance file format
- vendor bank remittance
audience: Application User
ms.search.region: Spain
---

# (ESP) Generate a vendor payment remittance file 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to generate remittance files for a selected method of payment format. You can also generate remittance files for a promissory note that is created with Single European Payment Area (SEPA). Before you create the remittance journal, complete the following tasks:

  - Set up methods of payment. For more information, see [(ESP) Set up methods of payment for payment remittance files](esp-set-up-methods-of-payment-for-payment-remittance-files.md).

  - Optional: Post vendor invoices in an invoice journal. For more information, see [Post invoices in an invoice journal](post-invoices-in-an-invoice-journal.md).

  - Draw a promissory note and settle open transactions. For more information, see [Draw a promissory note](draw-a-promissory-note.md).


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R3. For more information, see the section later in this topic.</P>



## Create a remittance journal and generate a remittance file in AX 2012 and AX 2012 R2

Use the following procedures to create a remittance journal for the selected remittance format, and to generate a remittance file.

## Create a remittance journal

To create a remittance journal for posted vendor invoices, follow these steps:

1.  Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Remittance journal**.

2.  Select a journal.

3.  Click the **Promissory note** tab, and then in the **Bank account** field, select a bank account.

4.  Click **Lines**, and then select a vendor account.

5.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

6.  Select the **Mark** check box next to an open promissory note transaction.

7.  Close the **Settle open transactions** form. Click **Post** \> **Post**.

## Generate a remittance file

To generate a remittance file, follow these steps:

1.  In the **Journal voucher** form, click **Functions** \> **Generate remittance**.

2.  In the **Method of payment** field, select a method of payment that uses the **Remittance Format 34 AEB(ES)** format, and then click **Dialog**. The **Remittance Format 34 AEB(ES)** dialog box opens.

3.  In the **Remittance format** field, select the export format for the selected method of payment.

4.  Enter the file name and location to create the remittance file.

5.  Select the **Control report** check box to print a report that displays information about the transactions that are included in the remittance file.

6.  Click **OK**.

7.  In the **Generate remittance** form, click **OK**.
    
    The remittance file is generated, and the **Bank remittance** control report is printed. Information about the remittance file, including the journal number, file name, and transactions, is available in the **Remittance files for vendors** form.

8.  Review the control report. If changes are needed, repeat steps 2 through 8 to regenerate the remittance file.

## Generate a remittance file for a selected SEPA format in Microsoft Dynamics AX 2012 R3, AX 2012 R2, and AX 2012

To generate a remittance file for posted vendor invoices, follow these steps:

1.  Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Remittance journal**.

2.  Select a journal that uses the **Vendor bank remittance** journal type.

3.  On the **Promissory note** tab, select a remittance type and a bank account.

4.  Click **Lines**, and then select a vendor account that uses a SEPA credit transfer payment format.

5.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

6.  Select the **Mark** check box next to an open promissory note transaction.

7.  Close the **Settle open transactions** form. Click **Post** \> **Post**.

8.  Click **Functions** \> **Generate remittance**.

9.  In the **Remittance format** field, select the export format that is meant for SEPA credit transfer.

10. Enter the file name and location to create the remittance file.

11. Select the **Control report** check box to print a report that displays information about the transactions that are included in the remittance file.

12. Click **OK**.

13. In the **Generate remittance** form, click **OK**.
    
    The remittance file is generated, and the **Bank remittance** control report is printed. Information about the remittance file that includes the journal number, file name, and transactions, is available in the **Remittance files for vendors** form.

## See also

[(ESP) AEB remittance formats](esp-aeb-remittance-formats.md)

[(ESP) Generate a customer payment remittance file](esp-generate-a-customer-payment-remittance-file.md)

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

  


