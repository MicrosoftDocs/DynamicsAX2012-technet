---
title: (BRA) Post an NF-e from a free text invoice
TOCTitle: (BRA) Post an NF-e from a free text invoice
ms:assetid: 37f3d890-d463-4702-84af-965196bc9832
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ915359(v=AX.60)
ms:contentKeyID: 50874340
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- Post electronic fiscal document
- Post NF-e
audience: Application User
ms.search.region: Brazil
---

# (BRA) Post an NF-e from a free text invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create and post a free text invoice to generate a nota fiscal eletrônica (NF-e). When you post the free text invoice, an NF-e XML file is generated and submitted to the Secretaria da Fazenda (SEFAZ).

After the status of the NF-e is received from SEFAZ, you can perform the following tasks:

  - If the NF-e is approved, you can print the Documento Auxiliar da Nota Fiscal Eletrônica (DANFE). Alternatively, if you selected the **Print DANFE when NF-e is approved** check box on the **NF-e federal** FastTab in the **Fiscal establishments** form, the DANFE is printed automatically. For more information, see [(BRA) Set up NF-e parameters for a fiscal establishment](bra-set-up-nf-e-parameters-for-a-fiscal-establishment.md).

  - If the NF-e is denied, you must cancel the NF-e. For more information, see [(BRA) Cancel a customer NF-e](bra-cancel-a-customer-nf-e.md).

  - If the NF-e is rejected and can be fixed, you can correct the incorrect information. You can then click **Resend** on the **NF-e federal** tab on the **Action Pane** in the **Fiscal document** form to resend the NF-e to SEFAZ.

  - If the NF-e is rejected and cannot be fixed, you must cancel the NF-e.

Use the following procedure to post an NF-e from a free text invoice.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Create a free text invoice. For more information, see [(BRA) Create and post a free text invoice](bra-create-and-post-a-free-text-invoice.md).

3.  Click **Header view**, and then, on the **Fiscal information** FastTab, in the **Fiscal document type** field, select the fiscal document type for the NF-e.
    

    > [!NOTE]
    > <P>You can select only the fiscal document types that are defined for the fiscal establishment that you selected for the free text invoice.</P>



4.  On the **Action Pane**, on the **Invoice** tab, click **Post** to open the **Post free text invoice** form.

5.  On the **Bill of lading** tab, in the **Volume type** and **Volume quantity** fields, enter the volume type and volume quantity for the invoice posting.
    

    > [!NOTE]
    > <P>The <STRONG>Bill of lading</STRONG> tab is available only if the <STRONG>Service invoice</STRONG> check box is cleared on the <STRONG>Fiscal information invoice line</STRONG> tab on the <STRONG>Line details</STRONG> FastTab in the <STRONG>Free text invoice</STRONG> form.</P>



6.  Click **OK** to post the free text invoice. When you post the free text invoice, an NF-e XML is generated and submitted to SEFAZ. For more information, see [(BRA) Set up the export or import process for NF-e](bra-set-up-the-export-or-import-process-for-nf-e.md).

## See also

[(BRA) Set up NF-e federal parameters](bra-set-up-nf-e-federal-parameters.md)

[(BRA) Set up print management for NF-e](bra-set-up-print-management-for-nf-e.md)

[(BRA) Set up email addresses for customers](bra-set-up-email-addresses-for-customers.md)

[(BRA) Set up email parameters and email templates for an NF-e](bra-set-up-email-parameters-and-email-templates-for-an-nf-e.md)

[(BRA) Free text invoice (modified form)](https://technet.microsoft.com/en-us/library/jj933514\(v=ax.60\))

[(BRA) Fiscal document types (form)](https://technet.microsoft.com/en-us/library/jj710551\(v=ax.60\))

  


