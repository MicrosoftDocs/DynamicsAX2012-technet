---
title: Customize display templates for an online store
TOCTitle: Customize display templates for an online store
ms:assetid: fb5d84ba-7d57-486a-b6b1-d7579258ac12
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn720877(v=AX.60)
ms:contentKeyID: 62235499
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Customize display templates for an online store 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Retail starter store is a site built by using the commerce runtime (CRT) and the new site authoring and publishing model in Microsoft SharePoint Server 2013. You can use the Retail starter store as a basis for developing your own online store. To customize the display of items from your catalog, you can modify the display templates for the search-driven Web Parts. For more information, see the section *Search-driven Web Parts and display templates* in [Overview of the SharePoint 2013 page model](http://go.microsoft.com/fwlink/?linkid=294931&clcid=0x409).

You can modify any of the display templates that are found in the folder \_catalogs\\masterpage\\Display Templates\\Content Web Parts. This folder is available after you [Map a network drive](map-a-network-drive-to-the-sharepoint-2013-files-for-online-stores.md) to the SharePoint Server 2013 files for the starter store.

The following table describes three display templates that you can modify.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>File Name</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Contoso_Default_Item_ProductDetails.html</p></td>
<td><p>Display template for the Product Details page.</p></td>
</tr>
<tr class="even">
<td><p>Contoso_Default_Item_ProductQuickView.html</p></td>
<td><p>Display template for the Product QuickView page.</p></td>
</tr>
<tr class="odd">
<td><p>Contoso_Default_Item_ProductGallery</p></td>
<td><p>Display template for the Product Gallery page.</p></td>
</tr>
</tbody>
</table>


### To modify a display template

1.  Observe the web site behavior when you click on a product. For example, click **Electronics**, and then click a product name under one of the cameras to display the **Product Details** page.

2.  [Map a network drive](map-a-network-drive-to-the-sharepoint-2013-files-for-online-stores.md) to the SharePoint Server 2013 files for the starter store.

3.  Open the Contoso\_Default\_Item\_ProductDetails.html file in the \_catalogs\\masterpage\\Display Templates\\Content Web Parts folder.

4.  Find the text $resource(“ItemNumber”). ItemNumber refers to a string defined in the resource file, StorefrontResources.js.

5.  Open the StorefrontResources.js file.

6.  Find the text “ItemNumber”: “ITEM NUMBER:”, and change the text to read “ItemNumber”: “ITEM SERIAL NUMBER:”.

7.  Save your changes.

8.  Refresh the **Product Details** page in your browser and observe the changed text.

## See also

[Architecture of the Microsoft Dynamics AX Retail online store](architecture-of-the-microsoft-dynamics-ax-retail-online-store.md)

[Display template reference in SharePoint Server 2013](http://technet.microsoft.com/en-us/library/jj944947.aspx)

[How to: Create a display template in SharePoint Server 2013](http://msdn.microsoft.com/en-us/library/jj945138.aspx)

  


