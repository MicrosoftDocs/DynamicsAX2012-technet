---
title: (THA, SAU, GBR, IRL) Create an item withholding tax group and attach a withholding tax code
TOCTitle: (THA, SAU, GBR, IRL) Create an item withholding tax group and attach a withholding tax code
ms:assetid: 867a8f50-68c6-4585-a045-2ffef953d5be
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209327(v=AX.60)
ms:contentKeyID: 36058416
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Thailand
- withholding tax group
---

# (THA, SAU, GBR, IRL) Create an item withholding tax group and attach a withholding tax code 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Item withholding tax groups** form to create an item withholding tax group. You can attach one or more withholding tax codes to an item withholding tax group and attach multiple withholding tax rates to accommodate partial payment transactions. You can also attach a withholding tax group to an item group or item.

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Item withholding tax groups**.

2.  Press CTRL+N to create a new item withholding tax group.

3.  In the **Item withholding tax group** field, enter an identification code for the item withholding tax group.

4.  In the **Description** field, enter a description for the group.

5.  In the **Withholding tax revenue type** field, select the revenue type for the item withholding tax group.

6.  Click the **Setup** tab, and then in the **Withholding tax code** field, select the withholding tax code for the item withholding tax group.
    

    > [!NOTE]
    > <P>You can attach more than one withholding tax code to an item withholding tax group.</P>



7.  Close the form.

8.  Click **Product information management** \> **Common** \> **Released products**.

9.  Click **Edit** to open the **Released product details** form.

10. Click the **Purchase** FastTab, and then in the **Item sales tax group** field, select the item withholding tax group for the item.

11. Close the form.

## See also

[(THA, SAU, GBR, IRL) Item withholding tax groups (form)](https://technet.microsoft.com/en-us/library/hh242862\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

