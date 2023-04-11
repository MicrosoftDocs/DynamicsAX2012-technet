---
title: Set up sales tax overrides
TOCTitle: Set up sales tax overrides
ms:assetid: b6e85310-e435-4b81-af08-4cd2bf1feab6
ms:mtpsurl: https://technet.microsoft.com/library/Hh597219(v=AX.60)
ms:contentKeyID: 39519291
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up sales tax overrides 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You can set up sales tax overrides, so that cashiers can modify the amount of tax on a sales transaction. Sales tax overrides are useful in various scenarios. Consider the following examples:

  - Some customers, such as charitable organizations, children, and indigenous people, are subject to different tax rates.

  - Some items are subject to different tax rates under certain conditions. For example, food items that are consumed in the store are taxed differently than food items that are carried out of the store.

Each sales tax override specifies the sales tax group or item sales tax group that is overridden, and the sales tax group or item sales tax group that is used instead. Sales tax overrides are organized into sales tax override groups, so that several overrides can be available at each store.

Sales tax overrides are applied by cashiers. For example, the item sales tax group for an item includes a **Food** sales tax code, but the customer is exempt from taxes on food items. Therefore, the cashier overrides the item sales tax group by using an item sales tax group that does not include the **Food** sales tax code.

1.  Click **Retail** \> **Setup** \> **Sales taxes** \> **Sales tax overrides**.

2.  In the **Sales tax overrides** form, click **New** to create a new sales tax override.

3.  In the **Sales tax override** field, type a unique identifier for the override. Then, in the **Description** field, type a name for the override.

4.  In the **Status** field, select **Enable**.
    

    > [!NOTE]
    > <P>If you select <STRONG>Disable</STRONG> in the <STRONG>Status</STRONG> field, the override is not used when an override group that includes the override is applied to a transaction.</P>



5.  On the **Override** FastTab, in the **Type** field, select the type of sales tax code that is overridden at the point of sale.

6.  In the **From** field, select the tax group that is overridden at the point of sale. Then, in the **To** field, select the tax group that is used instead.

7.  In the **Override by** field, select whether the tax override is applied to the products on specific lines or to the whole transaction.

In addition to setting up sales tax overrides, you must complete the following tasks before you can use the sales tax overrides at the point of sale:

1.  Set up sales tax override groups.

2.  Select sales tax override groups for stores.

3.  Set up reason codes for sales tax overrides.

4.  Set permissions to allow specific cashiers to apply overrides.

## See also

[About setting up taxes](about-setting-up-taxes.md)

  


