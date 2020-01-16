---
title: Set up product compliance parameters
TOCTitle: Set up product compliance parameters
ms:assetid: 76b5f756-d691-4fc0-9695-23c0953ecbeb
ms:mtpsurl: https://technet.microsoft.com/library/Hh352212(v=AX.60)
ms:contentKeyID: 36687847
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up product compliance parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up parameters to create and maintain product compliance records. You can select which parameters to set up for your company.

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  Click the **Product compliance** FastTab.

3.  In the **Administrator user ID** field, select the user identification for the product compliance administrator. This user receives the notifications that you select in the **Product safety data sheet notifications** group.

4.  In the **Product safety data sheet validity in days** group, set up the following parameters:
    
      - **Validity in days** – Enter the default number of days that product safety data sheets are valid from their approval date.
    
      - **Expiry advice in days** – Enter the number of days before the expiration date of product safety data sheets that users are notified of the pending expiration.

5.  In the **Annual reporting quantity** group, select the start and end dates used to calculate annual quantities for reporting usage data.

6.  In the **Compliance** group, select the options that are required to issue user warnings when product safety data sheets are expired or were never sent to the customer. You can decide to print these documents at the time when packing slips are printed to provide to customers who never received the documents. You can also prevent the posting of packing slips and invoices when the documents are expired.

7.  In the **Product safety data sheet control** group, select the option to require users to specify a reason when product safety data sheets are modified. You also select the basis to use for determining the effective date for product safety data sheets when sales order and purchase order transactions are generated. You can select from the following options:
    
      - **Current date** — Use the product safety data sheet that is in effect on the date that the sales order or purchase order is entered as the active document.
    
      - **Delivery date** — Use the product safety data sheet that is in effect on the requested delivery date for the sales order or purchase order as the active document. This is the date on which the sales order or purchase order is expected to ship.

8.  In the **Product safety data sheet notifications** group, select the options for issuing alerts and warnings to the product compliance administrator. This is done when product safety data sheets are either expired or were never sent to the customer. You can also select printing and posting parameters.

## See also

[(PM) Inventory and warehouse management parameters (form)](https://technet.microsoft.com/library/hh352320\(v=ax.60\))

  


