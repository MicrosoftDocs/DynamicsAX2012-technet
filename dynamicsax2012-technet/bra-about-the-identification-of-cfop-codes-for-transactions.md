---
title: (BRA) About the identification of CFOP codes for transactions
TOCTitle: (BRA) About the identification of CFOP codes for transactions
ms:assetid: da494277-889f-474a-9269-5912f7f1e2a5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ937994(v=AX.60)
ms:contentKeyID: 50950782
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- CFOP
- CFOP codes for transactions
- identification of CFOP codes
- identify CFOP
- BR - 00033
audience: Application User
ms.search.region: Brazil
---

# (BRA) About the identification of CFOP codes for transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Código Fiscal de Operações e Prestações (CFOP) codes are specified by the Brazilian government. They are used to classify types of transactions. CFOP codes are identified based on the following parameters:

  - The order type

  - The operation type

  - The direction

  - The location

  - The delivery address on the order

  - The location of the customer or vendor

  - The address of the fiscal establishment that is associated with the fiscal document, or the address of the site of the fiscal establishment that is associated with the fiscal document

You can create CFOP codes and define the default CFOP code for a transaction and an operation type. For more information, see [(BRA) Set up the CFOP codes](bra-set-up-the-cfop-codes.md) and [(BRA) Set up the CFOP matrix](bra-set-up-the-cfop-matrix.md).

## Identification of CFOP for a purchase order

The identification of the CFOP codes for **Journal**, **Purchase order**, and **Returned order** order types is based on the location of the site of the fiscal establishment, and the operation type, order type, direction, location of the vendor, and delivery address of the purchase order line. The direction for the **Journal** order type and the **Purchase order** order type is **Incoming**, and for the **Returned order** order type, it is **Outgoing**.

## Identification of CFOP for a purchase requisition and request for quotation replies

The identification of the CFOP codes for a purchase requisition and a request for quotation reply is based on the order type, operation type, direction, delivery address of the fiscal establishment, and location of the vendor. The direction for a purchase requisition and a request for quotation is **Incoming**.

## Identification of CFOP for a vendor invoice

The identification of CFOP codes for vendor invoice lines of **Journal**, **Purchase order**, and **Returned order** purchase order types is based on the operation type of the vendor invoice, order type, and direction. It is also based on the delivery address of the vendor invoice line, the remittance address of the vendor invoice line and the address of the fiscal establishment. The direction for **Journal** and **Purchase order** order types is **Incoming**, and for the **Returned order** order type, it is **Outgoing**.

For a new vendor invoice line for which purchase order information is not available, the CFOP code identification depends on the operation type of the vendor invoice, the order type, the location of the delivery address of the vendor invoice line, and the remittance address of the vendor invoice line. The delivery address for a vendor invoice line is updated with the address of the fiscal establishment of the site. The remittance address for the vendor invoice line is updated with the address of the vendor that is set up by using **Remit to** as the purpose in the **Vendors** form, or the vendor primary address when the remittance address is not set up for the vendor.

## Identification of CFOP for a sales order and a sales quotation

For **Journal**, **Subscription**, **Sales order**, **Returned order**, and **Sales quotation** sales order types, the identification of the CFOP codes for the sales order line is based on the location of the site of the fiscal establishment, and the operation type, order type, direction, location, and delivery address of the customer.

The direction for **Journal**, **Subscription**, **Sales order**, and **Sales quotation** order types is **Outgoing**, and for the **Returned order** order type, it is **Incoming**.

## Identification of CFOP for a free text invoice

The identification of CFOP codes for a free text invoice is based on the operation type, direction, and location of the fiscal establishment, and the delivery address of the customer. The direction for a free text invoice is **Outgoing**.

## Identification of CFOP for a tax fiscal document

The identification of CFOP codes for a tax fiscal document is based on the direction, the location of the fiscal establishment, and the address of the tax fiscal document. The direction for the tax fiscal document is based on the value in the **Direction** field on the **General** FastTab in the **Tax fiscal document** form.

## See also

[(BRA) About fiscal establishments](bra-about-fiscal-establishments.md)

[(BRA) Create a fiscal establishment](bra-create-a-fiscal-establishment.md)

[(BRA) Fiscal establishments (form)](https://technet.microsoft.com/en-us/library/jj933531\(v=ax.60\))

[(BRA) CFOP codes (form)](https://technet.microsoft.com/en-us/library/jj933522\(v=ax.60\))

[(BRA) CFOP matrix (form)](https://technet.microsoft.com/en-us/library/jj933496\(v=ax.60\))

[(BRA) Set up a tax matrix](bra-set-up-a-tax-matrix.md)

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/en-us/library/jj911277\(v=ax.60\))

[(BRA) Purchase requisitions - lines (modified form)](https://technet.microsoft.com/en-us/library/jj923406\(v=ax.60\))

[(BRA) Request for quotation reply (modified form)](https://technet.microsoft.com/en-us/library/jj730981\(v=ax.60\))

[(BRA) Vendor invoice (modified form)](https://technet.microsoft.com/en-us/library/jj898464\(v=ax.60\))

[(BRA) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj911252\(v=ax.60\))

[(BRA) Sales quotation (modified form)](https://technet.microsoft.com/en-us/library/jj923173\(v=ax.60\))

[(BRA) Free text invoice (modified form)](https://technet.microsoft.com/en-us/library/jj933514\(v=ax.60\))

[(BRA) Tax fiscal document (form)](https://technet.microsoft.com/en-us/library/jj710428\(v=ax.60\))

  


