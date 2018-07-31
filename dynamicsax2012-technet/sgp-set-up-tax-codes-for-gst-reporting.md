---
title: (SGP) Set up tax codes for GST reporting
TOCTitle: (SGP) Set up tax codes for GST reporting
ms:assetid: b97e7c7c-e95b-4261-96c7-494241ceb4e3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213586(v=AX.60)
ms:contentKeyID: 36059118
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Singapore
---

# (SGP) Set up tax codes for GST reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Sales tax codes** form to set up tax codes for items that are taxed using the standard goods and services tax percentage. You can also use this form to set up tax codes for exempt items that are not subject to tax and items that have special trade-zone status for which the tax rate is 0 percent. For more information, see [Create various kinds of sales tax codes](create-various-kinds-of-sales-tax-codes.md).

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Press CTRL+N to create a new tax code.

3.  In the **Sales tax code** field, enter a code, such as GST, and then enter other information about the sales tax code.

4.  Click the **Calculation** FastTab.

5.  In the **VAT type** field, select the type of tax to calculate, based on the type of item to which the tax is applied.

6.  Click **Values** to open the **Values** form. Enter the dates for which the tax code is in effect.

7.  In the **Value** field, enter one of the following values:
    
      - For standard items, enter the current tax percentage. For example, if the tax percentage is 5 percent, enter 5.00.
    
      - For exempt items, do not enter a value.
    
      - For zero-rated items, enter 0.00.

8.  Repeat steps 2 through 7 to set up additional tax codes.

9.  Close the form to save your changes.

## See also

[(SGP) Set up tax groups for GST reporting](sgp-set-up-tax-groups-for-gst-reporting.md)

[(SGP) Calculate a sales tax payment and print the GST F5 report](sgp-calculate-a-sales-tax-payment-and-print-the-gst-f5-report.md)

  


