---
title: About importing products from a vendor
TOCTitle: About importing products from a vendor
ms:assetid: 5a0bc98c-6e42-4138-a470-6d8f6768d68b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597102(v=AX.60)
ms:contentKeyID: 39519150
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- vendors
- products
- product
---

# About importing products from a vendor 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Any products that you sell through retail channels must first be added to Microsoft Dynamics AX. You can create and maintain product data manually, or you can import product data from your vendors. To import product data from your vendors, you can use the catalog import feature in Microsoft Dynamics AX. The files from the vendors are submitted as catalog maintenance request (CMR) files. The information in these files can include the vendor’s product numbers, bar codes, descriptions, the vendor’s categories, size and color information, purchase prices, and sales prices. You can review the product data that is included in the CMR file, and then approve or reject the products. After the products are approved, the product data is added to the product master and released to specific legal entities. Product data for sales prices, purchase prices, bar codes, and variants is also added or updated, or used to create purchase orders.

To import product data from your retail vendors, you must complete the following tasks:

1.  Create a folder to store the CMR files that are received from the vendor.

2.  Configure an inbound integration port by using Application Integration Framework (AIF).

3.  Set up a retail product hierarchy, and map your vendors to the categories in which they supply products.

4.  Configure workflow for catalog import.

5.  Configure the vendor for catalog import.

6.  Create a retail vendor catalog.

7.  Generate a template for catalog import files. This template is an XSD file that is used to build the CMR files. CMR files are in XML format.

8.  Create a CMR file.

9.  Upload the CMR file.

10. Review the products in the vendor catalog, and approve or reject the products.

## Set up the system to import vendor catalog data

Before you can import retail product data from your vendors, you must set up a root folder where all the catalog import files, or CMR files, are stored. After you configure the root folder and specify the location of the folder in Microsoft Dynamics AX, you must configure an inbound integration port. Inbound integration ports are configured by using AIF.

For more information about how to set up the root folder that stores the CMR files, see [Set up vendor catalog import parameters](set-up-vendor-catalog-import-parameters.md). For information about how to configure the inbound integration port, see [Managing integration ports](managing-integration-ports.md).

## Set up a retail product hierarchy and a retail vendor category hierarchy

A CMR file that is created for the vendor’s product data must include the categories in which the vendor supplies products. To map vendors to the retail categories in which the vendors supply products, you must complete the following tasks:

1.  Create a retail product hierarchy.

2.  Create a retail vendor category hierarchy.

3.  Assign the vendor to the retail vendor category hierarchy.

4.  Add the vendor’s category to the retail product category in the retail product hierarchy.

For information about how to set up a retail product hierarchy, see [Set up a retail hierarchy](set-up-a-retail-hierarchy.md). For information about how to set up a retail vendor category hierarchy, see [Set up a retail vendor hierarchy](set-up-a-retail-vendor-hierarchy.md).

## Configure the vendor for catalog import

Before you can import CMR files for a vendor’s retail products, you must enable the vendor for catalog import. You can automatically enable the vendor for catalog import when you create a new vendor catalog on the **Vendor catalogs** list page. Alternatively, you can manually enable the vendor for catalog import in the **Vendors** form.

For more information about how to configure a vendor for catalog import, see [Import a product file from a vendor](import-a-product-file-from-a-vendor.md).

## Configure workflow for catalog import

When you import a CMR file that includes data for a vendor’s retail products, you can route the CMR file through workflow in two ways. You can set up the vendor’s catalog for automated approval, or you can route the CMR file and the products that it contains to one or more reviewers for manual review and approval.

For more information about how to configure workflow for catalog import, see [Set up Procurement and sourcing workflows](set-up-procurement-and-sourcing-workflows.md).

## Create a retail vendor catalog

You must set up an import catalog for your vendor. The CMR files that you receive from your vendor are grouped into this catalog.

For more information about how to create a retail vendor catalog, see [Import a product file from a vendor](import-a-product-file-from-a-vendor.md).

## Create and upload a CMR file

A CMR file is the source of the retail vendor’s catalog data. The CMR file is an XML file that is created from an XSD file. The format of the XSD file is based on the categories in which the vendor supplies products. This file includes information such as the vendor’s product numbers, bar codes, descriptions, the vendor’s categories, size and color information, purchase prices, and sales prices.

To create and upload the CMR file for a retail vendor, you must complete the following tasks:

1.  Generate the XSD file for the vendor by using the template for catalog import files.

2.  Create the XML file that includes the data for the vendor’s products. This task can be completed either by the vendor or by the user who maintains the vendor’s product data for your organization.

3.  Upload the CMR file to the vendor catalog.

For more information about how to create and upload a CMR file, see [Import a product file from a vendor](import-a-product-file-from-a-vendor.md).

## Review, approve, or reject the products in the vendor catalog

After a CMR file has been submitted and imported, you can review the details of the CMR file by using the **Catalog approval page** form. You can then release the approved products to the appropriate legal entities and, optionally, generate purchase orders for the approved products.

## See also

[Import a product file from a vendor](import-a-product-file-from-a-vendor.md)

[Imported vendor catalogs overview](imported-vendor-catalogs-overview.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

