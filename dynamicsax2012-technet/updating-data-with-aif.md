---
title: Updating Data With AIF
TOCTitle: Updating Data With AIF
ms:assetid: 74f95270-663f-445b-9225-dc5a1685d6bb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc593511(v=AX.60)
ms:contentKeyID: 35245939
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Updating Data With AIF [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the different ways that you can update data by using Application Integration Framework (AIF). Many of the document services that are included with Microsoft Dynamics AX support the modification of data by using the update service operation. For more information about document services included with Microsoft Dynamics AX, see [Standard Document Services](standard-document-services.md).

AIF supports two types of updates:

  - Full update – This type of update replaces the existing document by using the new one. All the data submitted to AIF is considered to be the full document and all fields in the database tables are replaced with the field values from the submitted document. If there are fields in the corresponding tables that are not in the submitted data, those table fields are cleared according to the rules for the data type of the field. For more information about full updates, see [Full Update With AIF](full-update-with-aif.md) and [Walkthrough: Updating Data with AIF (Full Update)](walkthrough-updating-data-with-aif-full-update.md).

  - Partial update – This type of update modifies the existing document. Only the fields that are submitted to AIF are modified in the corresponding database tables. Fields for which no new values have been submitted retain their original values, unless their values have been reset to a default value because a related field was modified. For more information, see [Partial Update With AIF](partial-update-with-aif.md).

## Calling the Update Service Operation

To update data through AIF, you must call the update service operation for the document service. For example, if you want to update a sales order, call the SalesSalesOrderService.update service operation. This service operation takes two parameters.

  - \_entityKeyList – A list of one or more entity key values, or IDs, for the documents to be updated.

  - \_salesSalesOrder – The document that contains the sales order data that updates the sales order in the database.

Each of these parameters must be serialized to XML that complies with the document and related schemas. These schemas specify the content and structure of the service operation parameters. For more information about the schemas used in AIF, see [Messages and transforms in AIF](messages-and-transforms-in-aif.md) and [Document Schemas](document-schemas.md).


> [!TIP]
> <P>In some cases, you can view the fields that can be updated in a form that corresponds to a particular document. There is not an exact mapping between the way that fields are used in the form and in the document service, but frequently the correspondence is very close. For example, to see the fields involved with the Sales Order service, you can view the <STRONG>Sales order</STRONG> form. Click <STRONG>Accounts receivable</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Sales orders</STRONG> &gt; <STRONG>All sales orders</STRONG>.</P>



## See also

[Customize service contracts](customize-service-contracts.md)

[Managing integration ports](managing-integration-ports.md)

[Concurrency When Updating Data](concurrency-when-updating-data.md)

