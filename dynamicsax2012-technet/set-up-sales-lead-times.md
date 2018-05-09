---
title: Set up sales lead times
TOCTitle: Set up sales lead times
ms:assetid: e2b4149a-01ad-4ff8-9861-be9cc15849cc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243215(v=AX.60)
ms:contentKeyID: 36688022
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up sales lead times 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the following procedures to set up sales order lead times.

## Set up a default sales order lead time

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click the **Shipments** tab.

3.  In the **Sales lead time** field, specify the default lead time for sales orders in number of days. The lead time is applied to the sales order header.

4.  Close the form to save your changes.

## Set up a sales order lead time for an item

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Double-click the item that you want to set up a sales order lead time for.

3.  In the **Released products** form, click **Manage inventory** \> **Default order settings** to open the **Default order settings** form.

4.  Click the **Sales order** tab, and then select the **Override sales lead time** check box to override the sales lead time specified in the **Accounts receivable parameters** form.

5.  In the **Sales lead time** field, specify the sales order lead time in number of days. The lead time is applied to a specific item.

6.  Close the forms to save your changes.

## Set up site specific sales order lead times

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Double-click the item that you want to set up a site specific sales order lead time for.

3.  In the **Released products** form, click **Manage inventory** \> **Site specific order settings** to open the **Site specific order settings** form.

4.  Click the **Sales order** tab, and then select the **Override** check box.

5.  In the **Sales lead time** field, specify the sales order lead time in number of days. The lead time is applied to a specific site.

6.  Close the forms to save your changes.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

