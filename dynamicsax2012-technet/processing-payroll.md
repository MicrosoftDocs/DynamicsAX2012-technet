---
title: Processing payroll
TOCTitle: Processing payroll
ms:assetid: d372d8bf-a2ec-41d1-9ed6-3731b84dea9a
ms:mtpsurl: https://technet.microsoft.com/library/JJ677364(v=AX.60)
ms:contentKeyID: 49384139
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- payroll processing
audience: Application User
ms.search.region: USA
---

# Processing payroll 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You use a combination of manual and automated tasks when you process payroll. This topic contains a high-level overview of the end-to-end process and links to more detailed information.


> [!TIP]
> <P>When you automatically generate earnings or pay statements, we recommend that you use the batch processing mode to improve performance.</P>



These topics include information about payroll processing tasks that are outside the typical end-to-end process flow:

  - To reprint pay statements, replace paychecks that have been lost or damaged, and perform similar tasks after pay statements have been generated or payments have been issued to workers, see [Work with existing payroll payments](work-with-existing-payroll-payments.md).

  - To process payroll when you transfer Payroll beginning balances, see [Payroll beginning balance tasks](payroll-beginning-balance-tasks.md).

  - To find answers to common questions, see [Earnings and the earnings generation process](earnings-and-the-earnings-generation-process.md) and [Pay statements and the payment generation process](pay-statements-and-the-payment-generation-process.md).

This illustration shows the basic steps for processing payroll. The numbers correspond to the steps below.

![Basic steps for processing earnings](images/JJ677320.Payroll_Processing_earnings_basics(AX.60).gif "Basic steps for processing earnings")

## 1\. Generate earnings

You can generate earnings for workers in multiple ways. You can automatically generate earnings for salaried positions, for positions that use a schedule, and for recurring earnings, premium earnings, and retroactive earnings. You can also enter earnings manually.

You must manually enter some earnings, such as overtime earnings, sick time, and paid time off. You can enter these earnings either before or after you use the automated process to generate the standard earning lines. If you use the automated process first, you have to add and remove earning lines manually until the earnings statement is correct.

For more information about the earnings generation process, see [Generate earnings](generate-earnings.md).

Premium earnings and retroactive earnings are not available prior to Microsoft Dynamics AX 2012 R3 cumulative update 8.

## 2\. Release earnings

To process payments for workers, you must release the earnings. If you have to, you can hold some earnings when the remaining earnings are released for payment.

For information about how to hold, release, or change earnings, see [Work with existing earnings](work-with-existing-earnings.md).

## 3\. Generate pay statements

When you generate pay statements, all worker deductions and employer contributions for benefits and taxes are calculated, benefit accruals are processed, and the worker’s net pay is determined. Completed pay statements are used to issue worker payments.

For information about how to generate or change pay statements, see [Work with pay statements](work-with-pay-statements.md).

## 4\. Issue worker payments

You can pay workers by check or by electronic payment. When you submit pay statements, an invoice is created and posted to the general ledger for the sum of the worker’s net pay for the vendor. A payment journal that has lines is created, which lets you generate and post payments. You can optionally post the payroll costs that are associated with workers to the general journal when you submit payments.

For information about how to submit pay statements, generate payments, generate a positive pay file, and post the payment journal, see [Issue worker payments](issue-worker-payments.md).

## 5\. Post payroll and generate vendor invoices

When you post payroll, the accounting distributions that are specified on each pay statement line determine the correct offset accounts to use. When each line has a balanced transaction, all transactions for the pay statement can be entered in the general ledger.

After you post payroll, you will generate vendor invoices for the payables that resulted from the pay period that you posted. This process combines the amounts from all the pay statements that were posted for the period, and uses the benefit and tax setup information to create an invoice for each vendor. The totals and their corresponding accounting distributions from the original pay statement lines are used to create the invoices.

For more information, see [Post payroll and generate vendor invoices](post-payroll-and-generate-vendor-invoices.md).

  


