---
title: About item groups
TOCTitle: About item groups
ms:assetid: cf09aa0e-02f1-42c0-81f8-08fe6f123ec3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa572815(v=AX.60)
ms:contentKeyID: 45437262
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About item groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up item groups in Inventory management by using the **Item groups** form. (Click **Inventory management** \> **Setup** \> **Inventory** \> **Item groups**.)

## Using item groups

Item groups are used to manage inventory by dividing inventory items into groups. You can complete the following tasks for the items that are included in an item group:

  - Follow statistics for item sales, item purchases, and projected inventory transactions and balances.

  - Set up a posting profile for a group of items that require a posting setup other than the standard posting profile that is set up for items in the **Posting** form.
    
    Transactions for items that use the standard posting profile are posted to inventory issue and receipt accounts that are set up in the **Posting** form. (Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**. On the **Inventory** tab, click **Issue** and **Receipt** to set up the accounts.)


> [!IMPORTANT]
> <P>We recommend that you consider the structure of item groups carefully before you complete the setup of item groups, and before you select the item groups for product definitions. An item group that is associated with a product definition cannot be deleted. For more information about product definitions, see <A href="key-tasks-define-products.md">Key tasks: Define products</A>.</P>



To manage how information is posted to main accounts, you can create a series of different item groups that are associated with specific main accounts. This lets you track the floating physical inventory value of items at different stages. A physical cost amount that has not been financially updated in the general ledger is a floating value. An example of a floating value is an item that is being manufactured, or that was physically received and updated on a packing slip, but that has not been invoiced. This means that the final value of the item is not yet known.

## Posting setup on item groups

Each FastTab in the **Item groups** form lists a series of account types that must be related to main accounts in the general ledger. Accounts for sales, purchases, inventory, and production can be set up in detail, according to your legal entity’s needs.

The setup of main accounts is used to allocate the ledger transactions for receipts and issues that are generated in Inventory management.

## See also

[Item posting (form)](https://technet.microsoft.com/en-us/library/aa589971\(v=ax.60\))

[About fixed assets integration](about-fixed-assets-integration.md)

  


