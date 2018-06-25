---
title: Validate and approve imported catalogs
TOCTitle: Validate and approve imported catalogs
ms:assetid: 3d5c278c-5176-4462-832a-79e0b313192d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242238(v=AX.60)
ms:contentKeyID: 36056679
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- approve vendor catalogs
- catalog import
- vendor catalogs
---

# Validate and approve imported catalogs [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After a catalog maintenance request (CMR) file has been successfully uploaded, the purchasing professional can review the product details in the file. The vendor indicates whether the product is new, modified, or must be deleted. Information about the product pricing, product descriptions, product attributes, and order quantity requirements are also included in the CMR file. As an approver, you can indicate whether products are made available to selected legal entities and approve or reject the products in the file. Approved products are added to the product master and are released to the selected legal entities.

Use this procedure to review the product details for products that are included in a CMR file, and to approve or reject them. After you approve the products, you can release them to the legal entities that you select and generate trade agreements. Only approved products that have been released to a legal entity can be added to a procurement catalog.

## Validate and approve imported catalogs

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **Vendor catalogs**. On the **Vendor catalogs** list page, double-click a vendor catalog.

2.  In the **Update catalog** form, on the **Catalog file history** FastTab, select a CMR file, and then click **Details**.

3.  In the **Catalog approval page** form, review the product details for the products that are included in the CMR file. You can use the **Item status** field to view all items or only items that have a selected status. Select one of the following options:
    
      - **All items** – View all products that are included in the CMR file. This is the default setting.
    
      - **Add** – View only new products. After a new product is approved, it is added to the product master. When the product is released to the legal entity, the corresponding trade agreement is created and the product appears on the **Released products** list page.
    
      - **Update** – View only existing products that are being modified. After a product is approved, the modifications are applied to the existing product in the product master. New trade agreements are created only if there are price changes for the product.
    
      - **Delete** – View only products that are no longer offered by the vendor and should be deleted. After the product request is approved, the product is no longer available for purchase.

4.  To filter product changes by legal entity, select a legal entity in the **Buying legal entity** field. You can view the price, name and description, attribute value, and purchase quantity changes by legal entity.
    

    > [!NOTE]
    > <P>A legal entity appears in the list only if vendor products that have been imported are approved and released to the legal entity. If no products have been released to a legal entity for the vendor, the list is empty.</P>



5.  In the lower pane, on the **Price** tab, review the pricing for a selected product. The current price and new price are displayed in the currency and unit of measure in which the product is offered.

6.  On the **Name and description** tab, review the name and description of a selected product in specified languages.

7.  On the **Attribute** tab, review the attribute values that are assigned to a selected product.

8.  On the **Purchase quantity** tab, review changes to the purchase order quantity requirements and purchase lead time for the selected product.

9.  In the upper pane, select the products that you want to approve, and in the workflow message bar, click **Actions** \> **Approve**. Approved products are added to the product master.

10. In the upper pane, select the products that you want to reject, and in the workflow message bar, click **Actions** \> **Reject**. Products that are rejected are not added to the product master.

11. Click **Release products to legal entity**, and then in the **Release products to legal entity** form, select the legal entities in which the vendor’s approved products will be available. Corresponding trade agreements will be created for the products in these legal entities. Products must be added to the product master and be available in the legal entities before they can appear in the procurement catalog.
    

    > [!NOTE]
    > <P>If you do not release the approved products to the legal entities by using the <STRONG>Catalog approval page</STRONG> form, you can release approved products to legal entities by using either the <STRONG>Vendor catalogs</STRONG> list page or the <STRONG>Update catalog</STRONG> form.</P>



## See also

[Import a catalog from a vendor](import-a-catalog-from-a-vendor.md)

[Update catalog (form)](https://technet.microsoft.com/en-us/library/hh209525\(v=ax.60\))

[Release products to legal entity (form)](https://technet.microsoft.com/en-us/library/hh208803\(v=ax.60\))

[Catalog approval page (form)](https://technet.microsoft.com/en-us/library/hh209505\(v=ax.60\))

[Event log (form)](https://technet.microsoft.com/en-us/library/hh227443\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

