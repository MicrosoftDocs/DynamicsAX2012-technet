---
title: (BRA) About the NF-e process
TOCTitle: (BRA) About the NF-e process
ms:assetid: 2e491951-d107-4de2-b156-dbb35e096771
ms:mtpsurl: https://technet.microsoft.com/library/JJ898462(v=AX.60)
ms:contentKeyID: 50873681
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- electronic fiscal document process
- NF-e process
- BR - 00021
- BR - 00022
- BR - 00045
audience: Application User
ms.search.region: Brazil
---

# (BRA) About the NF-e process 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can generate a Nota Fiscal eletrônica (NF-e) to register the movement of items and services between two parties.

You can generate an NF-e from any of the following fiscal documents:

  - Sales orders

  - Purchase orders for non-taxpayer vendors

  - Project invoices

  - Tax fiscal documents

  - Free text invoices


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



You must perform the following tasks before you can generate an NF-e:

  - Set up web services, rejection codes, and schemas for a domain. For more information, see [(BRA) Set up NF-e federal parameters](bra-set-up-nf-e-federal-parameters.md).

  - Set up a certificate, environment, NF-e version, authority, template, schema validation, automatic printing of Documento Auxiliar da Nota fiscal eletrônica (DANFE) after NF-e approval, and a contingency mode for NF-e for each fiscal establishment. For more information, see [(BRA) Set up NF-e parameters for a fiscal establishment](bra-set-up-nf-e-parameters-for-a-fiscal-establishment.md) and [(BRA) Turn on or turn off contingency mode](bra-turn-on-or-turn-off-contingency-mode.md).

  - Set up web services that are related to a fiscal authority. For more information, see [(BRA) Set up NF-e federal parameters](bra-set-up-nf-e-federal-parameters.md).

  - Set up a fiscal document type for an NF-e. For more information, see [(BRA) Set up fiscal document types](bra-set-up-fiscal-document-types.md).

After you generate an NF-e, you can submit the digitally signed NF-e to the Secretaria da Fazenda (SEFAZ) in an XML message. The items can be delivered after the NF-e is electronically approved by SEFAZ. The NF-e process includes the following steps:

  - The fiscal establishment posts a fiscal document using a fiscal document type that is set up for fiscal document model 55 to generate an NF-e. For more information, see [(BRA) Post an NF-e from a sales order](bra-post-an-nf-e-from-a-sales-order.md), [(BRA) Post an NF-e from a purchase order](bra-post-an-nf-e-from-a-purchase-order.md), [(BRA) Post an NF-e from a free text invoice](bra-post-an-nf-e-from-a-free-text-invoice.md), [(BRA) Post an NF-e from a project invoice](bra-post-an-nf-e-from-a-project-invoice.md), and [(BRA) Post an NF-e from a tax fiscal document](bra-post-an-nf-e-from-a-tax-fiscal-document.md).

  - The NF-e export or import process detects the posted fiscal document for the fiscal document model 55 and generates an XML message in the specified format, which is transmitted to SEFAZ. A separate XML message is generated for each NF-e. For more information, see [(BRA) Set up the export or import process for NF-e](bra-set-up-the-export-or-import-process-for-nf-e.md).

  - SEFAZ processes the XML message and returns a protocol and status for each NF-e. The returned NF-e status and protocol are then assigned to the NF-e that is used in the NF-e export or import process. The returned status in the return protocol can be **Approved**, **Denied**, **Discarded**, **Canceled**, **Rejected non fixable**, or **Rejected**. This information is used to update the fiscal document status in Microsoft Dynamics AX.

After the status of the NF-e is received from SEFAZ, you can perform the following tasks:

  - If the NF-e is approved, you can print the DANFE. Alternatively, if you selected the **Print DANFE when NF-e is approved** check box on the **NF-e federal** FastTab in the **Fiscal establishments** form, the DANFE is printed automatically. For more information, see [(BRA) Turn on or turn off contingency mode](bra-turn-on-or-turn-off-contingency-mode.md), [(BRA) Print the DANFE in contingency mode](bra-print-the-danfe-in-contingency-mode.md), and [(BRA) Verify the NF-e status and print the DANFE](bra-verify-the-nf-e-status-and-print-the-danfe.md).
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: You can generate the DANFE for an approved NF-e as a PDF file. You can then send the DANFE PDF file and the NF-e XML file that are generated for an approved NF-e to a third-party customer or vendor via email. For more information, see <A href="bra-set-up-email-parameters-and-email-templates-for-an-nf-e.md">(BRA) Set up email parameters and email templates for an NF-e</A>, <A href="bra-generate-danfe-as-pdf-files.md">(BRA) Generate DANFE as PDF files</A>, and <A href="bra-generate-emails-for-approved-nf-e-and-attach-danfe-pdf-files-and-nf-e-xml-files-to-the-emails.md">(BRA) Generate emails for approved NF-e and attach DANFE PDF files and NF-e XML files to the emails</A>.</P>



  - If the NF-e is denied, then you must cancel the NF-e. For more information, see [(BRA) Cancel a customer NF-e](bra-cancel-a-customer-nf-e.md), [(BRA) Cancel a vendor NF-e](bra-cancel-a-vendor-nf-e.md), [(BRA) Cancel a project invoice NF-e](bra-cancel-a-project-invoice-nf-e.md), and [(BRA) Cancel an NF-e that is generated from a tax fiscal document](bra-cancel-an-nf-e-that-is-generated-from-a-tax-fiscal-document.md).

  - If the NF-e is rejected and can be fixed, you can correct the incorrect information, and then click **Resend** on the **NF-e federal** tab on the **Action Pane** in the **Fiscal document** form to resend the NF-e to SEFAZ.

  - If the NF-e is rejected and cannot be fixed, you must cancel the discarded NF-e with the discarded number. The NF-e export or import process detects the fiscal document that is posted and marked for discard and then generates an XML message in the specified format for the discarded NF-e number, which is transmitted to SEFAZ. The fiscal document status is set to **Discarded**.

## See also

[(BRA) About NF-e schemas and processes](bra-about-nf-e-schemas-and-processes.md)

[(BRA) NF-e federal parameters (form)](https://technet.microsoft.com/library/jj933509\(v=ax.60\))

[(BRA) Fiscal establishments (form)](https://technet.microsoft.com/library/jj933531\(v=ax.60\))

[(BRA) Fiscal document types (form)](https://technet.microsoft.com/library/jj710551\(v=ax.60\))

[(BRA) Contingency mode (form)](https://technet.microsoft.com/library/jj933511\(v=ax.60\))

[(BRA) Rejected fiscal documents with pending cancellation (list page)](https://technet.microsoft.com/library/jj937996\(v=ax.60\))

[(BRA) Fiscal documents pending an update to contingency mode (list page)](https://technet.microsoft.com/library/jj937991\(v=ax.60\))

  


