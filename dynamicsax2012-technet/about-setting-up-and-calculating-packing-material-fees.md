---
title: About setting up and calculating packing material fees
TOCTitle: About setting up and calculating packing material fees
ms:assetid: b14b557c-aa9c-4772-ba76-5f67046dfaaf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498648(v=AX.60)
ms:contentKeyID: 36058973
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About setting up and calculating packing material fees [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In addition to specifying the base data that is defined for the packaging material, you must specify packaging-material-fee base data. To calculate fees and print reports, you must also set up packaging-material-fee license numbers for your customers.

## Define packaging material fees

For each type of material, define the period of validity, price per material, currency, and unit.

## Set up customer packaging-material-fee license numbers

If the customers pay the packaging material fees, specify the customers' packaging-material-fee license numbers in the **Customers** form. When a license number has been assigned to a customer, the packaging material fees are calculated automatically when sales orders are invoiced. After invoicing, the **Calculate fee** check box is cleared in the **Packing material transactions** form, because you do not have to calculate and print a report. You can print the packaging material weights on the invoice, and inform the customers that they pay the fees.

If your company pays the packaging material fees, do not specify the customer license numbers. After invoicing, the **Calculate fee** check box is selected in the **Packing material transactions** form. This indicates that the fees are calculated when a report is created. You can print the weights on the invoice, and indicate that your company pays the fees.

## Print packaging material weights on invoices

You can print the packaging material weights on the invoice, and indicate who pays the packaging material fees. The weights are summarized by packaging code.

## Tasks that use this form

[Define packing material fees](define-packing-material-fees.md)

[Print packing material weights on invoices](print-packing-material-weights-on-invoices.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

