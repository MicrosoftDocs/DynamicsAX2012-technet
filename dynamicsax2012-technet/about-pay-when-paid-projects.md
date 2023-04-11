---
title: About pay-when-paid projects
TOCTitle: About pay-when-paid projects
ms:assetid: a2e5cbdb-2b98-4fb7-be4f-37061e762c33
ms:mtpsurl: https://technet.microsoft.com/library/Hh292606(v=AX.60)
ms:contentKeyID: 36655945
author: tfehr
ms.author: daxcpft
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project add-in
- customer invoices
- vendor payments
- pay when paid
- vendor invoices
- customer payments
- partial vendor payments
- PWP terms
- pay-when-paid
- PWP projects
audience: Application User
ms.search.region: Global
---

# About pay-when-paid projects 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you approve a vendor as a subcontractor to work on a project, you might want to withhold payment to the vendor or subcontractor until you have been paid by your customer for the project. To retain a payment to a vendor, you set up pay-when-paid (PWP) terms when you set up the purchase order with the vendor.

When you create a purchase order for the vendor and assign a project ID to the purchase order, PWP terms in the project are associated with the purchase order and the vendor. In the **Vendor invoices with pay when paid** form, you can view a list of the unpaid vendor invoices for a purchase order and the associated customer invoices. Use this form to determine whether and how much to pay a vendor. For example, when a customer pays an amount on a project invoice, you can release part or all of the related vendor invoices for payment.

You can set up PWP terms to specify payment to a vendor after you receive a specific percentage of the related payment from a customer. When you receive partial payment from a customer, you can manually release some of the related vendor invoices for payment.

The following example shows how you can use PWP terms to withhold payment to a vendor or subcontractor until you are paid by the customer.

## Example

Your organization enters into an agreement with a customer to provide 100 computers on which you install the software requested by the customer. The price that you and the customer agree on for each computer is 150.00.

You engage the services of a third-party vendor to provide the computers to you. The customer wants to approve the quality of the computers before the customer pays your organization. Your organization’s policy is to withhold payment to a third-party vendor until you have been paid by the customer on a project. You set up the project with a PWP percentage of 100 percent. Therefore, you withhold all payments to the vendor until you receive full payment for the customer invoice.

The vendor charges 100.00 for each computer. When the vendor sends the computers to you, they also include an invoice for 10,000.00 for 100 computers. Because you have set up the project with PWP terms, you do not pay the vendor.

After you receive the computers from the vendor, you install the required software on the computers. When you send the computers to the customer, you also send the customer an invoice for 15,000.00. The customer inspects the computers and approves the quality of the product. The customer pays your organization the full amount of the project invoice.

After you receive the full payment from the customer, you pay 10,000.00 to the vendor for the full amount of the vendor invoice.

## See also

[Vendor invoices with pay when paid (form)](https://technet.microsoft.com/library/hh227358\(v=ax.60\))

[Key tasks: Manage pay-when-paid projects](key-tasks-manage-pay-when-paid-projects.md)

  


