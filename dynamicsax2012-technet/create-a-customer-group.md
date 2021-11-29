---
title: Create a customer group
TOCTitle: Create a customer group
ms:assetid: 0f85526f-bfea-4ac7-b08d-7cd7fe2443fb
ms:mtpsurl: https://technet.microsoft.com/library/Aa496550(v=AX.60)
ms:contentKeyID: 36056020
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a customer group 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up groups that share characteristics such as payment terms and the length of time that it typically takes for payments to be received after an invoice is due. You can then assign these groups to customers.

1.  Click **Accounts receivable** \> **Setup** \> **Customers** \> **Customer groups**.

2.  Click **New**. In the **Customer group** field, enter a unique identifier for the customer group.

3.  In the **Description** field, enter a short description of the customer group.

4.  In the **Terms of payment** field, select the terms of payment that apply to customers who are assigned the selected customer group. Terms of payment are part of managing your customer accounts and are strongly recommended.
    
    For more information, see [Terms of payment (form)](https://technet.microsoft.com/library/aa588427\(v=ax.60\)).

5.  In the **Settle period** field, select the standard interval between the due date for payments from customers in the selected customer group, defined by the terms of payment, and the date on which the payments are received in your legal entity’s bank account. The settle period is used for liquidity calculations that are based on the cash flow forecast.

6.  To define ledger accounts for automatic ledger transactions that are related to the issuance of inventory to customers in the selected customer group, click **Setup** \> **Item posting**, and define the accounts.
    
    For more information, see [Item posting (form)](https://technet.microsoft.com/library/aa589971\(v=ax.60\)).

7.  To set up a sales forecast that applies to the customers in the customer group in the **Demand forecast** form, click **Forecast**.
    
    For more information, see [Demand forecast (form)](https://technet.microsoft.com/library/aa499758\(v=ax.60\)).


> [!NOTE]
> <P>For more information about the fields that are mentioned in this procedure, see <A href="https://technet.microsoft.com/library/aa550231(v=ax.60)">Customer groups (form)</A>.</P>



## See also

[Create a customer record](create-a-customer-record.md)

  


