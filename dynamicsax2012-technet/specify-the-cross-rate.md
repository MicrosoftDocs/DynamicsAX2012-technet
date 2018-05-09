---
title: Specify the cross rate
TOCTitle: Specify the cross rate
ms:assetid: dff2dc6c-3826-4cac-9dac-b1279ed55ac8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551296(v=AX.60)
ms:contentKeyID: 37822163
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Specify the cross rate 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains the purpose of a cross rate, and how to specify the cross rate when you settle a payment with an invoice. Use a cross rate when all of the following criteria apply:

  - You are settling a payment with an invoice.

  - The payment line and the invoice line use different currencies.

  - Neither currency is the accounting currency.

For example, the accounting currency is USD, the invoice currency is CAD, and the payment currency is EUR. The cross rate lets you enter an exchange rate to translate directly between CAD and EUR, and not have to translate through USD.

When you select an invoice and a primary payment, you can enter a cross rate for the invoice line. The cross rate is the exchange rate between the currencies for those transactions, as of the settlement date.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select the customer or vendor whose open transactions you are settling.

3.  On the **All customers** list page, click **Collect** \> **Settle open transactions**.
    
    –or–
    
    On the **All vendors** list page, click **Invoice** \> **Settle open transactions**.

4.  Select the transaction that is the primary payment, and then click **Mark payment**. The check box in the **Mark** column is selected, and an information icon is shown in the **Primary payment** column.

5.  In the **Cross rate** field, enter the exchange rate between the invoice currency and the payment currency, as of the settlement date.

## See also

[Settle transactions with payments](settle-transactions-with-payments.md)

[Reverse settlements](reverse-settlements.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

