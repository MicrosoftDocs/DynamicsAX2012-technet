---
title: Set up Fixed assets and Accounts payable integration
TOCTitle: Set up Fixed assets and Accounts payable integration
ms:assetid: f7b9764b-275f-4a33-a55f-f931db49c664
ms:mtpsurl: https://technet.microsoft.com/library/Gg243296(v=AX.60)
ms:contentKeyID: 36060041
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accounts payable and FA
- accounts payable integration
- AP and FA
- accounts payable and fixed assets
- AP and fixed assets
- fixed assets and AP
- fixed assets and accounts payable
- FA and accounts payable
- fixed asset integration
- FA and AP
audience: Application User
ms.search.region: Global
---

# Set up Fixed assets and Accounts payable integration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following methods are available for integrating Fixed assets and Accounts payable. When you select a method, you must use that same method for all fixed assets.

  - You manually create a fixed asset before you add the fixed asset number to the line on the purchase order or invoice. An acquisition transaction automatically is posted for the asset when you post the invoice. This is the default method.

  - You manually create a fixed asset before you add the fixed asset number to the line on the purchase order or invoice. No acquisition transaction is posted for the asset when you post the invoice.

  - A new fixed asset automatically is created when you post a product receipt or invoice that has the **Create asset during product receipt or invoice posting** check box selected in the **Fixed assets parameters** form. An acquisition transaction automatically is posted for the asset when you post the invoice.

  - A new fixed asset automatically is created when you post a product receipt or invoice that has the **Create asset during product receipt or invoice posting** check box selected in the **Fixed assets parameters** form. However, an acquisition transaction is not posted for the asset when you post the invoice.

For more information, see [About assets acquired through procurement](about-assets-acquired-through-procurement.md).

This topic discusses how to set up all of the methods except the default method.

1.  Click **Fixed assets** \> **Setup** \> **Fixed assets parameters**.

2.  Click **Fixed assets** \> **Purchase orders** FastTab, and then specify the following options for fixed assets:
    
      - Select the **Allow asset acquisition from Purchasing** check box to post acquisition transactions when you post invoices that include a fixed asset number or a new fixed asset.
    
      - Optional: Select a group in the **Restrict asset acquisition posting to user group** list to specify the user group that can post acquisition transactions.
    
      - Select the **Create asset during product receipt or invoice posting** check box to create a new fixed asset record.

3.  Click **Inventory management** \> **Setup** \> **Inventory** \> **Item groups**.

4.  Select the item group to define fixed asset receipt and fixed asset issue accounts for. For example, you might select the Computers item group if you receive portable computers from a vendor that are for employee use.
    
    You can set up the same item with fixed asset receipt, fixed asset issue, receipt, and issue accounts. You might want to do this so that you can use the same item with fixed asset purchases for resale and fixed asset purchases for internal use. For more information, see [About fixed assets integration](about-fixed-assets-integration.md) and [About assets acquired through procurement](about-assets-acquired-through-procurement.md).

5.  On the **Purchase order** tab, in the **Fixed asset receipt** field, enter the account number to use for posting the receipt of items in this group. This account is updated when you post an invoice with a fixed asset assigned, and the system is set up not to post an acquisition transaction for the asset when you post the invoice.

6.  On the **Inventory** tab, in the **Fixed asset issue** field, enter the account number to use when you issue items in this group. This account is updated when the asset acquisition is posted, either through invoice posting or through an acquisition proposal.
    

    > [!NOTE]
    > <P>Instead of setting up the <STRONG>Fixed asset receipt</STRONG> and <STRONG>Fixed asset issue</STRONG> accounts by item group, you can set them up by individual item in the <STRONG>Item posting</STRONG> form.</P>



7.  Click **Posting**.

8.  In the **Item posting** form, use the **Purchase order** and **Inventory** tabs to verify that the accounts that you set up in item groups were copied correctly to this form, and that the setup is correct for the fixed asset receipt and fixed asset issue types.


> [!NOTE]
> <P>If you are using capitalization thresholds, when new fixed assets are created from Accounts payable, the <STRONG>Depreciation</STRONG> check box can be automatically selected or cleared in the value models and depreciation books, depending on whether the purchase amount meets the capitalization threshold. Capitalization thresholds are set up in the <STRONG>Fixed asset groups</STRONG> form. For more information, see <A href="about-assets-acquired-through-procurement.md">About assets acquired through procurement</A>.</P>



## See also

[About fixed assets integration](about-fixed-assets-integration.md)

[Item posting (form)](https://technet.microsoft.com/library/aa589971\(v=ax.60\))

[Fixed assets parameters (form)](https://technet.microsoft.com/library/hh242490\(v=ax.60\))

[Item group (form)](https://technet.microsoft.com/library/aa575515\(v=ax.60\))

[About assets acquired through procurement](about-assets-acquired-through-procurement.md)

[Process assets created from Accounts payable](process-assets-created-from-accounts-payable.md)

  


