---
title: Create a formula and formula version
TOCTitle: Create a formula and formula version
ms:assetid: 2c2e3b3d-f087-453e-a74b-413fdbcb2f2f
ms:mtpsurl: https://technet.microsoft.com/library/Hh352191(v=AX.60)
ms:contentKeyID: 36687824
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a formula and formula version 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you create a new formula, it can have one or many versions. Each formula version has an effective date range to control the validity period for that version. Each formula also has a **From quantity** field. If a formula has multiple versions, the effective date ranges and from quantities cannot overlap.

## Create a formula and formula version

1.  Click **Inventory and warehouse management** \> **Common** \> **Formula**.

2.  Press CTRL+N to create a new formula.

3.  Enter information to identify the formula.

4.  Enter the site information.

5.  In the **Versions** grid, select the item number for this formula version:
    
    1.  Enter dates in the **From date** and **To date** fields to control the validity period of the formula version.
    
    2.  Set a minimum item quantity for using the formula version in the **From formula size** field. If the item is a catch weight item, enter the minimum item quantity in the **From CW size** field.
    
    3.  Once the first version is saved, the **Lines** button and **Co-products** button are available.

6.  Click **Lines** to open the **Formula line** form. Add the individual lines for any component items that make up the formula, and then close the form.

7.  Optionally click the **Co-products** button and add any co-products or by-products being produced.

8.  Click **Approve formula** to open the **Approve BOM or formula** form.

9.  Select the approving employee, and then click **OK**.

10. In the **Versions** grid, click **Approve** to open the **Approve version** form. Select the approving employee, and then click **OK**.

11. Click **Activation** to make the formula version active.

## Create a different version of the formula

1.  To create a different version of the same formula, press CTRL+N in the **Versions** grid to create a new line.

2.  Select the item number for the new formula version.

3.  Enter dates in the **From date** and **To date** fields to control the validity period for this version. This effective date range cannot overlap the date range for any existing version of this formula.

4.  In the **From formula size** field, enter the minimum item quantity for using this formula version. If the item is a catch weight item, enter the minimum item quantity in the **From CW size** field.

5.  Click **Approve** to approve the formula version.

6.  Click **Activation** to make this formula version active.

## See also

[About formulas](about-formulas.md)

[Approve BOM or formula (class form)](https://technet.microsoft.com/library/hh227377\(v=ax.60\))

[(PM) Approve formula version (class form)](https://technet.microsoft.com/library/hh242740\(v=ax.60\))

[Formula (form)](https://technet.microsoft.com/library/hh328668\(v=ax.60\))

[Formula line (form)](https://technet.microsoft.com/library/hh352331\(v=ax.60\))

  


