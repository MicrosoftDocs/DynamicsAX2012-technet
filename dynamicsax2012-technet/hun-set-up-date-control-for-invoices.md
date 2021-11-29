---
title: (HUN) Set up date control for invoices
TOCTitle: (HUN) Set up date control for invoices
ms:assetid: 05bf4eab-d4da-4c16-abe4-82474d50d995
ms:mtpsurl: https://technet.microsoft.com/library/JJ733508(v=AX.60)
ms:contentKeyID: 49685472
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Set up date control for invoices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use date control in Microsoft Dynamics AX to make sure that invoices and credit notes for customer transactions are generated within a specified time period after an order is fulfilled. For example, if your organization specifies that invoices must be generated within a 15 day period, and a service is provided to a customer on September 9, the invoice for the transaction must be generated no later than September 24.

You enable the date control fields in the **Updates** area in the **Accounts receivable parameters** form. You can specify the number of days that can pass after an order is fulfilled before the date control actions occur. After the specified time period, a warning or error message is displayed when you attempt to post the invoice.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the left pane, click **Updates**.

3.  In the **Invoice date control** and **Credit note date control** fields, select one of the following options:
    
      - **None** – No date control is applied.
    
      - **Warning** – If the invoice date is later than the fulfillment date by more than the allowed number of days, a warning message is displayed when you attempt to post the invoice. However, you can complete the posting process.
    
      - **Error** – If the invoice date is later than the fulfillment date by more than the allowed number of days, an error message is displayed when you attempt to post the invoice. In this case, you cannot complete the posting process.
        
        Modify the invoice or fulfillment date, and then complete the posting process.

4.  In the **Document date control** field, select one of the following options:
    
      - **None** – No date control is applied.
    
      - **Warning** – If you change the fulfillment date so that it no longer matches the date in Microsoft Dynamics AX, a warning message is displayed. However, you can still change the fulfillment date.
    
      - **Error** – If you change the fulfillment date so that it no longer matches the date in Microsoft Dynamics AX, an error message is displayed. In this case, you cannot change the fulfillment date.

5.  In the **Number of days** field, enter the number of days that can pass after an order is fulfilled before the date control actions occur.

## See also

[Invoicing](invoicing.md)

[Creating credit notes](creating-credit-notes.md)

  


