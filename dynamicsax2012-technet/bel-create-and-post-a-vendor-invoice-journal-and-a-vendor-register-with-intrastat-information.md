---
title: (BEL) Create and post a vendor invoice journal and a vendor register with Intrastat information
TOCTitle: (BEL) Create and post a vendor invoice journal and a vendor register with Intrastat information
ms:assetid: 25d8b505-2c4e-4e55-a395-082b8cd98c33
ms:mtpsurl: https://technet.microsoft.com/library/Hh208484(v=AX.60)
ms:contentKeyID: 36056194
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Belgium
- vendor invoice
- Intrastat
- vendor register
audience: Application User
ms.search.region: Belgium
---

# (BEL) Create and post a vendor invoice journal and a vendor register with Intrastat information 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Intrastat declaration is a mandatory statement that reports the movement of goods between the European Union (EU) member states. Belgian companies can use the **Intrastat** form to generate an Intrastat declaration in CSV format for submittal to the Belgian customs authority. Before you can create and post a vendor invoice journal or vendor register and submit an Intrastat declaration, you must set up Value Added Tax (VAT) and Intrastat information for the vendor.

Before you generate an Intrastat declaration, complete the following:

  - Set up Intrastat parameters to generate Intrastat transaction details and compression details. For more information, see [About Intrastat](about-intrastat.md) and [Intrastat (form)](https://technet.microsoft.com/library/aa619055\(v=ax.60\)).

  - Create an item and specify the **Commodity**, **Additional units**, and **Net weight** fields for the Intrastat transaction. For more information, see [Commodity codes (form)](https://technet.microsoft.com/library/aa617816\(v=ax.60\)) and [Units (form)](https://technet.microsoft.com/library/hh209233\(v=ax.60\)).

<!-- end list -->

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice register**.

2.  Select a journal line to enter the required details. For more information, see [Post invoices in an invoice journal](post-invoices-in-an-invoice-journal.md) and [Journal voucher - Invoice journal (form)](https://technet.microsoft.com/library/aa616218\(v=ax.60\)).

3.  Click the **Invoice** tab.

4.  In the **Transaction code** field, select the transaction code for European Union (EU) trade, used for Intrastat reporting.

5.  In the **Transport** and **Port** fields, specify the means of transport and the port where the delivery is to be loaded.

6.  In the **Statistics procedure** field, select the code for the statistical procedure.

7.  In the **Commodity** field, select the item code for Intrastat reporting.

8.  In the **Additional units** field, enter the number of additional item units for the invoice.

9.  In the **Charges percentage** field, specify the charges for the journal.

10. In the **Country/region** and **State/province** fields, specify the country or region and the state for the delivery of goods.

11. Click **Validate** \> **Validate** to validate the invoice journal.

12. Click **Post** \> **Post** to post the invoice journal. After you post an invoice, you can reverse it. For more information on reversing a transaction, see [Reverse a transaction](reverse-a-transaction.md).

13. Close the forms to save the changes.

## See also

[(BEL) Approve or cancel vendor register invoices with Intrastat information](bel-approve-or-cancel-vendor-register-invoices-with-intrastat-information.md)

[(BEL) Transfer vendor invoice transactions and generate an Intrastat declaration](bel-transfer-vendor-invoice-transactions-and-generate-an-intrastat-declaration.md)

[Compression of Intrastat (form)](https://technet.microsoft.com/library/aa584795\(v=ax.60\))

  


