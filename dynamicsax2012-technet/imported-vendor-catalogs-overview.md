---
title: Imported vendor catalogs overview
TOCTitle: Imported vendor catalogs overview
ms:assetid: 28a7181b-1cfa-4f15-85a4-0ec3118ded8b
ms:mtpsurl: https://technet.microsoft.com/library/Hh208492(v=AX.60)
ms:contentKeyID: 36056216
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- vendors
- import
- vendor catalogs
- vendor catalog
- imported vendor
- imported vendors
audience: Application User
ms.search.region: Global
---

# Imported vendor catalogs overview 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, purchasing professionals can create and maintain catalogs for company employees to use when they order items and services for internal use. When you create a procurement catalog you can add the items and services that you make available to employees, either by importing the vendor catalog data or by adding the vendor catalog data to the product master manually. If you use the catalog import process, the vendor can either upload their product catalog data by using the Vendor portal in Enterprise Portal for Microsoft Dynamics AX, or they can send you the product catalog data and you can upload it by using the Microsoft Dynamics AX client.

The product data that the vendor submits to you, in the form of a catalog maintenance request (CMR) file, must be in XML file format. The CMR file should contain all of the details for the products that the vendor supplies to your company. The CMR file can also include product image files. The product images can appear on the procurement site in Enterprise Portal.

## Importing vendor catalog data

To import vendor catalog data, you must complete the following tasks:

1.  Set up the system to import vendor catalog data.
    
      - Create a folder where you can store the CMR files that a vendor submits.
    
      - Configure an inbound port for catalog import by using the Application Integration Framework (AIF).

2.  Set up a procurement category hierarchy, and assign your vendors to procurement categories. If you use commodity codes, add the commodity codes to the procurement categories.

3.  Configure the vendor for catalog import.

4.  Configure workflow for catalog import.

5.  Create a vendor catalog.

6.  Generate a catalog import file template. The catalog file template is an XSD file that is used by the vendor to build the catalog maintenance request XML file.

7.  Create a CMR file.

8.  Upload the CMR file.

9.  Review, approve, or reject the products in the vendor catalog. Only approved products can be added to the procurement catalog.

## Set up the system to import vendor catalog data

Before you can import vendor catalog maintenance request (CMR) files, you must set up a root folder where all of the files are stored. The root folder must be set up on either a network share or a server. When you configure a vendor for catalog import, a folder structure is created under the root folder. When a CMR file is uploaded, it is stored in the pickup folder that was created when the vendor was configured for catalog import. The catalog import process pulls the CMR files from the pickup folder and pushes the data into Microsoft Dynamics AX.

After you configure the root folder and identify the location of the folder in Microsoft Dynamics AX, you must configure an inbound integration port. Inbound integration ports are configured by using the Application Integration Framework (AIF).

For information about how to set the root folder location for catalog import, see [Set up vendor catalog import parameters](set-up-vendor-catalog-import-parameters.md). For information about how to configure the inbound integration port, see [Walkthrough: Configuring an inbound integration port for catalog import](walkthrough-configuring-an-inbound-integration-port-for-catalog-import.md).

## Assign vendors to procurement categories

You must assign a vendor to the procurement categories in which they are authorized to supply products.

When the CMR file is created, it must include either the procurement categories or the commodity codes that the vendor uses. When the CMR file is uploaded, the vendor’s products are automatically mapped to the procurement categories.

For information about how to set up a procurement category hierarchy and assign commodity codes to a procurement category, see [Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md). For information about how to assign a vendor to a procurement category, see [Key tasks: Set up and maintain procurement category hierarchies](key-tasks-set-up-and-maintain-procurement-category-hierarchies.md).

## Configure the vendor for catalog import

You can configure the vendor for catalog import by using one of the following methods:

  - When you create a new vendor catalog on the **Vendor catalogs** list page, the system asks if you want to configure the vendor for catalog import, if the vendor is not already configured for catalog import. If you click **Yes**, the vendor is automatically configured for catalog import.

  - You can manually configure the vendor for catalog import by using the **Vendors** form. To open the **Vendors** form, do the following:
    
    1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
    2.  Select a vendor in the list. Then configure the vendor for catalog import.

To disable a vendor for catalog import, you must use the **Vendors** form.

For information about how to configure a vendor for catalog import, see [Import a catalog from a vendor](import-a-catalog-from-a-vendor.md).

## Configure workflow for catalog import

When you import a catalog maintenance request (CMR) file, you have two options when routing the CMR through workflow. You can set up the vendor’s catalog for automated approval, or you can route the CMR file and its products to one or more reviewers. If you enable the automated approval option for a vendor catalog, the CMR files that are received from the vendor are automatically approved by using workflow. No manual intervention is required. If you want to manually review and approve or reject the CMR files that you import, you must configure the workflow process so that the CMR files are routed to the appropriate reviewers.

To configure workflow for catalog import, set up the following types of workflow in this order:

1.  **Catalog import product approval** – The line-level workflow. This workflow processes all the products that are included in the CMR file. Completion of the individual line-level workflow completes the overall catalog import workflow.

2.  **Catalog import approval** – The header-level workflow. This workflow processes the CMR file as a whole. When you configure this workflow, you must reference the **Catalog import product approval** workflow that you configured.

For more information about how to configure workflow for catalog import, see [Set up Procurement and sourcing workflows](set-up-procurement-and-sourcing-workflows.md).

## Create a vendor catalog

You must set up a catalog for your vendor. The catalog maintenance request (CMR) files that you receive from your vendor are grouped in this catalog. After you set up the catalog, you can upload CMR files for the vendor or the vendor can submit CMR files for their catalog. You can also view the details and the event log for new or existing CMR files that have been added to the vendor catalog.

For information about how to create a vendor catalog, see [Import a catalog from a vendor](import-a-catalog-from-a-vendor.md).

## Create and upload a CMR file

To create and upload a catalog maintenance request (CMR) file, you or the vendor must do the following tasks:

  - Generate the catalog import file template, in .xsd format. The vendor uses this file to create and submit their CMR file.
    
    Depending on the selection that you make when you generate the catalog import file template, the template automatically includes either the procurement categories or the commodity codes that the vendor is associated with.

  - Use the catalog import file template to create the CMR XML file that contains the vendor’s products.
    
    When the CMR file is created, the products that are included in the file are mapped to the procurement categories in the catalog template. Alternatively, if commodity codes are included in the catalog import file template, the commodity codes are used to map the products to the procurement categories.

  - Upload the CMR file.

For information about how to create and upload a CMR file, see [Import a catalog from a vendor](import-a-catalog-from-a-vendor.md).

## Review, approve, or reject products in a vendor catalog

After a catalog maintenance request (CMR) file has been submitted and imported, the purchasing professional can review the details of the CMR by using the **Catalog approval page** form. Details that can be reviewed include the product name, description, pricing, product attributes, or order quantity requirements.

As an approver, you can indicate whether products are made available to selected legal entities and approve or reject the products in the file. Approved products are added to the product master and are released to the selected legal entities.

For information about how to review, approve, or reject products in a vendor catalog, see [Validate and approve imported catalogs](validate-and-approve-imported-catalogs.md)

## See also

[Set up vendor catalog import parameters](set-up-vendor-catalog-import-parameters.md)

[Import a catalog from a vendor](import-a-catalog-from-a-vendor.md)

[Validate and approve imported catalogs](validate-and-approve-imported-catalogs.md)

  


