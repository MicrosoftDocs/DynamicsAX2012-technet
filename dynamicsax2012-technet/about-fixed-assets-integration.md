---
title: About fixed assets integration
TOCTitle: About fixed assets integration
ms:assetid: 7b41e403-ced1-4504-af92-f2bdd20cd17b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550078(v=AX.60)
ms:contentKeyID: 44080996
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About fixed assets integration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fixed assets can be integrated with General ledger, Inventory management, Accounts receivable, and Accounts payable. You can also set up Fixed assets so that it is integrated with purchase orders.

## General ledger

In General ledger, the value of all fixed assets is usually summarized in multiple main accounts that are required for financial reporting. However, in the **Fixed assets** form, you can create many fixed asset records. These records can include information such as the acquisition price, depreciation, and valuation. Each time that you post a transaction for a fixed asset, the appropriate main accounts are updated. The main accounts for fixed assets always show the updated value of the fixed assets.

In the **Fixed asset posting profiles** form, you define the main accounts that fixed asset value model transactions are posted to. You also specify the types of fixed asset transactions that are posted to each main account. You can create various combinations of main accounts for fixed assets, depending on the level of detail that you want for fixed assets in the general ledger. Main accounts can be based on transaction types, value models, and other main accounts.

Depreciation books do not affect the general ledger. They are used only to report taxes and other assets.

## Inventory management

In the inventory journal for fixed assets, you can enter the acquisition of fixed assets that the legal entity has produced or constructed for itself. You can then transfer inventory items to fixed assets either as an acquisition or as part of an acquisition.

You can also acquire assets by using purchase orders. When purchase orders contain inventory items that are designated as fixed assets, the setting of the **Allow asset acquisition from Purchasing** check box in the **Fixed assets parameters** form determines whether an acquisition is posted for the fixed asset when the invoice is posted. The effect that the acquisition of fixed assets has on inventory depends on the setup of the legal entity.

When an inventory item becomes a fixed asset acquisition through the inventory journal, a purchase order, or an acquisition proposal, a fixed asset value model acquisition transaction is created. If a value model acquisition includes a derived depreciation book, a depreciation book acquisition transaction is also created.

The decrease in inventory when an acquisition is posted is controlled by the posting rules that are set up in the **Posting** form in Inventory management. However, you do not always decrease inventory when you post invoices that are related to fixed assets. In some cases, the fixed assets might be purchased for internal use, such as a laptop that is purchased for the sales department. When you work with purchase orders, you can use items that are set up for both resale and internal use.

If you use specific receipt and issue accounts on item groups for fixed assets, you can use the same inventory item both for internal purchases and as stock for resale.

Fixed assets that are for internal use are set up so that they have a **Fixed asset receipt** account type. This account type is used to track the receipt of the fixed asset. When you post a vendor invoice, use the fixed asset receipt account if any of the following conditions is true:

  - The invoice line contains an existing fixed asset for internal purposes.

  - The **New fixed asset?** check box is selected for the product receipt line that is posted.

  - The **Create a new fixed asset** check box is selected for the vendor invoice line.

This account is typically an expense account. You can set up the **Fixed asset receipt** account type for either an item group or an individual item by using the **Purchase order** tab in the **Item group** or **Posting** forms.

Similarly, fixed assets that are for internal use can be set up so that they have a **Fixed asset issue** account type. This account type is used to track the issuing of the fixed asset to the recipient. When an asset is acquired by using a purchase order, the fixed asset issue account offsets the fixed asset debit account. The asset acquisition can be posted either when you post a vendor invoice, or when you post the asset acquisition in the **Fixed assets** journal, possibly by using an acquisition proposal. You can set up the **Fixed asset issue** account type for either an item group or an individual item by using the **Inventory** tab in the **Item group** or **Item posting** form.

Ultimately, the main accounts that are used for posting are determined by the options for ledger integration that are specified for the item model group. Additionally, the main accounts that are used vary, depending on whether an asset is assigned to the purchase order line. The accounts are derived from the posting profile for each item group.


> [!NOTE]
> <P>If an inventory reservation exists when product receipts are posted, you cannot assign a fixed asset or create a fixed asset from the line.</P>



The accounts that fixed asset transactions are posted to depend on whether the assets are purchased or constructed by the legal entity, and on the transaction type of the asset.

The transaction type connects the inventory transaction to the posting profile in Fixed assets. Because the posting profile in Fixed assets defines which accounts are updated, the selection of a transaction type for a fixed asset is also, indirectly, the selection of the main accounts that the transaction is posted to. For both constructed and purchased fixed assets, the transaction type is usually **Acquisition** or **Acquisition adjustment**.

## Accounts receivable

The integration of Fixed assets with Accounts receivable uses posting profiles that are set up in Fixed assets. These posting profiles are activated when a fixed asset, value model, and fixed asset transaction type are selected for a customer invoice before the customer invoice is posted. Because fixed assets are not part of Inventory management, you must use the **Free text invoice** form when you sell a fixed asset.

If the value model includes a derived depreciation book, a depreciation book transaction is created when you post the customer invoice.

## Accounts payable

Fixed assets are usually acquired from external vendors. You can use the **Fixed assets parameters** form to specify whether asset acquisitions are always posted when you post vendor invoices, or whether asset acquisitions can be posted only from Fixed assets. If you allow asset acquisitions to be posted from Accounts payable, fixed asset accounts are updated whenever a vendor invoice for a fixed asset acquisition is posted.

If the system is set up to post an asset acquisition when an invoice is posted, the transaction is posted according to the posting profiles that are set up in Fixed assets for the various fixed asset transaction types. The posting is controlled by the fixed asset, value model, and fixed asset transaction type that are selected in the **Purchase order** form before the vendor invoice is posted.

If the value model includes a derived depreciation book, a depreciation book transaction is created when you post the vendor invoice.

The integration for each order line is activated on the **Fixed assets** tab on the **Line details** FastTab in the **Purchase order** form. You can send a purchase order for a fixed asset to the vendor. However, the fixed assets and main accounts are updated only when you post the vendor invoice after the fixed asset is received. Because purchase orders can contain only inventory items, the effect that the acquisition of fixed assets has on inventory depends on the setup of the legal entity.

## Project management and accounting

You can associate a project with an asset that is affected by the project. You can also associate each phase, task, or subproject to a different asset. One asset can be associated with each project record. You create the association when you enter a fixed asset number in the **Fixed asset number** field in the **Projects** form. (Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a project ID that has a project type of **Internal** or **Cost project**, and then click **Edit**.)

You can also use the **Projects** form to view details about assets that are associated with projects. To view the fixed asset record, click the asset link on the **Setup** FastTab to open the **Fixed assets** form. Then click **Projects** \> **All projects** to view the projects that are associated with the fixed asset.

You typically associate fixed assets with projects when the projects are related to work, maintenance, or improvements for the asset. When the project is completed, a write-up adjustment for the asset is not created automatically. Therefore, you must create the write-up adjustment manually, if a write-up adjustment is required.

To delete the association between a project and an asset, clear the **Fixed asset number** field in the **Projects** form.

You can also designate a fixed asset that you are creating or manufacturing as part of an estimate project. At the end of an estimate project, you can automatically post an asset acquisition transaction.

## See also

[About options for entering fixed asset transactions](about-options-for-entering-fixed-asset-transactions.md)

[Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\))

[Set up Fixed assets and Accounts payable integration](set-up-fixed-assets-and-accounts-payable-integration.md)

[About assets acquired through procurement](about-assets-acquired-through-procurement.md)

[Item posting (form)](https://technet.microsoft.com/en-us/library/aa589971\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

