---
title: Import a catalog from a vendor
TOCTitle: Import a catalog from a vendor
ms:assetid: b94877f5-d2da-4ada-b641-9850f3d30dfd
ms:mtpsurl: https://technet.microsoft.com/library/Hh242762(v=AX.60)
ms:contentKeyID: 36059115
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Import a catalog from a vendor 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To import a catalog from a vendor, you must complete the following tasks:

  - Create a catalog for the vendor in Microsoft Dynamics AX. This is where you will store the catalog maintenance request (CMR) files for the vendor.

  - Configure the vendor for catalog import.

  - Generate a catalog import file template and create a CMR file. A CMR file is an XML file that contains the product data for the vendor’s catalog.

  - Upload the CMR file from the vendor and verify that the upload was successful.


> [!NOTE]
> <P>CMR files can be created for vendor products by the customer, in the Microsoft Dynamics AX client, or by the vendor. Vendors can work in the Vendor portal in Enterprise Portal for Microsoft Dynamics AX, or they can submit their product data directly to the customer in other formats. The information in this topic explains how to import vendor catalog data from within Microsoft Dynamics AX.</P>



## Create a vendor catalog

Use this procedure to create a new vendor catalog. This is the catalog to which you upload a CMR for a vendor. If you delete the vendor catalog, you can no longer import CMR files to it. If you still want to import catalog data from the vendor, you must create a new catalog for the vendor

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Vendor catalogs**.

2.  On the **Vendor catalogs** list page, on the **Action Pane**, on the **Catalogs** tab, in the **New** group, click **Catalog**.

3.  In the **New catalog** form, in the **Vendor** field, select the vendor that you are creating the catalog for.

4.  Enter a name and description for the catalog, and then click **Close**.

5.  If the vendor has not been configured for catalog import, the **Enable vendor** dialog box appears. Click **Yes** to automatically enable the vendor for catalog import.
    

    > [!NOTE]
    > <P>The vendor must be configured for catalog import before you can create a vendor catalog for them.</P>



6.  If you want to configure the catalog so that all CMR files that are received for this vendor are automatically approved, do the following:
    
      - On the **Vendor catalogs** list page, select the catalog that you want to configure for automated approval.
    
      - On the **Action Pane**, on the **Catalogs** tab, in the **Maintain** group, click **Enable automated approval**. This sets the **Automated approval** field on the **Details** FastTab to **Enabled**.

You must configure workflow for catalog import whether the catalog will be automatically approved or the CMR files will be manually reviewed. For more information about how to configure workflow for catalog import, see [Set up Procurement and sourcing workflows](set-up-procurement-and-sourcing-workflows.md).

## Manually configure or disable a vendor for catalog import

Use this procedure to manually configure a vendor for catalog import. If you no longer upload catalog maintenance request (CMR) files for a vendor, use this procedure to disable the vendor for catalog import.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  On the **All vendors** list page, double-click the vendor that you want to configure or disable for catalog import.

3.  In the **Vendors** form, on the **Action Pane**, on the **Procurement** tab, do one of the following:
    
      - To configure the vendor for catalog import – In the **Set up** group, click **Set up**, and then click **Configure vendor for catalog import**.
    
      - To disable the vendor for catalog import – In the **Set up** group, click **Set up**, and then click **Disable catalog import**.

## Generate a catalog import file template

The catalog import file template is an industry-standard XSD file that you use to create a CMR file for a vendor’s products. You can use the CMR file to create a new catalog, replace an existing catalog, or modify an existing catalog.

After you create the CMR file, you can upload it to the vendor catalog. In the vendor catalog, you can review the details of the file.

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Vendor catalogs**.

2.  On the **Vendor catalogs** list page, double-click the catalog that you want to work with.

3.  To download a current catalog import template (XSD file), in the **Update catalog** form, on the **Action Pane**, on the **Catalogs** tab, in the **Related information** group, click **Generate catalog template**. Select one of the following options:
    
      - **Procurement category** – Generate a catalog template that includes the procurement categories in which the vendor is authorized to provide products.
    
      - **Commodity code** – Generate a catalog template that includes industry-standard commodity codes.

4.  In the **Save as** dialog box, select the location where you want to store the catalog file template and save the file.

## Create a catalog maintenance request (CMR) file

You create a CMR file by using a schema-aware XML editor. You must use the most current catalog import file template. Complete the following steps in the XML editor:

