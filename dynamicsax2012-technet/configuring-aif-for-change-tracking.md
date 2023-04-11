---
title: Configuring AIF for change tracking
TOCTitle: Configuring AIF for change tracking
ms:assetid: aa8dbbdb-dab3-40af-8450-ebf721c7f436
ms:mtpsurl: https://technet.microsoft.com/library/Hh433529(v=AX.60)
ms:contentKeyID: 36941316
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Configuring AIF for change tracking 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In services and Application Integration Framework (AIF) document services, you can use change tracking to retrieve documents that have been modified, based on criteria that you specify.

## Enabling change tracking

Change tracking must be enabled for the database tables that are used by the document service. For more information about how to enable change tracking, see [Configuring and Managing Change Tracking](https://go.microsoft.com/fwlink/?linkid=227482).

## Configuring the integration port

You can use change tracking only if the document service is exposed through an inbound enhanced integration port. To retrieve the entity keys for documents that were changed, you must expose the **getChangedKeys** service operation from the integration port. For information about how to expose service operations from enhanced integration ports, see [Customize service contracts](customize-service-contracts.md).

## Adding filtering criteria

To add filtering criteria for change tracking, you can create document filters.


> [!IMPORTANT]
> <P>You must create at least one document filter. Otherwise, no entity keys are returned from the <STRONG>getChangedKeys</STRONG> service operation.</P>



You can create document filters when you configure an inbound enhanced integration port. For information about how to create document filters, see [Configure processing options](configure-processing-options.md).

## Using change tracking

You can use change tracking in two ways:

  - Submit an XML document to AIF that specifies the getChangedKeys action in the message header.

  - Call the getChangedKeys method on a document service class.

The response message contains a list of entity keys. These keys represent the documents that have been changed according to the criteria that you specified, such as documents that were changed after a certain date and time.

For more information about how to use change tracking in development scenarios, see [AIF Document Services](aif-document-services.md).

