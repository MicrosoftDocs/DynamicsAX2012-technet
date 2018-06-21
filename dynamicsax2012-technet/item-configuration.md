---
title: Item configuration
TOCTitle: Item configuration
ms:assetid: 45b5a5e2-5962-4806-9185-97dc4bc24b5d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496983(v=AX.60)
ms:contentKeyID: 36056897
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- product builder
- item configuration - product builder
---

# Item configuration [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you create a sales order, sales quotation, purchase order, production order, project quotation, or item requirement for a modeling-enabled item, you can start the configuration process. For sales and purchase orders and quotations, click **Configure line**. For production orders, click **Configure production**. For item requirements, click **Functions** \> **Configure line**.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



## Configuring the item

When you start the configuration process, the configuration user dialog box is created, based on the product model’s setup of modeling variables and validation rules. In the user dialog box, enter the required configuration data for the product that you are configuring. Click **OK** to let the product model pass through the modeling tree and generate a BOM and route for the configured item. The product model attaches a BOM ID and a route ID to the order line, quotation line, or item requirement line.

By default, when you start the configuration of an item by clicking **Configure line**, the product model that is currently active for the item is used for the configuration. The active product model is specified on the **Versions** pane of the **Product model details** form. However, you can specify a different product model for the order line or quotation line on the **Other** tab.

The structure of a product model’s user dialog box is determined by the setup of the modeling variables and variable groups. Each variable group is displayed as a tab. If a variable group has subgroups, each subgroup is displayed as a field group on the tab for the top-level group. If you display the user dialog box as a tree structure, the groups appear as nodes, and the subgroups appear as subnodes.

## Automatic and mandatory configuration

The user dialog box appears automatically after you enter the configurable item numbers on the order lines or quotation lines, and then save the record. You do not have to click **Configure line**. This user dialog box can be set to open automatically and is item controlled. It can be set up by selecting the **Autostart configuration** check box on the **General** tab of the **Released products** form.

You can set up the system to start the configuration automatically when you click **Configure line**. Select the **Hide dialog box** check box on the **General** tab of the **Released products** form. If the system starts the configuration automatically, all default settings are applied.

You can skip the approval dialog box by selecting the **Hide approval dialog** check box on the **General** tab of the **Released products** form. If you skip the approval dialog box, you make all of the required choices in the user dialog box. However, the configuration approval, and the calculation of the sales price and delivery date are performed automatically.

To calculate only the price or delivery date automatically, select the **Automatic price calculation** check box or the **Automatic calculation of delivery date** check box on the **Approval** tab of the **Product builder parameters** form.

You can also make the configuration of modeling-enabled items on order lines or quotation lines mandatory. This mandatory configuration is also item-controlled. To set up the mandatory configuration, select the **Mandatory configuration** check box on the **General** tab of the **Released products** form.

## See also

[About configurable items](about-configurable-items.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

