---
title: Create multiple versions of a formula
TOCTitle: Create multiple versions of a formula
ms:assetid: 196e4654-f5db-4da3-b767-734cb2f19f6a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352186(v=AX.60)
ms:contentKeyID: 36687819
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create multiple versions of a formula 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create different versions of a formula. Each formula version has an effective date range to control the validity period for that version. If a formula has multiple versions, the effective date ranges cannot overlap.

1.  Click **Inventory and warehouse management** \> **Common** \> **Formula**.

2.  Select the formula for which you want to create a new version.

3.  In the **Versions** grid, press CTRL+N to add a new formula version.

4.  In the **Item number** field, select the item number for this formula version.

5.  Enter dates in the **From date** and **To date** fields to control the validity period of the formula version. This effective date range cannot overlap the date range for any existing version of this formula.

6.  In the **From formula size** field, enter the minimum item quantity for using this formula version. If the item is a catch weight item, enter the minimum item quantity in the **From CW size** field.

7.  Click **Approve** to open the **Approve version** form.

8.  Click **Activation** to make this formula version active.

## See also

[About formulas](about-formulas.md)

[(PM) Approve formula version (class form)](https://technet.microsoft.com/en-us/library/hh242740\(v=ax.60\))

[Formula (form)](https://technet.microsoft.com/en-us/library/hh328668\(v=ax.60\))

  


