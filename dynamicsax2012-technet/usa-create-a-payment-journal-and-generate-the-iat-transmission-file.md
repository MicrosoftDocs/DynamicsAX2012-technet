---
title: (USA) Create a payment journal and generate the IAT transmission file
TOCTitle: (USA) Create a payment journal and generate the IAT transmission file
ms:assetid: cb94ad70-9743-45ee-8eeb-62696c7f51c0
ms:mtpsurl: https://technet.microsoft.com/library/Hh242854(v=AX.60)
ms:contentKeyID: 36059343
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- IAT
- USA
- payment journal
- transmission file
audience: Application User
ms.search.region: USA
---

# (USA) Create a payment journal and generate the IAT transmission file 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you process a payment to a vendor or refund a payment to a customer who is outside the United States, you must enter a payment transaction to generate the National Automated Clearing House Association – International ACH Transactions (NACHA-IAT) file. The key elements that cause an ACH transaction to be treated as an IAT transaction are the following:

  - A payment instruction is issued to create an ACH transaction.

  - The payment transaction is funded by, transmitted to, or received from a financial agency located outside the territorial jurisdiction of the United States.

  - A part of the transaction is processed through the United States ACH network.

## Create a payment journal

Create a payment journal to record payment transactions that use the IAT export format for the selected method of payment for the vendor or customer. For more information, see [Key tasks: Vendor payments and settlements](key-tasks-vendor-payments-and-settlements.md), [Reimbursements overview](reimbursements-overview.md), and [Refund customers overview](refund-customers-overview.md).

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.
    
    –or–
    
    Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new journal, and then click **Lines** to open the **Journal voucher** form. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  In the **Debit** field, enter the payment amount.

4.  In the **Method of payment** field, select the payment method for NACHA IAT.

5.  Click the icon next to the **Method of payment** field to open the **NACHA IAT information** form. The icon is available only when you enter an amount in the **Debit** field and select the payment method that you created in the **Method of payment** field in the **Methods of payment - vendors** or **Methods of payment - customers** form.

6.  In the **Foreign exchange indicator** field, select the foreign exchange indicator from the following options:
    
      - **None** – Foreign exchange conversion is not used.
    
      - **FV** – Fixed to variable. The entry originates in a fixed-value amount and is received in a variable amount, based on the foreign exchange conversion.
    
      - **VF** – Variable to fixed. The entry originates in a variable-value amount, based on a specific foreign exchange rate for conversion to a fixed-value amount in which the entry is received.
    
      - **FF** – Fixed to fixed. The entry originates in a fixed-value amount and is received in the same fixed-value amount in the same currency. There is no foreign exchange conversion for entries transmitted using this code. For entries that originate in a fixed-value amount, the **Foreign exchange reference** field will be null or filled with spaces.

7.  In the **Foreign exchange reference indicator** field, select the foreign exchange reference indicator from the following options:
    
      - **1** – Foreign Exchange Rate
    
      - **2** – Foreign Exchange Reference Number
    
      - **3** – Null or spaces

8.  In the **Foreign exchange reference** field, enter the foreign exchange reference.

9.  In the **Gateway operator OFAC screening indicator** and **Secondary OFAC screening indicator** fields, select the gateway operator OFAC screening indicator value and the secondary OFAC screening indicator value.

10. In the **Originating DFI qualifier** and **Receiving DFI qualifier** fields, select the originating DFI qualifier code and the receiving DFI qualifier code to specify the financial institution that initiates the payment transactions for the company.

11. Close the form to save your changes.

## Generate the IAT transmission file

You can generate the NACHA – IAT transmission file for vendor payments and customer refunds.

1.  In the **Journal voucher** form, click **Functions** \> **Generate payments** to open the **Generate payments** form.

2.  In the **Export format** field, select the **NACHA IAT (US)** format.

3.  In the **Bank account** field, select the bank account from which the payment is made and select the **Show format dialog** check box.

4.  Click **OK** to open the **NACHA IAT (US)** form.

5.  In the **File name** field, select the path, and then enter the file name.

6.  In the **Effective date** field, select the effective date.

7.  Click **OK** to export the file in the NACHA IAT (US) format.

8.  Close the forms to save your changes.

## See also

[(USA) Set up IAT ACH file parameters](usa-set-up-iat-ach-file-parameters.md)

[(USA) NACHA IAT information (form)](https://technet.microsoft.com/library/hh227435\(v=ax.60\))

  


