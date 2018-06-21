---
title: Set prices in a catalog
TOCTitle: Set prices in a catalog
ms:assetid: 7aa79e99-7ad7-4bad-9be9-6577bdde0c61
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497791(v=AX.60)
ms:contentKeyID: 62200102
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# Set prices in a catalog [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to manage the prices of retail products in catalogs by using price groups. The price group links the catalog and its products with the trade agreements that specify prices. This is especially useful if your company publishes many catalogs and uses many price changes.

To set prices in a catalog, complete the following tasks in this order:

1.  Create a price group

2.  Link the price group to a catalog

3.  Create trade agreements

4.  Send the changes to the stores

## Create a price group

1.  Click **Retail** \> **Setup** \> **Pricing and discounts** \> **Price groups**.

2.  In the **Price groups** form, click **New** to create a new price group.

3.  Enter an identification code, and a descriptive name for the price group.

4.  Select the **Retail** check box to identify the price group as an exclusively retail price group.

5.  Close the **Price groups** form.

## Link the price group to a catalog

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**.

2.  In the **Catalogs** list page, select a catalog, and then click **Edit**.

3.  In the **Catalogs** form, on the **Action Pane**, in the **Pricelist** group, click **Price groups**.

4.  In the **Catalog price groups** form, click **Add**, and then in the **Price group** field, select the price group that you created in step 1.

5.  Close the **Catalog price groups** form.

6.  In the **Catalogs** form, on the **Action Pane**, in the **Publish** group, click **Validate catalog**.

7.  In the **Validate catalog** form, click **Validate catalog**, and then close the form.

8.  In the **Catalogs** form, in the workflow message bar, click **Submit**.

9.  Close the **Catalogs** form.

## Create trade agreements

1.  Click **Sales and marketing** \> **Journals** \> **Price/discount agreement journals**.

2.  In the **Price/discount agreement journals** form, click **New** to create a journal.

3.  In the **Name** field, select a journal type.

4.  On the **General** tab, set the **Default relation** to **Price (sales)**.

5.  Click **Lines**.

6.  In the **Journal lines, price/discount agreement** form, press **Ctrl+N** to add a new line, and then in the **Relation** field, select **Price (sales)**.

7.  In the **Account code** field, select **Group**.

8.  In the **Account selection** field, select the price group that you created in step 1.

9.  In the **Item code** field, select **Table**.

10. In the **Item relation** field, select the product that has a price that you want to change.

11. If the product is a variant, select the appropriate values in the **Configuration**, **Size**, **Color**, and **Style** fields.

12. In the **Amount in currency** field, enter the new price.

13. Repeat steps 6 through 12 for each product that has a price that you want to set.

14. Select the **Find next** check box.

15. Click **Post**.

16. After the journal posts, close the **Price/discount agreement journals** form.

## Send the changes to the stores

1.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

2.  In the **Distribution schedule** form, select **1040** – **Products, prices, and bar codes**.

3.  Click **Run now**, or to run the job later, click **Create batch job**.

4.  Select **1020** - **Discount**.

5.  Click **Run now**, or to run the job later, click **Create batch job**.

6.  Close the **Distribution schedule** form.

## See also

[About setting prices by using price groups](about-setting-prices-by-using-price-groups.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

