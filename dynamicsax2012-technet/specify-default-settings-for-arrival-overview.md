---
title: Specify default settings for arrival overview
TOCTitle: Specify default settings for arrival overview
ms:assetid: bf1616c4-9756-40de-9838-80119c24d2d6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213625(v=AX.60)
ms:contentKeyID: 36059254
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- arrival overview
- arrival overview setup
- set up arrival overview
- arrival overview defaults
---

# Specify default settings for arrival overview [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

When items arrive in the inbound dock, the **Arrival overview** form is used to match the information accompanying the items with the information in Microsoft Dynamics AX. The settings can be saved per user and per computer so that users can have their personal settings on each computer that is located in the inbound dock. One user can have multiple setups.

For example, a user could customize to filter on the current warehouse or on all receipts expected today.

A few example customizations are included. In the **Setup name** field in the **Display options** area, you can select **Today** to filter on receipts expected today; **Inquiry** is intended to be an inspiration to filter on whatever options are relevant in the situation; **Options used** is a default that cannot be overwritten or deleted.

1.  Click **Inventory management** \> **Periodic** \> **Arrival overview**.

2.  On the **Setup** tab define settings for:
    
      - Arrival journals − The journal name to use and which warehouse and location to register receipts. A journal name must be specified. If a warehouse and location are not specified, the information about the lines is used.
    
      - Data updates – If the form should update automatically when it is opened, select the **Update on startup** check box. If updates should be automatic when values are changed for **Range** on the **Overview** tab, select the **Update on range change** check box.
    
      - Transaction types display – Under **Transaction types shown**, select the transaction types to show in the list of receipts.

For more information about the options in the form, see [Arrival overview (form)](https://technet.microsoft.com/en-us/library/hh227654\(v=ax.60\)).

Settings in **Setup** tab and **Range** settings on the **Overview** tab are saved as default settings under **Options used** when you close the form. To save the settings under a different name, click the **Modify...** button on the **Setup** tab, and then click **Save**.

## See also

[Using inventory journals](using-inventory-journals.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

