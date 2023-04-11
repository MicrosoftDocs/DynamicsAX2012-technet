---
title: Record Level Security and Outbound Documents
TOCTitle: Record Level Security and Outbound Documents
ms:assetid: 532b36b8-d76c-498a-9986-a0676f7ddda4
ms:mtpsurl: https://technet.microsoft.com/library/Aa630391(v=AX.60)
ms:contentKeyID: 35244324
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Record Level Security and Outbound Documents 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Record-level security (RLS) enables you to restrict the information shown in reports and on forms. RLS also restricts the information that is sent from Application Integration Framework (AIF) to external systems.

With RLS you can restrict access to data as shown in the following common scenarios:

  - Allows members of a sales user group to see only the accounts that they manage.

  - Prohibits financial data from appearing on forms or reports for a specific user group.

  - Prohibits account details or account IDs from appearing on forms and reports for a specific user group.

  - Restricts form and report data according to location or country/region.


> [!NOTE]
> <P>RLS does not apply when the AIF deserializes data from XML and writes to the database. This is the case for inbound documents that create data in Microsoft Dynamics AX.</P>



For more information, see [Security architecture](security-architecture-of-the-microsoft-dynamics-ax-application.md).

RLS is enabled by default for all outbound documents that are sent from Microsoft Dynamics AX through AIF. This helps ensure that AIF does not send user-restricted data. Documents sent electronically by AIF conform to the standard RLS functionality in Microsoft Dynamics AX. For more information about security in AIF documents, see [Security in Axd\<Document\> and Ax\<Table\> Classes](security-in-axd-document-and-ax-table-classes.md).

## Bypassing RLS

It may be necessary to bypass RLS in a document when the omission of data renders the document invalid, for example, in the sales invoice document. In this case, RLS is bypassed to create a valid document. The following standard documents bypass RLS by default when sent from Microsoft Dynamics AX:

  - Sales Invoice - AxdSalesInvoice

  - Advance Ship Notice - AxdASN

  - Purchase Requisition - AxdPurchaseRequisition

For more information, see [How to: Bypass Record Level Security in Outbound Documents](how-to-bypass-record-level-security-in-outbound-documents.md).

