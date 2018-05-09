---
title: (RUS) Set up a fixed asset location
TOCTitle: (RUS) Set up a fixed asset location
ms:assetid: 8002a829-c7b8-43a2-9108-091fbec1ee1a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678412(v=AX.60)
ms:contentKeyID: 49387642
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a fixed asset location 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **FA location** form to set up a fixed asset location and specify the company division that the asset belongs to.

Locations are defined for fixed assets to calculate depreciation accrual. Depending on the fixed asset location, the calculated depreciation amount is allocated to the production cost of the product or to a ledger account.

You must define the location of the fixed asset before you acquire the fixed asset. If you are transferring a fixed asset from one location to another, you can create a transfer transaction to register the transfer of the asset..

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Location**.

2.  Click **New** to create a fixed asset location.

3.  In the **Location** and **Name** fields, enter a location code and a description for the location.

4.  In the **Separate division ID** field, select a separate division if the fixed asset is not located at the head office of the company. If you do not specify a separate division, the location of the fixed asset is the head office.

5.  Click the **Fixed asset posting profiles** FastTab.

6.  Create a line.

7.  In the **Groupings** field, select the grouping for the fixed asset posting profile from one of the following options:
    
      - **Table** – The posting profile is grouped by the selected fixed asset.
    
      - **Group** – The posting profile is grouped by the depreciation group.
    
      - **All** – The posting profile is grouped by all fixed assets.
    
      - **Accounting** – The posting profile is grouped by the value model.

8.  In the **Account/Group number** field, select the depreciation group, fixed asset, or value model that the posting profile is used for.

9.  In the **Main account** field, select a ledger account to use to post the fixed asset transactions.

10. In the **Account for depr.bonus** field, select a ledger account to use to post the depreciation bonus for the fixed asset, if a depreciation bonus applies.

## See also

[(RUS) FA location (form)](https://technet.microsoft.com/en-us/library/jj733271\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

