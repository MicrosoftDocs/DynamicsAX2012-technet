---
title: (FRA) Apply a penalty when a customer payment is past due
TOCTitle: (FRA) Apply a penalty when a customer payment is past due
ms:assetid: 7b10ef47-c7db-47fe-9d92-23ea0a1fad1b
ms:mtpsurl: https://technet.microsoft.com/library/Dn304978(v=AX.60)
ms:contentKeyID: 54899956
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- FR – 00018
audience: Application User
ms.search.region: France
---

# (FRA) Apply a penalty when a customer payment is past due 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

You can apply a penalty when a customer payment is past due. You can print the lump sum recovery text that displays the penalty amount that must be paid on the invoice, and the due date of the payment. For more information about how to set up and print the lump sum recovery text on a customer invoice, see [(FRA) Configure and print a lump sum recovery text on a customer invoice](fra-configure-and-print-a-lump-sum-recovery-text-on-a-customer-invoice.md).


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 5 for AX 2012.</P>



## What is lump sum recovery text?

Lump sum recovery text shows the penalty amount and the due date for the payment. The penalty amount is applied if the payment is past the due date. Lump sum recovery text is printed on the customer invoice. You can specify the penalty amount and the currency along with any instructions in the **Lump sum recovery text** field in the **Invoice** area on the **Form setup** form.

## How do I print lump sum recovery text on a customer invoice?

First, you can use the **Form setup** form to set up the parameters to print lump sum recovery text. Next, you can use the **Posting invoice** form or the **Invoice journal** form to print lump sum recovery text on a customer invoice.

## When do I apply a penalty to a customer payment?

You can apply a penalty on a customer payment when the payment is not received, and it is past the due date. For more information about how to apply penalty on customer payments and settle customer payments, see [Key tasks: Customer payments and settlements](key-tasks-customer-payments-and-settlements.md).

## What documents is lump sum recovery text printed on?

After you set up the parameter to print lump sum recovery text, it is printed on the following customer documents:

  - Customer invoices

  - Free text invoices

  - Customer proforma invoices

  - Customer credit notes

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  


