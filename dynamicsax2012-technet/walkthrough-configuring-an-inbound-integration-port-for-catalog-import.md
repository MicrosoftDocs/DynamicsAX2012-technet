---
title: 'Walkthrough: Configuring an inbound integration port for catalog import'
TOCTitle: 'Walkthrough: Configuring an inbound integration port for catalog import'
ms:assetid: 9f843ab7-ea4a-47d1-a3a4-d5da5215281f
ms:mtpsurl: https://technet.microsoft.com/library/Hh533450(v=AX.60)
ms:contentKeyID: 39056466
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Walkthrough: Configuring an inbound integration port for catalog import 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To create and maintain procurement catalogs on your procurement site, you can allow vendors to submit catalog maintenance request (CMR) files by using the vendor self-service portal. Before a vendor can use the vendor self-service portal to import catalog files, you must set up an integration port by using Application Integration Framework (AIF). Only users who are assigned to the System Administrator role can configure integration ports.

This topic provides specific information about how to configure an integration port to receive CMR files. This task is only one of the steps that are required to enable imported catalogs. Before you can configure a port to receive CMR files from vendors, you must set up a root folder where all the files are stored. For information about how to set up the root folder, and for an overview of the whole process that is used to import catalogs, see [Imported vendor catalogs overview](imported-vendor-catalogs-overview.md).

## Initialize AIF

If this is the first time that you have worked with services and AIF, you must first set up AIF. To set up AIF, follow these steps.

1.  Click **System administration** \> **Setup** \> **Checklists** \> **Initialization checklist**.

2.  Expand the **Initialize system** node.

3.  Click **Set up Application Integration Framework**.

Adapters, basic ports, and services are registered. This operation can take some time to be completed.

## Create the integration port

Use this procedure to set up the inbound port. You also use this procedure to specify the location where the AIF service can find the CMR file that has been submitted for import.

1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  Click **New** to create a new enhanced inbound port.

3.  Enter a name and an optional description to identify the port that is used to import catalogs.

4.  In the **Adapter** list, select **File system adapter**.

5.  In the **URI** field, enter the path of the CatalogImportPickup subfolder in the root folder that you created to receive the vendor’s catalog files.

## Add the service operation

Inbound integration ports must be associated with a service operation. To enable the processing of imported catalogs, you must select the **CatImpService.create** service operation.

1.  In the **Inbound ports** form, on the **Service contract customizations** tab, click **Service operations**.

2.  In the **Select service operations** form, in the **Remaining service operations** list, select **CatImpService.create**.

3.  Click the arrow button to move the service operation to the **Selected service operations** list.

4.  Close the form.

## Add the pipeline component

The catalog import service requires a special component that processes CMR documents. To enable this component, follow these steps.

1.  In the **Inbound ports** form, on the **Processing options** tab, select the **Preprocess service operation requests** check box, and then click **Inbound pipelines**.

2.  In the **Inbound pipelines** form, click **Add**. Then, in the **Class name** list, select **CatVendorXmlTransform**.

3.  In the **Purpose** field, enter an optional description, such as “Transform vendor XML files,” and then close the **Inbound pipelines** form.

4.  Click **Activate** to deploy the integration port.

## Configuration notes

Permissions to submit CMR files are maintained through the vendor self-service portal. We do not recommend that you use the security settings in the **Inbound ports** form to add restrictions.

## See also

[Managing integration ports](managing-integration-ports.md)

