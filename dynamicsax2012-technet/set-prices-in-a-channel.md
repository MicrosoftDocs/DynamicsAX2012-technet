---
title: Set prices in a channel
TOCTitle: Set prices in a channel
ms:assetid: 49f7e8b2-682d-430e-b8cc-c0ee38210093
ms:mtpsurl: https://technet.microsoft.com/library/Dn497746(v=AX.60)
ms:contentKeyID: 62200063
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set prices in a channel 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to use price groups to easily manage the prices of products in specific channels, such as the retail stores in particular cities.

To set prices in a channel, complete the following tasks in this order:

1.  Create a price group

2.  Link the price group to a channel

3.  Create trade agreements

4.  Send the changes to the channel

## Create a price group

1.  Click **Retail** \> **Setup** \> **Pricing and discounts** \> **Price groups**.

2.  In the **Price groups** form, click **New** to create a price group.

3.  In the **Price groups** field, enter an identification code, and then in the **Name** field, enter a descriptive name for the price group.

4.  Select the **Retail** check box.

5.  Close the **Price groups** form.

## Link the price group to a channel

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  On the **Retail stores** list page, select a store, and then click **Edit**.

3.  In the **Stores** form, on the **Action Pane**, in the **Pricing** group, click **Price groups**.

4.  In the **Retail channel price groups** form, click **New**, and then in the **Price group** field, select the price group that you created in the previous procedure.

5.  Close the **Retail channel price groups** form.

## Create trade agreements

1.  Click **Sales and marketing** \> **Journals** \> **Price/discount agreement journals**.

2.  In the **Price/discount agreement journals** form, click **New** to create a journal.

3.  In the **Name** field, select a journal type.

4.  On the **General** tab, set the **Default relation** field to **Price (sales)**.

5.  Click **Lines**.

6.  In the **Journal lines, price/discount agreement** form, press Ctrl+N to add a line, and then in the **Relation** field, select **Price (sales)**.

7.  In the **Account code** field, select **Group**.

8.  In the **Account selection** field, select the price group that you created in the first procedure.

9.  In the **Item code** field, select **Table**.

10. In the **Item relation** field, select the product whose price you want to change.

11. If the product is a variant, select the appropriate values in the **Configuration**, **Size**, **Color**, and **Style** fields.

12. In the **Amount in currency** field, enter the new price.

13. Select the **Find next** check box.

14. Click **Post**.

15. After the journal is posted, close the **Price/discount agreement journals** form.

## Send the changes to the channel

1.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

2.  In the **Distribution schedule** form, for each of following jobs, select the job in the list. Then click **Run now** or, to run the job later, click **Create batch job**.
    
      - **1020** – **Discount**
    
      - **1040** – **Products, prices, and bar codes**
    
      - **1070** – **Channels and tenders**

3.  Close the **Distribution schedule** form.

## See also

[About setting prices by using price groups](about-setting-prices-by-using-price-groups.md)

  


