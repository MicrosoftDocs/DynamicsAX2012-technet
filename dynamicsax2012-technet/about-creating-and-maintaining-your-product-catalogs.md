---
title: About creating and maintaining your product catalogs
TOCTitle: About creating and maintaining your product catalogs
ms:assetid: 1a7e1499-01c7-457c-b8f5-a15d2dffe772
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271465(v=AX.60)
ms:contentKeyID: 36384097
ms.date: 05/01/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About creating and maintaining your product catalogs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the Vendor portal, you can create and maintain a catalog of the items and services that you supply to your customer. You deliver your catalog information in an XML file that contains details about the products that you supply. After the file is uploaded from the Vendor portal to the customer, the customer can import your products into their procurement catalog.

Before you can download a catalog import file template or upload a product catalog in the Vendor portal, the following tasks must be completed:

  - Your customer must configure your company for catalog import in Microsoft Dynamics AX.

  - A user in your company must be authorized to upload catalog maintenance request (CMR) files for the vendor catalogs in the Vendor portal.

For more information about how to use the Vendor portal, see [About the Vendor portal](about-the-vendor-portal.md). For more information about how to submit user requests for access to the Vendor portal, see [Add and maintain your users](add-and-maintain-your-users.md). For more information about the available vendor roles, see [About user roles](about-user-roles.md).

## Maintaining product catalogs

Creating or updating a catalog involves the following general steps:

1.  Download the catalog import file template from the Vendor portal. Select whether you want to generate a template that includes the procurement categories in which you are authorized to supply products, or a template that includes industry-standard commodity codes for your products. If you use industry-standard commodity codes, the codes are used to map the categorization of the products.

2.  Create a catalog maintenance request (CMR) file, and validate it against the catalog file template.

3.  In the Vendor portal, upload the CMR file to the customer.

4.  Review the details of the catalog file.

## Download the catalog file template from the Vendor portal

The catalog import file template is an industry-standard XSD file that you can use to build an XML file. The XML file that you build contains the details about the items and services that you supply to your customer.

When you generate the catalog file template, you must indicate whether your CMR file will include industry-standard commodity codes or the customer's procurement categories for each product. If the template includes procurement categories, the products that are included in the CMR file are mapped to the procurement categories in the catalog file template. If the catalog file template includes commodity codes, the codes are used to map the categorization of the products. The XML file that you create and upload for your customer must include either commodity codes or procurement categories.

When you upload your XML file, the file is validated against the most current XSD schema. If the file format does not match the requirements of the schema, the upload will fail and your catalog file will be rejected.


> [!IMPORTANT]
> <P>You must not modify the XSD file after you download it from your customer.</P>



For more information about how to generate a catalog import file template, see [Key tasks: Create and maintain your product catalog](key-tasks-create-and-maintain-your-product-catalog.md).

## Create a catalog maintenance request (CMR) file

By using a schema-aware XML editor, you can create an XML CMR file that is validated against the catalog file template that you downloaded from your customer. The CMR file can include data for your products such as product pricing, product attributes, detailed product descriptions, and related products. The file can also include the path of the file where the product images are stored. You can submit a CMR file that contains any of the following information:

  - Only product data

  - Product data plus the path of the file where the product images are stored

  - Only the path of the file where the product images are stored


> [!NOTE]
> <P>Microsoft Dynamics AX does not provide a schema-aware XML editor.</P>



For more information about how to create a catalog file, see [Key tasks: Create and maintain your product catalog](key-tasks-create-and-maintain-your-product-catalog.md).

## Upload the catalog maintenance request file to the Vendor portal

When you create the XML CMR file, you can indicate whether the file is a new catalog or an update to an existing catalog.

  - If the file is a new catalog, all of the approved items and services that are included in the CMR file are added to your customer's catalog.

  - If the file is a new catalog that replaces an existing catalog, all existing items and services are overwritten by the items and services that are included in the new CMR file. Any existing items that are not included in the new catalog are deleted from the existing catalog.

  - If the file is an update to an existing catalog, you can indicate that the new catalog file is an update to an existing catalog and you can add the details about the items and services that are changing, add new items, and delete existing items.

For more information about how to upload a CMR file, see [Upload a catalog maintenance request](upload-a-catalog-maintenance-request.md).

## Review the details of the catalog maintenance request file

After you upload the CMR file, you can view the upload status for the file.

After the catalog file is successfully uploaded, your customer can import the product data, review and approve the products and changes, and add the products to its procurement catalog. An information log displays the status of the CMR file. The log includes information about any products that the customer rejected for import.

For more information about how to review the details of a CMR file, see [Upload a catalog maintenance request](upload-a-catalog-maintenance-request.md).

## See also

[Key tasks: Create and maintain your product catalog](key-tasks-create-and-maintain-your-product-catalog.md)

[Upload a catalog maintenance request](upload-a-catalog-maintenance-request.md)

  


