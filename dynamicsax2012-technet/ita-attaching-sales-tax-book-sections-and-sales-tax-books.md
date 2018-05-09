---
title: (ITA) Attaching sales tax book sections and sales tax books
TOCTitle: (ITA) Attaching sales tax book sections and sales tax books
ms:assetid: 993ba587-7380-4b87-a7dd-1473c1adec95
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209422(v=AX.60)
ms:contentKeyID: 36058691
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (ITA)
- Attaching a sales tax book section to a sales tax book
- Sales tax book
- Sales tax book section
---

# (ITA) Attaching sales tax book sections and sales tax books 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Italy, every value-added tax (VAT) transaction must belong to a tax book. VAT books can be of the type **Sales**, **Purchase**, or **Summary**. After you set up Italian sales tax books and number sequence codes, you must attach the sales tax book to the sales tax book type. The sales tax book type is required to make sure that all sales and purchase transactions will be included in the Italian sales tax payment report. Then, you must create sales tax book sections to attach to the sales tax book. For more information about setting up Italian sales tax books and generating the Italian sales tax payment report, see the **Set up the Italian sales tax book** and **Generate the sales tax payment report** section in [(ITA) Reverse a conditional sales tax transaction and generate the sales tax payment report](ita-reverse-a-conditional-sales-tax-transaction-and-generate-the-sales-tax-payment-report.md). The sales tax book sections are visible in the following forms:

  - **Accounts receivable parameters**

  - **Accounts payable parameters**

  - **Project management and accounting parameters**

  - **Journal names** in **Project management and accounting**

  - **General ledger parameters** in **General ledger**

## Setting up number sequences for sales tax book sections

Each sales tax book section must be attached to a number sequence and to a sales tax book. The number sequence codes that are selected for a sales tax book section are those that are attached to the transactions that will generate a VAT transaction. When you attach each sales tax book section to a sales tax book or to the particular purchase or sales transaction type, you must choose the following criteria for sales tax books of the type **Purchase**, **Sales**, or **Not included**:

  - If a sales tax book of the type **Purchase** is selected, you can only select purchase number sequences in the **Number sequence code** field.

  - If a sales tax book of the type **Sales** is selected, you can only select sales number sequences in the **Number sequence code** field.

  - If a sales tax book of the type **Not included** is selected, you can select a number sequence that has not been selected for a different sales tax book section as **Purchase**, **Sales**, or **Not included**. The sales tax book of the type **Not included** will not be included in the final sales tax reporting.

For the voucher to follow the number sequence of the invoice or credit note, you must select the **Reuse numbers** check box when you set up the number sequences for those invoices and credit notes. For example, in the **Accounts receivable parameters** form, in the **Number sequences** link, select the **Reuse numbers** check box for the **Free text invoice voucher** to synchronize the number allocation for the **Free text invoice voucher** and **Free text invoice**.

In the **Italian sales tax book sections** form, you can create sales tax book sections manually for each purchase or sales transaction type, or you can click **Create** to create the sales tax book section. If you have set up several number sequences for purchase vouchers, sales vouchers, or credit note vouchers, you must create a sales tax book section for each of the existing number sequences. In the **Italian sales tax book sections** form, the voucher number of each voucher number sequence will be attached to the sales tax book section in the **Number sequence code** field. Voucher numbers that are assigned during posting must be sequentially ordered by the posting date, and the sales tax transactions within the same number sequence code must be posted in sequence. If the voucher numbers are not sequentially ordered, an error message is displayed. In addition, posting is interrupted if a sales transaction is not assigned to any sales tax book section when you update a sales invoice.

When you create a sales tax book section, a default sales tax book will be attached to each sales tax book section according to the selection in the **Sales tax book type** field. If several sales tax books with the same type exist, the first sales tax book will be used by default, although you can change this. The **Sales tax book section** and **Name** fields will both be filled in with the identification and name of the number sequence code in the **Number sequences** form. Additionally, you can change the name of the sales tax book section.

## See also

[(ITA) Italian sales tax book sections (form)](https://technet.microsoft.com/en-us/library/aa600627\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

