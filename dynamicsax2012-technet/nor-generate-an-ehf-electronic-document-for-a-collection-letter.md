---
title: (NOR) Generate an EHF electronic document for a collection letter
TOCTitle: (NOR) Generate an EHF electronic document for a collection letter
ms:assetid: 1c94ddef-2a1c-454f-9806-708c8fbd0b5e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn304969(v=AX.60)
ms:contentKeyID: 54899947
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustCollectionLetterNote
- NO - 00010
- MsDynAx060.Forms.CustCollectionLetterNote
audience: Application User
ms.search.region: Norway
---

# (NOR) Generate an EHF electronic document for a collection letter 


_**Applies To:** Microsoft Dynamics AX 2012_

Follow the steps in this topic to post collection letters and generate XML files. Microsoft Dynamics AX processes the XML files and creates Elektronisk HandelsFormat (EHF) files in the shared folder that you specified for the **EInvoiceFileTransform\_OIOUBL** batch job task for the batch job.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 4 for AX 2012.</P>



The following illustration shows how to generate an EHF electronic document for a collection letter. The numbers correspond to the procedures later in this topic.

![Generate an EHF electronic invoice](images/Dn304969.CU4-Norway-GenerateanEHFelectronicinvoice(AX.60).gif "Generate an EHF electronic invoice")

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
<td><p>Configure EHF electronic invoicing. For more information, see <a href="nor-configure-ehf-electronic-invoicing.md">(NOR) Configure EHF electronic invoicing</a>.</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>Create collection letter sequences. For more information, see <a href="set-up-a-collection-letter-sequence.md">Set up a collection letter sequence</a>.</p></td>
</tr>
<tr class="odd">
<td></td>
<td><p>Create collection letters for customers for whom you select the <strong>eInvoice</strong> check box in the <strong>Customers</strong> form. For more information, see <a href="create-collection-letters.md">Create collection letters</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Post a collection letter for a public sector organization

Use the **Print/post collection letters** form to post a collection letter and generate an XML file. Microsoft Dynamics AX processes the XML file and creates an EHF file. You can send the EHF file to the Norwegian public sector customer electronically.

To post a collection letter for a public sector organization, follow these steps:

1.  Click **Accounts receivable** \> **Periodic** \> **Collections** \> **Print/post collection letters**.

2.  Select a collection letter that you created for a customer for whom you selected the **eInvoice** check box in the **Customers** form.

3.  Click **Post** to open the **Post collection letter note** form.

4.  In the **Billing classification** field, select the billing classification to post the transactions for.
    

    > [!NOTE]
    > <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>



5.  Select the **Include transactions without a billing classification** check box to post the transactions that do not have a billing classification assigned to them.
    

    > [!NOTE]
    > <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>



6.  In the **Posting date** field, select the posting date for the collection letter.

7.  Click **OK** to post the collection letter and generate an XML file. Microsoft Dynamics AX processes the XML file and creates an EHF file.

8.  In the **Print/post collection letters** form, click **Send electronically** to send the EHF file to the customer electronically.
    

    > [!NOTE]
    > <P>The <STRONG>Send electronically</STRONG> button is available only if you select a collection letter that has a status of <STRONG>Posted</STRONG>.</P>



## Related tasks

[(NOR) EHF electronic documents](nor-ehf-electronic-documents.md)

  


