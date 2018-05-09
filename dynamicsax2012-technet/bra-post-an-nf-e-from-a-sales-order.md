---
title: (BRA) Post an NF-e from a sales order
TOCTitle: (BRA) Post an NF-e from a sales order
ms:assetid: ec08de0b-5b9d-4f9a-bbfb-692a98b29248
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ933536(v=AX.60)
ms:contentKeyID: 50935150
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- Post electronic fiscal document
- Post NF-e
---

# (BRA) Post an NF-e from a sales order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post a sales order to generate a Nota Fiscal eletrônica (NF-e). When you post the sales order, an NF-e XML file is generated and submitted to the Secretaria da Fazenda (SEFAZ).

After the status of the NF-e is received from SEFAZ, you can perform the following tasks:

  - If the NF-e is approved, you can print the Documento Auxiliar da Nota Fiscal Eletrônica (DANFE). Alternatively, if you selected the **Print DANFE when NF-e is approved** check box on the **NF-e federal** FastTab in the **Fiscal establishments** form, the DANFE is printed automatically. For more information, see [(BRA) Verify the NF-e status and print the DANFE](bra-verify-the-nf-e-status-and-print-the-danfe.md) and [(BRA) Set up NF-e parameters for a fiscal establishment](bra-set-up-nf-e-parameters-for-a-fiscal-establishment.md).

  - If the NF-e is denied, you must cancel the NF-e. For more information, see [(BRA) Cancel a customer NF-e](bra-cancel-a-customer-nf-e.md).

  - If the NF-e is rejected and can be fixed, you can correct the incorrect information. You can then click **Resend** on the **NF-e federal** tab on the **Action Pane** in the **Fiscal document** form to resend the NF-e to SEFAZ.

  - If the NF-e is rejected and cannot be fixed, you must cancel the NF-e.

Use the following procedure to post an NF-e from a sales order.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create a sales order. For more information, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md).

3.  Click **Line view**.

4.  On the **Line details** FastTab, on the **Fiscal information** tab, in the **Fiscal document type** field, select the type of fiscal document for the NF-e.
    

    > [!NOTE]
    > <P>You can select only the fiscal document types that are defined for the fiscal establishment of the site for the selected sales order line.</P>



5.  In the **CFOP** field, select the Código Fiscal de Operações e Prestações (CFOP) code.
    

    > [!NOTE]
    > <P>You can select only the CFOP codes that are based on the fiscal establishment of the site for the selected sales order line. You can also leave the <STRONG>CFOP</STRONG> field blank, because a CFOP code is not mandatory for the electronic fiscal document for services.</P>



6.  On the **Setup** tab, in the **Sales tax group** and **Item sales tax group** fields, select the sales tax group and item sales tax group for the selected order line.

7.  On the **Action Pane**, on the **Invoice** tab, click **Invoice** to open the **Posting invoice** form.

8.  Select the **Posting** and **Print invoice** check boxes to post the sales order and print the fiscal document.

9.  Click **OK** to post the sales order. When you post the sales order, an NF-e XML message is generated and submitted to SEFAZ.

## See also

[(BRA) Set up NF-e federal parameters](bra-set-up-nf-e-federal-parameters.md)

[(BRA) Set up print management for NF-e](bra-set-up-print-management-for-nf-e.md)

[(BRA) Set up email addresses for customers](bra-set-up-email-addresses-for-customers.md)

[(BRA) Set up email parameters and email templates for an NF-e](bra-set-up-email-parameters-and-email-templates-for-an-nf-e.md)

[(BRA) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj911252\(v=ax.60\))

[(BRA) Print the DANFE in contingency mode](bra-print-the-danfe-in-contingency-mode.md)

[(BRA) About NF-e schemas and processes](bra-about-nf-e-schemas-and-processes.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

