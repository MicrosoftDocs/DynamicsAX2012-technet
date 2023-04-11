---
title: (BRA) Import and verify NF-e XML documents and DANFE that you receive in emails
TOCTitle: (BRA) Import and verify NF-e XML documents and DANFE that you receive in emails
ms:assetid: 40e55405-0d7f-4026-8f58-46cd618c1d80
ms:mtpsurl: https://technet.microsoft.com/library/Dn527707(v=AX.60)
ms:contentKeyID: 59626279
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- XML
- Brazil
- NF-e
- DANFE
- BR - 00048
- emails
- import XML
- import DANFE
- import NF-e XML
audience: Application User
ms.search.region: Brazil
---

# (BRA) Import and verify NF-e XML documents and DANFE that you receive in emails 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can perform the following tasks to set up and use Microsoft Dynamics AX to import Nota Fiscal eletrônica (NF-e) XML documents and Documento Auxiliar da Nota Fiscal Eletrônica (DANFE) that you receive in emails.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



  - Set up email accounts to import XML files and DANFE for electronic fiscal documents.

  - Set up the Instituto Brasileiro de Geografia e Estatistica (IBGE) code for a state, and then set up a state authority.

  - Import the NF-e XML documents and DANFE that you receive in emails, and then perform the following tasks:
    
      - View the XML document for an NF-e.
    
      - View the DANFE for the NF-e XML document.
    
      - Inquire about the current status of the NF-e at the Secretaria da Fazenda (SEFAZ) using the access key.

  - Manually enter an access key for an NF-e for which you did not receive an XML document.

  - Post electronic fiscal documents that have access keys that are not validated by the SEFAZ. Alternatively, you can set up Microsoft Dynamics AX to post only the electronic fiscal documents that have access keys that are validated by the SEFAZ.

  - If you post the electronic fiscal documents for which access keys are not available in the **Received NF-e XML documents** form, you can update the access keys or XML documents for the electronic fiscal documents after posting. You can view the posted NF-e documents that require access keys or XML documents:
    
      - NF-e documents for which the access keys are not validated by the SEFAZ.
    
      - NF-e documents for which the status is updated from approved to canceled.
    
      - NF-e documents for which XML attachments are not available.
    
      - NF-e documents for which the access keys are not available in the received NF-e XML documents.

  - You can also view the electronic fiscal documents that are not posted, and for which you receive the access keys.

You can set up Microsoft Dynamics AX to inquire about the status of NF-e access keys at the SEFAZ multiple times. Inquiries regarding the status of the NF-e are made multiple times, and the last inquiry is performed after the time that the vendor has to cancel an approved NF-e has elapsed.

For more information, see [(BRA) Set up, import, and verify NF-e XML documents and DANFE that you receive in emails](bra-set-up-import-and-verify-nf-e-xml-documents-and-danfe-that-you-receive-in-emails.md).

## How do I import XML documents and DANFE from emails?

You can use the **Import XML files from email** form to import the XML files and DANFE for NF-e from emails. You must set up email accounts that are used to import XML documents and DANFE for NF-e before you import the files.

## Can I update the access key manually for an NF-e for which I did not receive the XML document?

Yes. You can update the access key manually for an NF-e for which you did not receive the XML document. You can first generate the list of NF-e documents for which the access keys are not available in the received NF-e XML documents. You can select the **Access keys are not found in received NF-e XML documents** check box in the **Posted NF-e with pending validation** form to generate the list, and then update the access key for the NF-e in the **Access key** field in the **Received NF-e XML documents** form.

## Can I post an NF-e document without validating the access key?

Yes. You can post an NF-e document without validating the access key. You can validate the access keys for these NF-e documents after posting. To generate a list of NF-e documents for which the access keys are not validated by the SEFAZ, select the **SEFAZ status not inquired** check box in the **Posted NF-e with pending validation** form.

Conversely, you can select the **Post only NF-e that have valid access keys** check box on the **NF-e federal** FastTab in the **Fiscal establishments** form to set up Microsoft Dynamics AX to post only the electronic fiscal documents that have access keys that are validated by the SEFAZ.

## How do I set up Microsoft Dynamics AX to inquire about the status of NF-e access keys at the SEFAZ?

You can use the **Received XML Inquiry** form to set up Microsoft Dynamics AX to inquire about the status of NF-e access keys at the SEFAZ. Inquiries regarding the status of the access keys are made multiple times before the NF-e is approved, and one additional inquiry is made about the status after the time that the vendor has to cancel an approved NF-e has elapsed.

## How do I generate a list of NF-e documents that were not posted, and for which I received the XML documents?

You can use the **Posted** check box in the **Received NF-e XML documents** form to verify the NF-e documents that were not posted, and for which you have received the XML documents.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  