1.  To create a CMR file for a new catalog set the **"Action type"** attribute of the **\<Vendor catalog\>** element to **New**. You can create a CMR file that contains only product data, product data and product images, or only product images. The details that you include in the CMR file can include product details, product pricing, product attributes, detailed product descriptions, and product images.
    

    > [!NOTE]
    > <P>If you are creating a new catalog to replace an existing catalog, all items and services that are in that catalog are overwritten by the matching items and services in the new CMR file. Any existing items and services that are not in the new CMR file are deleted. Any items and services that are included in the new CMR file, but that are not included in the existing catalog, are treated as new products.</P>



2.  To include product images in the CMR file, enter the location of the image file for the product, and associate it with the product by using the **Image** element in the CMR file.

3.  To create a CMR file to update an existing catalog, set the **"Action type"** attribute of the **\<Vendor catalog\>** element to **Update**. Add the details for the products that you want to add, delete, or modify.

4.  To delete a selected product from an existing catalog, add the product to the CMR file, and set the **"Delete"** attribute of the **\<Product\>** element to **Yes**.

5.  Save the CMR file in the folder that you created for your vendor catalogs.

## Upload a catalog maintenance request (CMR) file in the Microsoft Dynamics AX client

After you create a CMR file, you can upload it to the vendor catalog. When you upload the CMR file, the file is validated against the catalog import template that you used. If you did not use the most current catalog import template, the catalog upload process will fail. You can view the details for the CMR file upload status in the event log. After the CMR file is uploaded successfully, you can review the details of the CMR file in the vendor catalog.

After the products in the CMR file are reviewed and approved, you can release the approved products to the legal entities in which the vendor is authorized to supply products, and appropriate trade agreements can be created. For more information about how to view and approve the products in a CMR file, see [Validate and approve imported catalogs](validate-and-approve-imported-catalogs.md).

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Vendor catalogs**.

2.  On the **Vendor catalogs** list page, double-click the catalog that you want to work with.

3.  In the **Update catalog** form, on the **Catalog file history** tab, click **Upload file**.

4.  In the **Upload file** dialog box, browse to the location of the CMR file that you created.

5.  Enter an effective date and an expiration date. These dates define the date range in which the pricing for the products in the CMR file is valid.

6.  Select one of the following update types for the CMR file:
    
      - **Add updates to the existing vendor catalog** – Add product updates to an existing catalog.
    
      - **Replace the existing vendor catalog with a new catalog** – Add a new catalog, or replace an existing catalog with a new catalog.

7.  Click **OK** to start the upload process for the CMR file.

8.  To view the details about the processing status of the CMR file, on the **Catalog file history** tab, click **Event log**.

9.  In the **Event log** form, the status of the CMR file is updated as the file is processed. CMR files can have the following statuses:
    
      - **Start processing** – The CMR file has been submitted for import.
    
      - **Start catalog upload** – The CMR file has been submitted and is in process.
    
      - **Catalog upload failed** – An error occurred after the file was submitted for processing, and the CMR file was not imported. The upload process can fail for several reasons. For example, it can fail if the file exceeds the maximum size allowed, or if too many files were submitted at the same time.
    
      - **Catalog upload complete** – The CMR file was successfully uploaded.
    
      - **Validating with schema** – The CMR file is being validated against the most current schema for catalog import.
    
      - **Invalid CMR** – The CMR file does not comply with the current schema for catalog import. If the CMR file was created by using an outdated schema, the CMR file must be recreated by using the current schema.
    
      - **Import complete** – The products and images have been successfully copied from the CMR file to the staging tables in Microsoft Dynamics AX.
    
      - **Pending approval** – The CMR file is in review and waiting for approval by the purchasing agent.
    
      - **Product rejections** – Products in the CMR file were rejected for import into the procurement catalog. Product rejections are indicated by a warning during the import process, and the file continues to be processed for products that are approved.
    
      - **Approval complete** – The purchasing professional has completed the review of the products and images that are contained in the CMR file.
    
      - **Finish processing** – Approved products and images have been added to the product master in Microsoft Dynamics AX and trade agreement journals have been created. The data in the CMR file has been passed to the archive folder for the vendor.
        

        > [!NOTE]
        > <P>When the vendor products are approved, they can be added to the product master and released to the selected legal entities. Additionally, the appropriate trade agreement journals can be created in the legal entities. For more information about how to create trade agreement journals and how to add products to the product master for vendor catalog files, see <A href="validate-and-approve-imported-catalogs.md">Validate and approve imported catalogs</A>.</P>



## See also

[Imported vendor catalogs overview](imported-vendor-catalogs-overview.md)

[Validate and approve imported catalogs](validate-and-approve-imported-catalogs.md)

[Release products to legal entity (form)](https://technet.microsoft.com/library/hh208803\(v=ax.60\))

[Event log (form)](https://technet.microsoft.com/library/hh227443\(v=ax.60\))

  


