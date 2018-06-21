---
title: (BRA) Post an NF-e from a project invoice
TOCTitle: (BRA) Post an NF-e from a project invoice
ms:assetid: 21d77e19-7018-4411-a904-607a2605bd44
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ933501(v=AX.60)
ms:contentKeyID: 50935114
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- Post electronic fiscal document
- Post NF-e
---

# (BRA) Post an NF-e from a project invoice [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post a project invoice to generate a nota fiscal eletrônica (NF-e). When you post a project invoice, an NF-e XML file is generated and submitted to the Secretaria da Fazenda (SEFAZ).

Before you can generate the NF-e, you must assign a fiscal document type for the NF-e to the fiscal establishment that is related to the primary address of the legal entity. For more information, see [(BRA) Assign fiscal document types for customers or vendors](bra-assign-fiscal-document-types-for-customers-or-vendors.md).

After the status of the NF-e is received from SEFAZ, you can perform the following tasks:

  - If the NF-e is approved, you can print the Documento Auxiliar da Nota Fiscal Eletrônica (DANFE), or the DANFE is printed automatically if you select the **Print DANFE when NF-e is approved** check box on the **NF-e federal** FastTab in the **Fiscal establishments** form. For more information, see [(BRA) Set up NF-e parameters for a fiscal establishment](bra-set-up-nf-e-parameters-for-a-fiscal-establishment.md).

  - If the NF-e is denied, then you must cancel the NF-e. For more information, see [(BRA) Cancel a project invoice NF-e](bra-cancel-a-project-invoice-nf-e.md).

  - If the NF-e is rejected and can be fixed, you can correct the incorrect information, and then you can click **Resend** on the **NF-e federal** tab on the **Action Pane** in the **Fiscal document** form to resend the NF-e to SEFAZ.

  - If the NF-e is rejected and not fixable, you must cancel the NF-e.

<!-- end list -->

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a project, and then on the **Action Pane**, on the **Project** tab, in the **Maintain** group, click **Edit**. Alternatively, in the **All projects** list, double-click a project line.

2.  Click the **Manage** tab, and then click **Invoice proposals**. For more information, see [Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\)).

3.  Click **Invoice proposal**.

4.  In the **Project contract** field, select the project contract to create an invoice proposal for.

5.  In the **Project** field, select a project that is associated with the selected contract. If you do not select a project, all transactions for the selected project contract are displayed in the search results.

6.  In the **Invoice date** field, select the date on which to post the invoice.

7.  Click **Search** to search for project transactions.

8.  Click **Select all** to select all transactions.

9.  Click **OK** to post the invoice.

## See also

[(BRA) Cancel a vendor NF-e](bra-cancel-a-vendor-nf-e.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

