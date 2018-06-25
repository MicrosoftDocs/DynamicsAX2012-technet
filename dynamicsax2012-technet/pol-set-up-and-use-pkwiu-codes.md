---
title: (POL) Set up and use PKWiU codes
TOCTitle: (POL) Set up and use PKWiU codes
ms:assetid: 6ba96fc7-95db-4216-a7df-12f7d3c5a418
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678231(v=AX.60)
ms:contentKeyID: 49386953
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (POL) Set up and use PKWiU codes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The PKWiU code is used for tax purposes to categorize goods and services sold in Poland. It is included on all sales order invoices, free text invoices, and invoices posted from the Project module.

You can view the PKWiU code in the project invoice. Print the project invoice by using the **Invoice journals** form.

## Set up notifications for when a PKWiU code is missing from an invoice

To ensure that users include a PKWiU code on all invoices, select one of the following options for the **PKWiU code requirement** field on the **Accounts receivable parameters** form:

  - **None** – Do not display a message when a PKWiU code is missing from a sales order or a free text invoice. The PKWiU code is not required for invoices.

  - **Warning** – Display a message when you invoice a sales order or a free text invoice that is missing the PKWiU code.

  - **Error** – Display a message when you invoice a sales order or a free text invoice that is missing the PKWiU code and stop the invoice from being processed.

## Assign a PKWiU code to the sales category hierarchy

Category hierarchies are used to classify products or transactions for reporting and analysis. The category hierarchy that is of the **Sales category hierarchy** type is used for organizing products for sales activities. You can assign a PKWiU code to the sales category hierarchy so that the PKWiU code is included on invoices that include non-inventoried items.

1.  Click **Product information management** \> **Setup** \> **Categories** \> **Category hierarchies**. Select the sales category hierarchy. On the **Action Pane**, click **Edit**.

2.  On the **Assign PKWiU code** FastTab, enter the PKWiU code for the sales category hierarchy.

## Assign a PKWiU code to released products

1.  Click **Product information management** \> **Common** \> **Released products**. Select the released product to assign a PKWiU code to. On the **Action Pane**, click **Edit**.

2.  On the **Sell** FastTab, enter the PKWiU code for the released product.

## See also

[Invoice journals (form) (Project)](https://technet.microsoft.com/en-us/library/aa618187\(v=ax.60\))

[Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

