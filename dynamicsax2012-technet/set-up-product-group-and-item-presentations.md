---
title: Set up product group and item presentations
TOCTitle: Set up product group and item presentations
ms:assetid: 4dd2d889-6626-4fda-8b11-41cdc02e9d9b
ms:mtpsurl: https://technet.microsoft.com/library/Aa497121(v=AX.60)
ms:contentKeyID: 44080981
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up product group and item presentations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the **Presentations** form, you can add descriptive text and an image for each product group. You can also add a description and an image for specific items. Both product groups and items are presented together with images, headings, and additional information.

When a customer clicks a product group in Enterprise Portal for Microsoft Dynamics AX, a list of the product items in that group is displayed. The text and image for the product group are displayed above the list of product items. When a customer clicks a product item, the product is presented together with a picture, summary, and product description.


> [!NOTE]
> <P>The tabs in the lower pane vary, depending on whether you select <STRONG>Product group</STRONG> or <STRONG>Item</STRONG> in the <STRONG>Type</STRONG> field:</P>
> <UL>
> <LI>
> <P>If you select <STRONG>Product group</STRONG>, the <STRONG>Text</STRONG> and <STRONG>Image</STRONG> tabs are available.</P>
> <LI>
> <P>If you select <STRONG>Item</STRONG>, the <STRONG>Description</STRONG>, <STRONG>Summary</STRONG>, <STRONG>Product description</STRONG>, and <STRONG>Image</STRONG> tabs are available.</P></LI></UL>



1.  Click **Product information management** \> **Setup** \> **Product catalogs** \> **Presentations**.

2.  In the **Type** field, select **Product group** or **Item**.

3.  In the **Language** field, select the language for the description, if your implementation supports multiple languages.

4.  For each tab, click **Edit** to add or modify the information for the product group or item. You can format the text in the text editor or the HTML editor.
    
    If you selected **Product group** in the **Type** field, follow these steps:
    
    1.  On the **Text** tab, click **Edit** to add or modify the heading for the product group. This heading is displayed when a user selects a product group.
    
    2.  In the **Brief description** field, enter the heading that is displayed when all the product groups are presented on the first webpage. This heading is displayed before the heading that is entered on the **Text** tab.
    
    3.  On the **Image** tab, click **Append** to insert an image.
    
    4.  In the **Add image** form, select the **Add to all languages** check box to add the image for all languages. If you do not select this check box, the image is added only for the current language.
    
    5.  Click **OK**, browse to the image to add to the current node, and then click **Open**.
    
    If you selected **Item** in the **Type** field, follow these steps:
    
    1.  On the **Description** tab, click **Edit** to add or modify the description for each item. The description is displayed on the **Description** tab of the webpage that shows item information. In the **Brief description** field, you can add or modify the heading that is displayed as a link to view additional item details. This heading is displayed when all the items in a product group are displayed.
    
    2.  On the **Summary** tab, click **Edit** to add or modify a summary. The summary is displayed together with the brief description. The summary also is displayed on the **Overview** tab of the webpage that shows item information.
    
    3.  On the **Product description** tab, click **Edit** to add a more detailed description for each item. This information is displayed below the description on the **Description** tab of the webpage that shows item information.
    
    4.  On the **Image** tab, click **Append** to insert an image.
    
    5.  In the **Add image** form, select the **Add to all languages** check box to add the image for all languages. If you do not select this check box, the image is added only for the current language.
    
    6.  Click **OK**, browse to the image to add to the current node, and then click **Open**.


> [!NOTE]
> <P>The image formats that are supported on the Internet are GIF and JPG.</P>


  


