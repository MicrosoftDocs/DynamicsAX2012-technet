---
title: About general budget reservations (Public sector)
TOCTitle: About general budget reservations (Public sector)
ms:assetid: 88e136c2-66bf-4087-8882-17095e3a8d14
ms:mtpsurl: https://technet.microsoft.com/library/Dn792456(v=AX.60)
ms:contentKeyID: 65205500
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- commitment
- budget reservation
- budget reservations
- general budget reservation
- general budget reservations
audience: Application User
ms.search.region: Denmark, France
---

# About general budget reservations (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A general budget reservation, sometimes referred to as a commitment, is a document often used by public sector entities to set aside or earmark budgeted funds so that they are not available for other purposes. Typically these reservations are made before any vendors have been selected for the purchase. Using general budget reservations, an organization can explicitly track planned expenditures for management and reporting. Each purchase requisition, purchase order, or vendor invoice that is generated can be associated with at least one general budget reservation.


> [!NOTE]
> <P>General budget reservations are available only if the following conditions are met:</P>
> <UL>
> <LI>
> <P>You have Microsoft Dynamics AX 2012 R3 Cumulative Update 8 installed, with Procurement and Sourcing, and have installed the following hotfix: KB3047235</P>
> <LI>
> <P>The <STRONG>Public Sector</STRONG>, <STRONG>Encumbrance process</STRONG>, and <STRONG>Pre-encumbrance process</STRONG> configuration keys are selected.</P>
> <LI>
> <P>You are using posting definitions (not required if you do not activate commitment accounting).</P>
> <LI>
> <P>Budget control configuration is activated and configured, and budget control is turned on.</P></LI></UL>



General budget reservations contain lines which detail the purpose of the reservation and specifics about the planned reserved funds, including the start and end dates for the reservation. You can add, change, and delete lines, and specify various details such as the item requested, currency, unit price and quantity, and total amount.


> [!NOTE]
> <P>General budget reservations are intended for use with public sector entities. Private sector entities use the term “budget reservation” with encumbrances or with pre-encumbrances, but such reservations, unlike general budget reservations, are not documents in their own right. For more information, see <A href="encumber-purchase-orders.md">Encumber purchase orders</A>.</P>



You can create different types of general budget reservation in order to specify various characteristics and requirements, according to your purchasing needs. For example, you might create three reservation types for use with purchase requisitions, purchase orders, and vendor invoices. A reservation type defines characteristics, such as workflow, and default values for the budget reservation. For information about using workflow with general budget reservations, see [Set up general budget reservation workflows (Public sector)](set-up-general-budget-reservation-workflows-public-sector.md).

In the general budget reservation, you can also view accounting distributions and subledger journal lines for the transaction. For more information, see [About accounting distributions and subledger journal entries for vendor invoices](about-accounting-distributions-and-subledger-journal-entries-for-vendor-invoices.md) and [About accounting distributions and subledger journal entries for purchase orders](about-accounting-distributions-and-subledger-journal-entries-for-purchase-orders.md).

If you use project accounting, you can enable committed cost tracking for general budget reservations. For more information, see [Use project accounting with general budget reservations (Public sector)](use-project-accounting-with-general-budget-reservations-public-sector.md).

You can carry over general budget reservations from one fiscal year to the next. For more information, see [Carry forward general budget reservation information to a new fiscal year (Public sector)](carry-forward-general-budget-reservation-information-to-a-new-fiscal-year-public-sector.md). You can also close or finalize a completed or expired general budget reservation at year-end. For more information, see [Finalize a general budget reservation (Public sector)](finalize-a-general-budget-reservation-public-sector.md).

A general budget reservation is relieved depending on which document references it. If the document is a purchase order, the reservation is relieved when the purchase order is confirmed. If the document is an invoice, and does not reference a purchase order or purchase agreement, the general budget reservation is relieved when the invoice is posted. If the document is a purchase requisition, the reservation is relieved when the requisition is approved. For more information, see [About purchase requisitions](about-purchase-requisitions.md), [Create a purchase order](create-a-purchase-order.md) , and [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md).

## Basic process for general budget reservations

The basic process for using general budget reservations is as follows:

1.  [Set up general budget reservation rules and reservation types (Public sector)](set-up-general-budget-reservation-rules-and-reservation-types-public-sector.md)

2.  [Create a general budget reservation (Public sector)](create-a-general-budget-reservation-public-sector.md)

3.  [Relieve a general budget reservation (Public sector)](relieve-a-general-budget-reservation-public-sector.md)

4.  [Finalize a general budget reservation (Public sector)](finalize-a-general-budget-reservation-public-sector.md)

## See also

[Budgeting (Public sector)](budgeting-public-sector.md)

  


