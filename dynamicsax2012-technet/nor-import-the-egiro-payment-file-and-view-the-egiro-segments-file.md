---
title: (NOR) Import the eGiro payment file and view the eGiro segments file
TOCTitle: (NOR) Import the eGiro payment file and view the eGiro segments file
ms:assetid: 275fe80a-2c7c-4529-ab85-1110e226bc1d
ms:mtpsurl: https://technet.microsoft.com/library/Gg231002(v=AX.60)
ms:contentKeyID: 36056210
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Norway
---

# (NOR) Import the eGiro payment file and view the eGiro segments file 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

eGiro is an electronic payment method that uses a structured file format to automatically post payments that are received from customers. The eGiro EDI file format is based on the international United Nations standard EDIFACT CREMUL (Multiple Credit Advice Message) format. When you set up your eGiro parameters, you can specify the segment groups that should not be imported when an eGiro file is imported.

Use the **eGiro import** form to import the eGiro payment file to match payment lines with the open customer transactions. The import file will include only the segment groups that you have stipulated.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new journal and then click **Lines** to open the **Journal voucher** form.

3.  Click **Functions** and select **Import payments**.

4.  In the **Load diskette with payments** form, in the **Method of payment** field, select the method of payment with the **eGiro Innbetaling Pluss** import format.

5.  Click **OK** to open the **BBS import eInvoice** form. View or modify the information in the following fields:
    
      - **File name**: The name and location of the import file.
    
      - **Print import file**: Select this check box to print the import file report.
    
      - **Print payment lines**: Select this check box to print the payment lines in the report.
    
      - **Archive the file**: Select this check box to archive the import file in the database. You can view the archived file in the **File archive** form.
    
      - **Analyze the file**: Select this check box to analyze imported payment lines with the status of **Rejected**.
    
      - **Customer bank account test.**: Select this check box to save the bank account information in the import file as the default bank account information if the customer bank details are not entered in the **Bank account trap** form.

6.  Click **OK** to start the import process. The payment lines in the import file are matched with open customer transactions that are not yet settled, and the status is updated accordingly.
    
    After the import is complete, the status of the payment lines in the **Payment status** field is changed to either **Approved** or **Rejected**. The reason for the rejection of a payment line is displayed in the **Note** field on the **Payment** tab.

7.  When all the payment lines have an **Approved** status, validate and post the journal.

8.  Close the forms to save your changes.

## See also

[(NOR) Set up eGiro parameters](nor-set-up-egiro-parameters.md)

[(NOR) Set up the eGiro method of payment](nor-set-up-the-egiro-method-of-payment.md)

  


