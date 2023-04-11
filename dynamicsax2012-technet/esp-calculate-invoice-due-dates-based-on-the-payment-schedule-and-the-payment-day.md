---
title: (ESP) Calculate invoice due dates based on the payment schedule and the payment day
TOCTitle: (ESP) Calculate invoice due dates based on the payment schedule and the payment day
ms:assetid: 4c1163d8-2c22-4980-a10d-191ad08e932b
ms:mtpsurl: https://technet.microsoft.com/library/Dn304973(v=AX.60)
ms:contentKeyID: 54899951
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.PaymSched
- Forms.PaymDay
- Forms.PaymDueDateLimits_ES
- ES – 00004
- MsDynAx060.Forms.PaymSched
- MsDynAx060.Forms.PaymDay
- MsDynAx060.Forms.PaymDueDateLimits_ES
audience: Application User
ms.search.region: Spain
---

# (ESP) Calculate invoice due dates based on the payment schedule and the payment day 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012_

You can specify the payment schedule and the payment day for a customer invoice, a free text invoice, a vendor invoice, or a project invoice before you generate the invoice. Microsoft Dynamics AX calculates the payment due dates of vendor invoices and project invoices based on the delivery dates of items and services. For customer invoices, Microsoft Dynamics AX calculates the due dates based on the customer invoice receipt dates.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 4 for AX 2012.</P>



You can specify the number of days in the grace period, within which an invoice payment must be made in the **Due date limits** form. For more information, see [(ESP) Set up due date limits to calculate invoice due dates](esp-set-up-due-date-limits-to-calculate-invoice-due-dates.md) and [(ESP) Due date limits (form)](https://technet.microsoft.com/library/jj923623\(v=ax.60\)). You can select the **Use the delivery date to calculate the payment due date** check box in the **Terms of payment** form to use the delivery date to calculate the invoice due dates. For more information, see [(ESP) Assign due date limits to terms of payment to calculate invoice due dates](esp-assign-due-date-limits-to-terms-of-payment-to-calculate-invoice-due-dates.md) and [(ESP) Terms of payment (modified form)](https://technet.microsoft.com/library/jj910987\(v=ax.60\)).

You must specify a payment due date that comes before the due date limit for an invoice. You can set the payment schedule and the payment day for an invoice and manually calculate the invoice due date. If the date comes after the due date limit that is set in the **Due date limits** form, then you must correct the due date.

  


