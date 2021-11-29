---
title: (ESP) Generate a customer payment remittance file
TOCTitle: (ESP) Generate a customer payment remittance file
ms:assetid: 7c962c7a-8735-45df-9015-3dd7a6b5c221
ms:mtpsurl: https://technet.microsoft.com/library/Gg213132(v=AX.60)
ms:contentKeyID: 36058265
author: Khairunj
ms.date: 05/28/2014
mtps_version: v=AX.60
f1_keywords:
- SEPA
- CustSumForPaymRemittance
- Bill of exchange
- LedgerJournalTable_CustPaymRemittance
- remittance file format
- SEPA credit transfer
- remittance journal
audience: Application User
ms.search.region: Spain
---

# (ESP) Generate a customer payment remittance file 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to generate remittance files for a selected method of payment format. You can generate remittance files for a bill of exchange (BOE) that is created for Single European Payment Area (SEPA). Before you create the remittance journal, complete the following tasks:

  - Set up methods of payment. For more information, see [(ESP) Set up methods of payment for payment remittance files](esp-set-up-methods-of-payment-for-payment-remittance-files.md).

  - Optional: Post a free text invoice for a customer. For more information, see [Key tasks: Free text invoices](key-tasks-free-text-invoices.md).

  - Post a free text invoice for a customer account for the selected SEPA methods of payment.

  - Draw a BOE and settle open transactions. For more information, see [Draw a bill of exchange](draw-a-bill-of-exchange.md).


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R3. For more information, see the section later in this topic.</P>



## Create a remittance journal and generate a remittance file in AX 2012 and AX 2012 R2

Use the following procedures to create a remittance journal for the selected remittance format, and to generate a remittance file.

## Create a remittance journal

To create a remittance journal for the posted customer invoices, follow these steps:

1.  Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Remittance journal**.

2.  Select a journal that uses the **Customer bank remittance** journal type.

3.  On the **Bill of exchange** tab, select a remittance type and a bank account.

4.  Click **Lines**, and then select a customer account.

5.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

6.  Select the **Mark** check box next to an open BOE transaction.

7.  Close the **Settle open transactions** form. Click **Post** \> **Post**.

## Generate a remittance file

To generate a remittance file, follow these steps:

1.  In the **Journal voucher** form, click **Functions** \> **Generate remittance**.

2.  In the **Method of payment** field, select a method of payment that uses the **Remittance Format 19,32 & 58 AEB(ES)** format, and then click **Dialog**. The **Remittance Format 19,32 & 58 AEB(ES)** dialog box opens.

3.  In the **Remittance format** field, select the export format for the selected method of payment.
    
    For example, select **Format 19 proc. 1** or **Format 19 Proc. 2** for direct debit payments. Select **Format 32** for remittance payments or **Format 58** for advanced payments.

4.  Depending on the format that you selected, enter additional information. For example:
    
      - If you selected **Format 32**, indicate whether to attach physical drafts to the remittance file, and select which type of document to attach, such as a BOE.
    
      - If you selected **Format 19 proc. 1** or **Format 19 Proc. 2**, enter the date on which the payment is requested.

5.  Enter the file name and location to create the remittance file.

6.  Select the **Control report** check box to print a report that displays information about the transactions that are included in the remittance file.

7.  Click **OK**.

8.  In the **Generate remittance** form, click **OK**. The remittance file is generated and the **Bank remittance** report is printed.

9.  Review the control report. If changes are needed, repeat steps 2 through 8 to regenerate the remittance file.

## Generate a remittance file for a selected SEPA format in AX 2012 R3, AX 2012 R2, and AX 2012

To generate a remittance file for posted customer invoices, follow these steps:

1.  Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Remittance journal**.

2.  Select a journal that uses the **Customer bank remittance** journal type.

3.  On the **Bill of exchange** tab, select a remittance type and a bank account.

4.  Click **Lines**, and then select a customer account that uses a SEPA payment.

5.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

6.  Select the **Mark** check box next to an open BOE transaction.

7.  Close the **Settle open transactions** form. Click **Post** \> **Post**.

8.  Click **Functions** \> **Generate remittance**.

9.  In the **Remittance format** field, select the export format for the selected method of payment.

10. Enter the file name and location to create the remittance file.

11. Select the **Control report** check box to print a report that displays information about the transactions that are included in the remittance file.

12. Click **OK**.

13. In the **Generate remittance** form, click **OK**. The remittance file is generated, and the **Bank remittance** report is printed.

## See also

[(ESP) AEB remittance formats](esp-aeb-remittance-formats.md)

[(ESP) Generate a vendor payment remittance file](esp-generate-a-vendor-payment-remittance-file.md)

  


