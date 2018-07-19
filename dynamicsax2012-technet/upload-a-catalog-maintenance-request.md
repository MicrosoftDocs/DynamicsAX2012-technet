---
title: Upload a catalog maintenance request
TOCTitle: Upload a catalog maintenance request
ms:assetid: 9e2803cb-db76-4b20-a4bc-b386146fbc94
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271612(v=AX.60)
ms:contentKeyID: 36384244
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- CatVendorMaintenanceEventLog
- CatVendorUploadCatalog
audience: Application User
ms.search.region: Global
---

# Upload a catalog maintenance request 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Your customers can add the products that you supply to their procurement catalog. To add your products, a customer imports a catalog maintenance request (CMR) file that you provide. A CMR file is an XML file that you create in the Vendor portal. To submit the CMR file to your customer, you can upload it from the Vendor portal. Alternatively, you can send the product data to your customer, and your customer can then upload the data by using Microsoft Dynamics AX.

When you submit the CMR file for upload, the file is validated against a catalog file template that your customer provides. If the CMR file is valid, the customer reviews the products and product details, and accepts or rejects the products or the changes to existing products. After the customer has finished reviewing the products, a log file is generated that indicates how many products were approved and rejected. You can access the log file from the **Lines** FastTab in the **Update catalog** form.

1.  Click **Catalogs** on the Quick Launch.

2.  On the **Catalogs** page, select the catalog that you want to add a new CMR file to.

3.  On the **Action Pane**, on the **Catalogs** tab, in the **Maintain** group, click **Edit**.

4.  On the **Update catalog** page, click the **Browse** button to locate the CMR file that you created.

5.  Enter an effective date and an expiration date. These dates define the date range in which the pricing for the products in the CMR file is valid.

6.  Select one of the following update types for the CMR file:
    
      - **Add updates to the existing vendor catalog** – Add product updates to an existing catalog.
    
      - **Replace the existing vendor catalog with a new catalog** – Add a new catalog, or replace an existing catalog with a new catalog.

7.  Click **OK** to start the upload process for the CMR file.

The CMR file is validated against the most current catalog file template. You can view details about the processing status of the CMR file that you submitted to your customer. On the **Update catalog** page, on the **Lines** FastTab, select the CMR file for which you want to view the status, and then click **Event log**.

On the **Event log** page, the status of the CMR file is updated as the file is processed. CRM files can have the following statuses:

  - **Start processing** – The CMR file was submitted for import.

  - **Start catalog upload** – The CMR file was submitted, and the upload has started.

  - **Catalog upload failed** – An error occurred after the file was submitted for processing, and the import process stopped. A file upload can fail for many reasons. For example, the file may exceed the maximum file size that is allowed, or too many files were submitted at the same time.

  - **Catalog upload complete** – The CMR file was successfully uploaded.

  - **Validating with schema** – The CMR file is being validated against the schema that the customer supplied for catalog import.

  - **Invalid CMR** – The CMR file does not comply with the current schema for catalog import. The CMR file must be recreated based on the most current schema.

  - **Import complete** – The products and images were successfully copied from the CMR file to the staging tables in Microsoft Dynamics AX.

  - **Pending approval** – The customer is reviewing the products that are contained in the CMR file.

  - **Product rejections** – Products in the CMR file were rejected for import into the procurement catalog. Approved products in the CMR file continue to be processed.

  - **Approval complete** – The customer has reviewed the products and images that are contained in the CMR file.

  - **Finish processing** – The approved products and images were added to the product master in Microsoft Dynamics AX, and trade agreement journals were created.
    

    > [!NOTE]
    > <P>Products are added to the product master, and trade agreement journals are created, only for the legal entities that are selected in the <STRONG>Release approved products</STRONG> form.</P>



## See also

[Key tasks: Create and maintain your product catalog](key-tasks-create-and-maintain-your-product-catalog.md)

[About creating and maintaining your product catalogs](about-creating-and-maintaining-your-product-catalogs.md)

  


