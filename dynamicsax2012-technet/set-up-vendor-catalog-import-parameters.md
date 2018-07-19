---
title: Set up vendor catalog import parameters
TOCTitle: Set up vendor catalog import parameters
ms:assetid: d46b92b1-c39c-446c-98cc-f6809380ea27
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242928(v=AX.60)
ms:contentKeyID: 36059520
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Catalog import
- configure root folder
- root folder
audience: Application User
ms.search.region: Global
---

# Set up vendor catalog import parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To create and maintain procurement catalogs on your procurement site, you can use information that vendors submit in the form of catalog maintenance request (CMR) files. CMR files can be submitted by the vendor in the Vendor portal. Alternatively, the purchasing professional can upload CMR files that they receive from a vendor by using the Microsoft Dynamics AX client.

## Prerequisites

CMR files are stored in a preconfigured folder. Use the following procedure to set up the parameters that Microsoft Dynamics AX will use to process imported CMR files. Before you can configure the vendor catalog import parameters, you must follow these steps:

1.  Configure a root folder where the CMR files will be stored. The root folder must be set up on either a network share or a server. When you configure a vendor for catalog import, a folder structure is created under the root folder.

2.  An enhanced integration port is required for this feature. For information about how to configure the enhanced integration port, see [Managing integration ports](managing-integration-ports.md).
    

    > [!IMPORTANT]
    > <P>The enhanced integration port must be configured after you set up the root folder.</P>



## Set up the vendor catalog import parameters

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor catalog import parameters**.

2.  In the **Vendor catalog import parameters** form, in the **Root folder path** field, enter the location of the root folder that you created for storing CMR files.

3.  In the **Maximum upload size** field, enter the maximum size, in megabytes, for the CMR files that the vendor submits. Files that exceed the maximum size are not processed and an error is logged.

4.  In the **Maximum files in process** field, enter the maximum number of CMR files that can be processed at the same time.

## See also

[Vendor catalog import parameters (form)](https://technet.microsoft.com/en-us/library/hh227602\(v=ax.60\))

[Import a catalog from a vendor](import-a-catalog-from-a-vendor.md)

[Validate and approve imported catalogs](validate-and-approve-imported-catalogs.md)

  


