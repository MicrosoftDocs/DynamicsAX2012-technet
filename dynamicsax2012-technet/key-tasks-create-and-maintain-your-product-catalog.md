---
title: 'Key tasks: Create and maintain your product catalog'
TOCTitle: 'Key tasks: Create and maintain your product catalog'
ms:assetid: 133c3ace-840e-41ec-a57d-3384040d246a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271457(v=AX.60)
ms:contentKeyID: 36384089
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- catalog import
- CatVendorCatalogCreate
- CatVendorCatalogDelete
- CatVendorCatalogDetails
- CatVendorCatalogSchemaDownload
- catalog maintenance request
- catalog template
---

# Key tasks: Create and maintain your product catalog [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A catalog maintenance request (CMR) file is an XML file that contains information about the products that you want to supply to your customer. You upload CMR files to the customer by using the vendor self-service portal.

To create and maintain CMR files that your customer can import, complete the following tasks:

  - Create a new catalog to store the CMR files that you create and send to your customer.

  - Generate the catalog file template.

  - Determine whether the CMR file will include product data only, product data and the path to the product images, or the path to the product images only.

  - Determine whether the CMR file represents a new catalog or an update to an existing catalog. You can also delete catalogs that are no longer valid, or delete selected products from your catalogs.

  - Create a CMR file by using a schema-aware XML editor.


> [!NOTE]
> <P>These tasks are performed on the <STRONG>Vendor catalogs</STRONG> page. Before you can access this page, your customer must configure your company for catalog import in Microsoft Dynamics AX.</P>



## What do you want to do?

Learn more about...

Create a new catalog

Generate a catalog file template

Create a CMR file

Delete a catalog

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About creating and maintaining your product catalogs](about-creating-and-maintaining-your-product-catalogs.md)

## Create a new catalog

Create a catalog to store the CMR files that you submit to your customer. For example, you can create one catalog to store the CMR files for products that you offer in the fall, and another catalog for products that you offer in the spring. You can also upload a new CMR file when you create your catalog. For more information about how to upload a CMR file, see [Upload a catalog maintenance request](upload-a-catalog-maintenance-request.md).

1.  Click **Catalogs** on the Quick Launch.

2.  On the **Action Pane**, on the **Catalogs** tab, in the **New** group, click **Catalog**.

3.  On the **New catalog** page, enter a name and description for the catalog.

4.  Click **Save and close** to save the catalog.

Back to top

## Generate a catalog file template

Before you create the catalog maintenance request (CMR) file for the products in your catalog, you must generate the customer's most current catalog file template. You use the template to create your CMR files.

You can generate a CMR template that includes the procurement categories in which you are authorized to provide products. When you add your products to the file, you map them to the appropriate procurement categories. Alternatively, you can generate a catalog template that includes industry-standard commodity codes. Your customer can use the commodity codes to map your products to the appropriate procurement categories.

1.  Click **Catalogs** on the Quick Launch.

2.  Generate the most current catalog file template from your customer. On the **Catalogs** page, select one of the following options:
    
      - **Procurement category** – The CMR file template will contain all of the procurement categories in which your customer has authorized you to supply products.
    
      - **Commodity code** – You will provide the commodity codes for each of your products when you create the XML file. The commodity codes are used to map your products to the procurement categories in which your customer has authorized you to supply products.
        
        You must include either a procurement category or a commodity code for each item or service that you include in your CMR file.
        

        > [!NOTE]
        > <P>When you upload your CMR file, the XML file that you create is validated against the most current XSD schema that your customer provided. If the format of your CMR file does not match the requirements of the schema, the upload fails, and your CMR file is rejected.</P>



3.  In the **Save As** dialog box, select the location where you want to store the catalog file template and save the file.
    

    > [!NOTE]
    > <P>You must have both read access and write access to the folder that you save the catalog file template to.</P>



Back to top

 

## Create a CMR file

Create an XML catalog maintenance request (CMR) file by using a schema-aware XML editor, based on the catalog template that you downloaded from your customer. You can use the CMR file that you create to create a new catalog, replace an existing catalog, or modify an existing catalog.

Create a CMR file for a new catalog if you are sending the catalog to the customer for the first time, or if you are fully replacing an existing catalog. If you are replacing an existing catalog, all items and services that are in that catalog are overwritten by the matching items and services in the new CMR file. Any existing items and services that are not in the new CMR file are deleted. Any items and services that are included in the new CMR file, but that are not included in the existing catalog, are treated as new products and added to the catalog.

Create a CMR file to update an existing catalog if you only want to make some modifications to the catalog, such as add products or update your pricing. The CMR file can contain only the products or product details that you want to modify. You can modify a product's price, description, product attributes, or requirements for purchase quantities. You can also add new products, add or modify product images, or delete existing products.

After you create the CMR file, you can upload it to your customer in the vendor self-service portal. For more information about how to upload a CMR file to your customer, see [Upload a catalog maintenance request](upload-a-catalog-maintenance-request.md).

### Create a CMR file for a new catalog

1.  Generate the most current catalog file template from your customer.

2.  Create a CMR file by using a schema-aware XML editor, and set the **"Action type"** attribute of the **\<Vendor catalog\>** element to **New**. You can create a CMR file that contains only product data, product data and product images, or only product images. The details that you include in the CMR file can include product details, product pricing, product attributes, detailed product descriptions, data about related products, and product images.
    
    To include product images in the CMR file, enter the location of the image file for the product, and associate it with the product by using the **Image** element in the CMR file.

3.  Save the CMR file, and validate it against the catalog file template.

### Create a CMR file to update an existing catalog

1.  Generate the most current catalog file template from your customer.

2.  Create a CMR file by using a schema-aware XML editor, and set the **"Action type"** attribute of the **\<Vendor catalog\>** element to **Update**. Add the details for the products that you want to add, delete, or modify.

3.  To delete a selected product from an existing catalog, add the product to the CMR file, and set the **"Delete"** attribute of the **\<Product\>** element to **Yes**.

4.  Save the CMR file, and validate it against the catalog file template.

Back to top

## Delete a catalog

You can delete catalogs that contain products that you no longer offer to your customer. Alternatively, you can delete only selected products from an existing catalog. When you delete a catalog, it remains in the catalog list. CMR files cannot be added to a catalog that has been deleted. Additionally, products that are contained in a catalog that has been deleted are no longer available for order.

1.  Click **Catalogs** on the Quick Launch.

2.  On the **Vendor catalogs** page, select the catalog file that you want to delete, or that you want to delete products from.

3.  To delete the whole catalog, on the **Action Pane**, on the **Catalogs** tab, in the **Maintain** group, click **Delete**. In the **Vendor catalog message** dialog box, click **Yes**.
    
    –or–
    
    To delete selected products from the catalog, create a CMR file for the catalog. Then, for each product that you want to delete, set the **"Delete"** attribute of the **\<Product\>** element to **Yes**.

Back to top

## Find related tasks

[Upload a catalog maintenance request](upload-a-catalog-maintenance-request.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

