---
title: Enter and post invoices for recurring expenses
TOCTitle: Enter and post invoices for recurring expenses
ms:assetid: 475d2720-eeaf-4d38-ad7a-44d3715c8e63
ms:mtpsurl: https://technet.microsoft.com/library/Gg231396(v=AX.60)
ms:contentKeyID: 36966721
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Enter and post invoices for recurring expenses 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use voucher templates to streamline the process of entering invoices for recurring expenses, such as interest expenses or telephone expenses. You can use voucher templates with general journals or vendor invoice journals. You can create multiple voucher templates.

## Enter and save a voucher template

When you save a voucher template, you must specify how the template is used when new voucher amounts are created. You can select whether to use the original voucher total and line amounts, or the percentage of the original voucher total that is represented by each voucher line.

1.  Click **General ledger** \> **Journals** \> **General journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Select a journal, and then click **Lines**.

3.  Enter information for a voucher.

4.  Click **Functions** \> **Save voucher template**.

5.  In the **Save voucher template** dialog box, select a template type.
    
      - **Percent** – Use this template type if the total amount of the expense varies from period to period, such as a telephone expense that is allocated to several departments. When you use the template, you can enter the amount of the new transaction. The offset amounts are distributed to the lines according to the percentage of the original voucher total that is represented by each voucher line.
    
      - **Amount** – Use this template type if the total amount of the expense is the same from period to period, such as a fixed interest rate expense on a long-term note.

6.  Click **OK**. The voucher template is saved, and you can select it when you enter future expenses.

## Select a voucher template

When you create a voucher based on a **Percent** type voucher template, the percentage that was calculated for each line in the template is applied to the value that is entered in the **Voucher amount** dialog box to determine the amounts for the new voucher lines.

1.  Click **General ledger** \> **Journals** \> **General journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Select a journal, and then click **Lines**.

3.  Click **Functions** \> **Select voucher template**.

4.  In the upper pane of the **Voucher templates** form, select a voucher template. Information about the template is displayed in the lower pane.

5.  Click **OK**.

6.  If the voucher template type is **Percent**, the **Voucher amount** dialog box is displayed. Enter the amount of the new voucher, and then click **OK**. You must enter an amount that is greater than zero.

7.  In the **Journal voucher** form, you can change the voucher, as needed.

## See also

[Journal voucher - General journal (form)](https://technet.microsoft.com/library/aa591466\(v=ax.60\))

[Journal voucher - Invoice journal (form)](https://technet.microsoft.com/library/aa616218\(v=ax.60\))

[Voucher templates (form)](https://technet.microsoft.com/library/hh209570\(v=ax.60\))

  


