---
title: Import a product file from a vendor
TOCTitle: Import a product file from a vendor
ms:assetid: c3ea6a29-24e0-43d3-90dd-80d5bd4271bd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597236(v=AX.60)
ms:contentKeyID: 39519310
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Import a product file from a vendor [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

To add vendor products that you sell through retail channels, you can use the catalog import feature in Microsoft Dynamics AX. Information about a vendor’s products can be imported as catalog maintenance request (CMR) files. This information can include the vendor’s product numbers, bar codes, descriptions, the vendor’s categories, size and color information, purchase prices, and sales prices. To import a vendor’s products, review and approve them, and then release them to legal entities or create purchase orders, complete the following tasks:

1.  Configure the vendor for catalog import.

2.  Create a catalog for the vendor in Microsoft Dynamics AX. You store the CMR files for retail vendors in Microsoft Dynamics AX.

3.  Generate a template for catalog import files, and create a CMR file. A CMR file is an XML file that contains the product data for a specific vendor.

4.  Upload the CMR file from the vendor, and review and approve the products.


> [!IMPORTANT]
> <P>Before you can import retail product data from your vendors, you must set up a root folder where all the CMR files, are stored. After you configure the root folder and specify the location of the folder in Microsoft Dynamics AX, you must configure an inbound integration port. Inbound integration ports are configured by using Application Integration Framework (AIF).</P>
> <P>For more information about how to set up the root folder that stores the CMR files, see <A href="set-up-vendor-catalog-import-parameters.md">Set up vendor catalog import parameters</A>. For information about how to configure the inbound integration port, see <A href="managing-integration-ports.md">Managing integration ports</A>.</P>



## Create a catalog for the retail vendor

Before you import product data from a retail vendor, you must create a catalog to store the CMR files that Microsoft Dynamics AX uses to import the products. When you create the catalog, you are also prompted to enable the vendor for catalog import. For information about how to create a catalog that a retail vendor’s CMR files can be imported into, and how to enable the retail vendor for catalog import, see [Import a catalog from a vendor](import-a-catalog-from-a-vendor.md).

## Create and upload a CMR file

To import products from your retail vendors, you first generate the XSD catalog import template for retail vendors. You then create a CMR file in XML format by using the retail vendor’s catalog import template. After the CMR file is created, you use the catalog import feature in Microsoft Dynamics AX to upload the CMR file to the retail vendor catalog that you created.

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Vendor catalogs**.

2.  On the **Vendor catalogs** list page, double-click the catalog to work with.

3.  To download the XSD file for a current catalog import template, in the **Update catalog** form, on the **Action Pane**, on the **Catalogs** tab, in the **Related information** group, click **Generate catalog template**. Then select **Retail vendor product category** in the list.

4.  In the **Save as** dialog box, select the location to store the catalog file template, and save the file.

5.  Create a CMR file by using a schema-aware XML editor. For information about how to create the XML file that is used to import a retail vendor’s product data, see [Import a catalog from a vendor](import-a-catalog-from-a-vendor.md).

6.  To upload the CMR file to the retail vendor catalog, in the **Update catalog** form, on the **Catalog file history** tab, click **Upload file**.

7.  In the **Upload file** dialog box, browse to the location of the CMR file that you created.

8.  Enter an effective date and an expiration date. These dates define the date range in which the pricing for the products in the CMR file is valid.

9.  Select one of the following update types for the CMR file:
    
      - **Add updates to the existing vendor catalog** – Add product updates to an existing catalog.
    
      - **Replace the existing vendor catalog with a new catalog** – Add a new catalog, or replace an existing catalog with a new catalog.

10. Click **OK** to start the upload for the CMR file. To view details about the processing status of the CMR file, on the **Catalog file history** tab, click **Event log**.
    
    For information about the processing status of CMR files, see [Import a catalog from a vendor](import-a-catalog-from-a-vendor.md).

## Review and approve imported retail vendor product data

After a CMR file has been successfully uploaded, you can review the product details in the file. Information in the CMR file indicates whether a product in the file is new, has been modified, or must be deleted. The CMR file also includes information about product pricing, product descriptions, product attributes, product variants, and so on. As an approver, you can indicate whether products are made available to selected legal entities, and approve or reject the products in the file. Products that you approve are added to the product master, can be released to the selected legal entities, or can be used to generate purchase orders.

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Vendor catalogs**. On the **Vendor catalogs** list page, double-click a vendor catalog.

2.  In the **Update catalog** form, on the **Catalog file history** FastTab, select a CMR file, and then click **Details**.

3.  In the **Catalog approval page** form, review the product details for the products that are included in the CMR file.
    
    To filter product changes by legal entity, select a legal entity in the **Buying legal entity** field. You can view, by legal entity, changes that were made to the price, name and description, attribute values, product dimensions, and purchase quantity.

4.  In the upper pane, select the products to approve. Then, in the workflow message bar, click **Actions** \> **Approve**. The products that you approve are added to the product master.

5.  In the upper pane, select the products to reject. Then, in the workflow message bar, click **Actions** \> **Reject**. The products that you reject are not added to the product master.

6.  Click **Release products to legal entity**, and then, in the **Release products to legal entity** form, select the legal entities in which the approved products are available. Corresponding trade agreements are created for the products in these legal entities. Products must be added to the product master and be available in the legal entities before they can be made available to retail channels.
    
    If you do not release the approved products to the legal entities by using the **Catalog approval page** form, you can release approved products to legal entities by using either the **Vendor catalogs** list page or the **Update catalog** form.

7.  To generate purchase orders for the approved products, select the **Create purchase order** check box.

For more information about how to review and approve imported product data by using the catalog import feature in Microsoft Dynamics AX, see [Validate and approve imported catalogs](validate-and-approve-imported-catalogs.md).

## See also

[About importing products from a vendor](about-importing-products-from-a-vendor.md)

[Vendor catalogs (list page)](https://technet.microsoft.com/en-us/library/hh227480\(v=ax.60\))

[Update catalog (form)](https://technet.microsoft.com/en-us/library/hh209525\(v=ax.60\))

[Catalog approval page (form) (Retail)](https://technet.microsoft.com/en-us/library/hh597317\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

