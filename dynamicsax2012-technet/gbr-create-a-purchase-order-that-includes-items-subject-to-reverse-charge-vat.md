---
title: (GBR) Create a purchase order that includes items subject to reverse charge VAT
TOCTitle: (GBR) Create a purchase order that includes items subject to reverse charge VAT
ms:assetid: 03fba58d-470a-4867-ac06-7592cd45b0ea
ms:mtpsurl: https://technet.microsoft.com/library/Gg230657(v=AX.60)
ms:contentKeyID: 36055941
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: United Kingdom
---

# (GBR) Create a purchase order that includes items subject to reverse charge VAT 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Reverse charge VAT is required on sales and purchases of mobile telephones, computer chips, microprocessors, or CPUs for business purposes within the United Kingdom. Under reverse charge VAT rules, the buyer of the goods, instead of the seller, is liable to account for the VAT on the sale.

The seller does not charge VAT, but the items that are subject to reverse charge VAT and the total amount of reverse charge VAT are noted on the invoice. These items are also identified on VAT 100 reports as being subject to reverse charge VAT. You can use the **Reverse charge sales list** report to view information about reverse charge sales on a periodic basis. Depending on the setup, this information can be calculated automatically for vendor invoices.

Use the following procedures to create a purchase order that includes items subject to reverse charge VAT.

## Create a purchase order

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, click **Purchase order**.

3.  In the **Vendor account** field, select a vendor account, and then click **OK**.

4.  On the **Purchase order lines** FastTab, enter line items.

5.  Click the **Purchase** tab, and then click **Sales tax**.

6.  In the **Sales tax transactions** form, you can view the sales tax amounts for each sales tax code. If necessary, you can adjust the sales tax amount for the sales tax code that represents reverse charge VAT.

7.  Close the form.

8.  Press CTRL+S to save the purchase order. If reverse charge VAT applies, it is automatically calculated.

9.  Click **Confirm** to confirm the purchase order.

10. Close the form.

## Enter an invoice

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click a purchase order, and then select a purchase order line.

3.  Click the **Invoice** tab, and then click **Invoice**.

4.  Click the **Financials** tab, and then click **Sales tax**.

5.  In the **Sales tax transactions** form, you can view the sales tax amounts for each sales tax code. If necessary, adjust the sales tax amount for the sales tax code that represents reverse charge VAT to match the amount shown on the invoice that you received from your vendor.

6.  Close the form.

7.  In the **Vendor invoice** form, verify that the other invoice information is correct, and then click **Post** to post the invoice.

8.  Close the form.

## See also

[(GBR) Set up reverse charge VAT](gbr-set-up-reverse-charge-vat.md)

[(GBR) Print - UK report (RCSalesList\_UK)](gbr-print-uk-report-rcsaleslist-uk.md)

[Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\))

[Purchase order (form)](https://technet.microsoft.com/library/aa557983\(v=ax.60\))

  


