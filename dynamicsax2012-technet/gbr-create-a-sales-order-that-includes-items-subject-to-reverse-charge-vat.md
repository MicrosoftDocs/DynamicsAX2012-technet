---
title: (GBR) Create a sales order that includes items subject to reverse charge VAT
TOCTitle: (GBR) Create a sales order that includes items subject to reverse charge VAT
ms:assetid: 7d8af727-698f-4155-970f-5dab2bae9941
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213142(v=AX.60)
ms:contentKeyID: 36058309
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: United Kingdom
---

# (GBR) Create a sales order that includes items subject to reverse charge VAT 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Reverse charge VAT is required on sales and purchases of mobile telephones, computer chips, microprocessors, or CPUs for business purposes within the United Kingdom. Under reverse charge VAT rules, the buyer of the goods, instead of the seller, is liable to account for the VAT on the sale.

The seller does not charge VAT, but the items that are subject to reverse charge VAT and the total amount of reverse charge VAT are noted on the invoice. These items are also identified on VAT 100 reports as being subject to reverse charge VAT. You can use the **Reverse charge sales list** report to view information about reverse charge sales periodically. Depending on the setup, this information can be calculated automatically for sales orders.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click a customer account.

3.  In the **Customers** form, on the **Invoice and delivery** FastTab, verify that the customer's VAT number is displayed in the **Tax exempt number** field. If necessary, add it. For more information, see [Assign a tax exempt number to a customer](assign-a-tax-exempt-number-to-a-customer.md).

4.  Close the form.

5.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

6.  In the **Sales order** form, enter the line items for the order.

7.  Press CTRL+S to save the order. If applicable, the reverse charge VAT is calculated. When the invoice is printed, the total amount of the reverse charge is shown on the invoice.

8.  Close the form.

## See also

[(GBR) Set up reverse charge VAT](gbr-set-up-reverse-charge-vat.md)

[(GBR) Print - UK report (RCSalesList\_UK)](gbr-print-uk-report-rcsaleslist-uk.md)

  


