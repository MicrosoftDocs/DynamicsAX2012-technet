---
title: About ATP calculations
TOCTitle: About ATP calculations
ms:assetid: 55503035-663c-47e2-96d5-4f10037d1c67
ms:mtpsurl: https://technet.microsoft.com/library/Gg212804(v=AX.60)
ms:contentKeyID: 36931872
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- calculation
- calculations
- ATP
- available to promise
- available-to-promise
audience: Application User
ms.search.region: Global
---

# About ATP calculations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX calculates the available-to-promise (ATP) quantity based on the “cumulative ATP with look-ahead” method. The main advantage to this ATP calculation is that it can handle instances when the sum of issues between receipts is bigger than the latest receipt, for example, when it is necessary to use a quantity from an earlier receipt to meet a requirement. By including all of the issues until the cumulative quantity to receive is bigger than the cumulative quantity to issue, Microsoft Dynamics AX uses the ATP calculation method to evaluate if some of the quantity from an earlier period could be used in a later period.

The ATP quantity is the uncommitted inventory balance in the first period. It is normally calculated for each period in which a receipt is scheduled. The program calculates the ATP period in days, and calculates the current date as the first date for the ATP quantity. In the first period, ATP includes on-hand inventory less customer orders that are due and overdue.

Microsoft Dynamics AX calculates the ATP using the following formula:

ATP = ATP for the previous period + the receipts for the current period— the issues for the current period— the net issue quantity for each future period until the period when the sum of receipts for all future periods—up to and including the future period—is greater than the sum of issues, up to and including the future period.

When there are no more issues or receipts to consider, the ATP quantity for the following dates is the same as the latest calculated ATP quantity.

If all of the dimensions used for an item are not given when the ATP check is done, they might still be specified on the issue and receipts. In this case, in the ATP calculation, the receipts and issues must be aggregated to the existing dimensions, to reduce the number of receipt and issue lines used in the ATP calculation.

The ATP quantity shown is always \> = 0. If the calculation returns a negative ATP quantity, for example, if a larger quantity than the available quantity has been promised earlier, the program automatically sets the quantity to 0.

## Example

The settings **ATP backward demand time fence** and **ATP backward supply time fence** control how far backward in time to look for delayed demand orders or inventory issues and delayed supply orders or inventory receipts. If orders that are 7 days delayed should be considered in the ATP calculation, these fields should be set to 7. The settings **ATP delayed demand offset time** and **ATP delayed supply offset time** control when the delayed demand or supply will be considered in the ATP calculation. If the delayed supply and demand should be considered for the ATP calculation the day after tomorrow, the fields should be set to 2. This means that the quantity of an item on a delayed purchase order that should be considered in the ATP calculation will be seen as available 2 days after today’s date.

For the following example, **7** is entered in the **ATP backward demand time fence** and the **ATP backward supply time fence** fields, and **1** is entered in the **ATP delayed demand offset time** and the **ATP delayed supply offset time** fields.

Suppose that a purchase order for 200 pieces of a product that should have been received three days earlier has not been received yet. Because of this, a sales order line for 75 pieces of the same product that should have been shipped yesterday has not been shipped.

A customer calls and wants to order 150 pieces of the same product. When you verify the availability of the product, you find that there is another purchase order for 100 pieces of the product that will be delivered 10 days later.

1.  Susan creates a sales order line for the product and enters 150 for the quantity.

2.  Delivery date control is ATP. Therefore, the ATP data is calculated to find the earliest possible ship date. Based on the settings, the delayed purchase order and sales order are considered. This results in the ATP quantity for today is 0. Tomorrow, when the delayed purchase order is expected to be received, the ATP quantity is calculated to be larger than 0, in this case it is calculated to be 125. However, 10 days from now, the ATP quantity becomes larger than 150 when the additional purchase order for 100 pieces is expected to be received. The ship date is set to 10 days from now based on the ATP calculation.

3.  Susan tells the customer that the requested quantity can be delivered 10 days from now.

## See also

[ATP information (form)](https://technet.microsoft.com/library/hh209482\(v=ax.60\))

  


