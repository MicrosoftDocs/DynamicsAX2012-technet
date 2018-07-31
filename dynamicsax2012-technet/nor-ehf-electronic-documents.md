---
title: (NOR) EHF electronic documents
TOCTitle: (NOR) EHF electronic documents
ms:assetid: d2d2e150-509f-4769-b78a-42847d83edcc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn304984(v=AX.60)
ms:contentKeyID: 54899960
ms.date: 02/25/2014
mtps_version: v=AX.60
f1_keywords:
- NO - 00010
audience: Application User
ms.search.region: Norway
---

# (NOR) EHF electronic documents 


_**Applies To:** Microsoft Dynamics AX 2012_

You can send customer invoices, free text invoices, or collection letters to Norwegian public sector organizations as electronic documents in the Elektronisk HandelsFormat (EHF) format. In Microsoft Dynamics AX, the Application Integration Framework (AIF) is used to generate the electronic documents as XML files, which are then converted to EHF files.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 4 for AX 2012.</P>



## What is an EHF electronic document?

An EHF electronic document is an electronic document that was generated as an XML file, and then converted to EHF format by Microsoft Dynamics AX. The EHF format is based on Universal Business Language (UBL) 2.0 and is used to generate and send electronic documents to Norwegian public sector customers.

## What documents can I send as EHF electronic documents?

You can send the following documents as EHF electronic documents:

  - Customer invoices

  - Customer credit notes

  - Free text invoices

  - Project invoices

  - Project credit notes

  - Collection letters

## When is an EHF electronic document generated?

When you post a customer transaction to generate an XML file, Microsoft Dynamics AX processes the XML file and generates an EHF electronic document. The EHF file is stored in the folder (\\\\Server\\EHF\\Sales\\Target) that you create when you configure Microsoft Dynamics AX for EHF electronic invoicing.

## Which customers can I send EHF electronic documents to?

You can send EHF electronic documents to Norwegian public sector customers. You can generate an EHF electronic document for the public sector customers for whom you selected the **eInvoice** check box in the **Customers** form.

## Can I apply a transformation style sheet for an EHF electronic document?

Yes. You can store and use an Extensible Stylesheet Language for Transformations (XSLT) transformation style sheet to convert an XML file to an EHF electronic document. You can store the transformation style sheet at \\\\Server\\EHF\\Sales\\XSLT. You create this folder when you set up folders for EHF electronic invoicing. You can specify the transformation style sheet file name that is used to convert XML files to EHF electronic documents when you create a batch job for EHF electronic invoicing. Microsoft Dynamics AX uses this transformation style sheet to convert XML files to EHF electronic documents. For more information, see [(NOR) Configure EHF electronic invoicing](nor-configure-ehf-electronic-invoicing.md).

## Where can I find the default transformation style sheet?

You can find the default transformation style sheet file in the **Developer console**. Press CTRL+D to open the **Developer console**, expand the **AOT** node, and then expand the **Resources** node. Locate the resource, and then double-click the file or right-click the file, and then click **Open** to open the form. Click **Export** to export the file. The file is saved at \\\\Server\\EHF\\Sales\\XSLT.

## Can I attach supplementary documents to EHF electronic documents?

Yes. If you are using Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, you can attach a relevant file, such as a copy of the invoice to the EHF electronic document when you deliver items or services to Norwegian public sector customers. You can attach files that are in the following formats.

  - .pdf

  - .txt

  - .gif

  - .tiff

  - .tif

  - .jpeg

  - .jpg

  - .png

You can use the **Document handling of %1** form to specify the type of attachment and to attach supplementary documents to EHF electronic documents. For more information, see [Document handling (form)](https://technet.microsoft.com/en-us/library/aa616432\(v=ax.60\)).

You can specify the URL link to the supplementary documents that are related to the EHF electronic document. To specify a URL link to a supplementary document, click **New** \> **URL**, and then enter the URL in the **Description** field in the **Document handling of %1** form.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(NOR) Generate an EHF electronic document for a collection letter](nor-generate-an-ehf-electronic-document-for-a-collection-letter.md)

  


