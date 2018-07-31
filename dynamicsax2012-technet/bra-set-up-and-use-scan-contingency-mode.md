---
title: (BRA) Set up and use SCAN contingency mode
TOCTitle: (BRA) Set up and use SCAN contingency mode
ms:assetid: 9600a1b3-c72a-4576-a246-45a65c360c16
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn269133(v=AX.60)
ms:contentKeyID: 54920085
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.FiscalDocumentType_BR
- Forms.EFDocParameters_BR
- Forms.EFDocContingencyMode_BR
- BR-00046
- Forms.EFDocServiceInquire_BR
- MsDynAx060.Forms.EFDocParameters_BR
- MsDynAx060.Forms.EFDocContingencyMode_BR
- MsDynAx060.Forms.FiscalDocumentType_BR
- MsDynAx060.Forms.EFDocServiceInquire_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up and use SCAN contingency mode 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Follow the steps in this topic to set up and use the Sistema de Contingência do Ambiente Nacional (SCAN) contingency mode. You can use the SCAN contingency mode to generate, export, and import the status of a Nota Fiscal eletrônica (NF-e) when the origin Secretaria da Fazenda (SEFAZ) environment is not available.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><p>Set up the NF-e parameters for a fiscal establishment. For more information, see <a href="bra-set-up-nf-e-parameters-for-a-fiscal-establishment.md">(BRA) Set up NF-e parameters for a fiscal establishment</a>.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Set up the export or import process for an NF-e. For more information, see <a href="bra-set-up-the-export-or-import-process-for-nf-e.md">(BRA) Set up the export or import process for NF-e</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Set up a fiscal document type for the SCAN contingency mode

Use this procedure to set up a fiscal document type with a series and a fiscal document number sequence for the SCAN contingency mode.

To set up a fiscal document type for the SCAN contingency mode, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Fiscal document types**.

2.  Select or create a fiscal document type. For more information, see [(BRA) Set up fiscal document types](bra-set-up-fiscal-document-types.md).

3.  On the **General** FastTab, select the **NF-e federal** check box to indicate that the fiscal document type is created for an NF-e.

4.  In the **Series for SCAN mode** field, enter the SCAN series to use for electronic fiscal documents when you turn on the SCAN contingency mode.

5.  In the **Fiscal document number sequence to SCAN mode** field, select the number sequence to use for electronic fiscal documents when you turn on the SCAN contingency mode.

## 2\. Set up the NF-e federal parameters for the SCAN contingency mode

Use the **NF-e federal parameters** form to set up an authority for the SCAN contingency mode.

To set up the NF-e federal parameters for the SCAN contingency mode, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **NF-e federal parameters**.

2.  Select or create an authority for the SCAN contingency mode. For more information, see the “Set up web services for an NF-e” section in the [(BRA) Set up NF-e federal parameters](bra-set-up-nf-e-federal-parameters.md) topic.

3.  In the **Authority type** field, select **SCAN** to indicate that the authority is a SCAN authority.
    

    > [!NOTE]
    > <P>You can set up only one authority for the SCAN contingency mode.</P>



## 3\. Turn on the SCAN contingency mode

Use the **Contingency mode** form to turn on the SCAN contingency mode for a fiscal establishment when the origin SEFAZ is not available.

To turn on SCAN contingency mode, follow these steps:

1.  Click **Accounts receivable** \> **Periodic** \> **NF-e Federal** \> **Contingency**.

2.  Select the fiscal establishment to turn on the SCAN contingency mode for, and then click **On** to open the **Active contingency** form.

3.  In the **Contingency mode** field, select **SCAN**.

4.  In the **Contingency reason** field, enter the reason to turn on the SCAN contingency mode. The reason for the SCAN contingency mode must contain a minimum of 15 characters.

5.  Click **OK** to turn on the SCAN contingency mode. A transaction is recorded in the **Contingency mode** form.

## 4\. Turn off the SCAN contingency mode

Use the **Contingency mode** form to turn off the SCAN contingency mode for a fiscal establishment when the origin SEFAZ is available.

To turn off the SCAN contingency mode, follow these steps:

1.  Click **Accounts receivable** \> **Periodic** \> **NF-e Federal** \> **Contingency**.

2.  Select the fiscal establishment to turn off the SCAN contingency mode for, and then click **Off**.

## 5\. Verify the NF-e web service status

Use the **NF-e web services status** form to verify the status of the NF-e web services.

To verify the NF-e web service status, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **NF-e web services status**.

2.  Click **Service inquiry** to verify the status of the NF-e web services.

3.  Verify the status of the web services.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>State</strong></p></td>
    <td><p>The identification code for the state.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Authority</strong></p></td>
    <td><p>The authority that receives, approves, or denies electronic fiscal document requests.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Environment</strong></p></td>
    <td><p>The type of environment for the web service. It can be <strong>Testing</strong> or <strong>Production</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Status code</strong></p></td>
    <td><p>The return code for the NF-e web service, based on the returned SEFAZ code.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Status reason</strong></p></td>
    <td><p>The reason for the status of the NF-e web service.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Average response time</strong></p></td>
    <td><p>The average response time, in seconds, for NF-e web services in the last five minutes.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Planned return</strong></p></td>
    <td><p>The planned date and time for the return of the NF-e web service.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Notes</strong></p></td>
    <td><p>The notes from the authority about the NF-e services or the status requests for NF-e services.</p></td>
    </tr>
    </tbody>
    </table>


## Related tasks

[(BRA) SCAN contingency mode](bra-scan-contingency-mode.md)

[(BRA) About the NF-e process](bra-about-the-nf-e-process.md)

[(BRA) About NF-e schemas and processes](bra-about-nf-e-schemas-and-processes.md)

[(BRA) Post an NF-e from a free text invoice](bra-post-an-nf-e-from-a-free-text-invoice.md)

[(BRA) Post an NF-e from a project invoice](bra-post-an-nf-e-from-a-project-invoice.md)

[(BRA) Post an NF-e from a purchase order](bra-post-an-nf-e-from-a-purchase-order.md)

[(BRA) Post an NF-e from a sales order](bra-post-an-nf-e-from-a-sales-order.md)

[(BRA) Post an NF-e from a tax fiscal document](bra-post-an-nf-e-from-a-tax-fiscal-document.md)

[(BRA) Verify the NF-e status and print the DANFE](bra-verify-the-nf-e-status-and-print-the-danfe.md)

  


