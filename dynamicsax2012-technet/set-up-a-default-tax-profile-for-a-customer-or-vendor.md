---
title: Set up a default tax profile for a customer or vendor
TOCTitle: Set up a default tax profile for a customer or vendor
ms:assetid: 7e459c17-ceaa-4cfd-9bd1-73e9abff65e9
ms:mtpsurl: https://technet.microsoft.com/library/Aa571535(v=AX.60)
ms:contentKeyID: 37822148
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a default tax profile for a customer or vendor 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up a default tax profile for a customer or vendor. By default, the tax information is used when you create transactions for the customer or vendor. However, you can change the default information for individual transactions, if you have to.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Double-click the customer account or vendor account to set up a default sales tax profile for.

3.  On the **Invoice and delivery** FastTab, in the **Sales tax group** field, select the default sales tax group for the customer or vendor. The default sales tax group is selected automatically when transactions are created for the customer or vendor. However, you can change the sales tax group for individual transactions before the transactions are posted.

4.  In the **Tax exempt number** field, select the tax exempt number, if the customer or vendor has a tax exempt number.

5.  Select the **Prices include sales tax** check box if the prices on orders for the customer or vendor include sales tax.

## Example of prices that include sales tax

You create a sales order for 10 lamps. The unit price on the order line is 10.00. The sales tax is 25 percent.

## Case 1

For customer 1, the **Prices include sales tax** check box in the **Customers** form is selected. The sales tax is calculated as follows:

Gross price, which includes sales tax: 10 \* 10.00 = 100.00

Net price, which excludes sales tax: 100.00 / 1.25 = 80.00

## Case 2

For customer 2, the **Prices include sales tax** check box is cleared. The sales tax is calculated as follows:

Gross price, which includes sales tax: 100.00 \* 1.25 = 125.00

Net price, which excludes sales tax: 10 \* 10.00 = 100.00

## See also

[Customers (form)](https://technet.microsoft.com/library/aa590606\(v=ax.60\))

[Vendors (form)](https://technet.microsoft.com/library/aa592162\(v=ax.60\))

  


