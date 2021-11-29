---
title: About integration ports for vendor invoices
TOCTitle: About integration ports for vendor invoices
ms:assetid: 45e4f53a-ccf3-4ddc-b739-66a53a7ab4e4
ms:mtpsurl: https://technet.microsoft.com/library/Hh242384(v=AX.60)
ms:contentKeyID: 36056898
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor invoice
- OASIS
- UBL
audience: Application User
ms.search.region: Global
---

# About integration ports for vendor invoices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If your organization receives many vendor invoices, you can set up the system to automatically receive vendor invoices in electronic format. You can use an Application Integration Framework (AIF) service to import vendor invoices from XML files that you receive from your vendor. The vendor invoices must use the schema that is required for the **VendVendInvoiceService** service. For more information, see [Document Schemas](document-schemas.md) and [Messages and transforms in AIF](messages-and-transforms-in-aif.md).

In Microsoft Dynamics AX, you can view the invoices in the **Vendor invoice** form and on related list pages. You can set up workflow processing to route the invoices for approval. If it is needed, the workflow can automatically perform invoice matching, and route only the invoices that exceed the allowable tolerances for approval.

An enhanced integration port is required for this feature. For information about how to configure the enhanced integration port, see [Managing integration ports](managing-integration-ports.md).

  


