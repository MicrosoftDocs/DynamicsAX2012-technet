---
title: (BRA) Post an NF-e from a purchase order
TOCTitle: (BRA) Post an NF-e from a purchase order
ms:assetid: 34f72f34-e676-4afc-a63f-81dc8f9e717e
ms:mtpsurl: https://technet.microsoft.com/library/JJ933507(v=AX.60)
ms:contentKeyID: 50935120
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- Post NF-e
- post electronic fiscal document
audience: Application User
ms.search.region: Brazil
---

# (BRA) Post an NF-e from a purchase order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post a purchase order for a non-taxpayer vendor to generate a Nota Fiscal eletrônica (NF-e). When you post the purchase order, an NF-e XML file is generated and submitted to the Secretaria da Fazenda (SEFAZ).

Before you can generate an NF-e from a purchase order, you must perform the following tasks:

1.  Select the **Generate incoming fiscal document** check box on the **Fiscal information** FastTab in the **Vendors** form.

2.  Assign a fiscal document type for the NF-e to the non-taxpayer vendor. For more information, see [(BRA) Assign fiscal document types for customers or vendors](bra-assign-fiscal-document-types-for-customers-or-vendors.md).

After the status of the NF-e is received from SEFAZ, you can perform the following tasks:

  - If the NF-e is approved, you can print the Documento Auxiliar da Nota Fiscal Eletrônica (DANFE). Alternatively, if you selected the **Print DANFE when NF-e is approved** check box on the **NF-e federal** FastTab in the **Fiscal establishments** form, the DANFE is printed automatically. For more information, see [(BRA) Verify the NF-e status and print the DANFE](bra-verify-the-nf-e-status-and-print-the-danfe.md) and [(BRA) Set up NF-e parameters for a fiscal establishment](bra-set-up-nf-e-parameters-for-a-fiscal-establishment.md).

  - If the NF-e is denied, you must cancel the NF-e. For more information, see [(BRA) Cancel a vendor NF-e](bra-cancel-a-vendor-nf-e.md).

  - If the NF-e is rejected and can be fixed, you can correct the incorrect information. You can then click **Resend** on the **NF-e federal** tab on the **Action Pane** in the **Fiscal document** form to resend the NF-e to SEFAZ.

  - If the NF-e is rejected and cannot be fixed, you must cancel the NF-e.

Use the following procedure to post an NF-e from a purchase order for a non-taxpayer vendor.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Create a purchase order. For more information, see [(BRA) Create and post a vendor invoice for a nontaxpayer vendor](bra-create-and-post-a-vendor-invoice-for-a-nontaxpayer-vendor.md) and [(BRA) Create and post a return purchase order](bra-create-and-post-a-return-purchase-order.md).

3.  On the **Action Pane**, click **Invoice** \> **Invoice**.

4.  On the **Action Pane**, click **Post** \> **Post** to post the purchase order. When you post the purchase order, an NF-e XML message is generated and submitted to SEFAZ.

## See also

[(BRA) Set up NF-e federal parameters](bra-set-up-nf-e-federal-parameters.md)

[(BRA) Set up print management for NF-e](bra-set-up-print-management-for-nf-e.md)

[(BRA) Set up email addresses for vendors](bra-set-up-email-addresses-for-vendors.md)

[(BRA) Set up email parameters and email templates for an NF-e](bra-set-up-email-parameters-and-email-templates-for-an-nf-e.md)

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/library/jj911277\(v=ax.60\))

[(BRA) Vendor invoice (modified form)](https://technet.microsoft.com/library/jj898464\(v=ax.60\))

  


