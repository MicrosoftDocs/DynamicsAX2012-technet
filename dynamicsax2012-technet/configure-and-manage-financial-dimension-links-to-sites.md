---
title: Configure and manage financial dimension links to sites
TOCTitle: Configure and manage financial dimension links to sites
ms:assetid: 721cdfc8-1102-4bf9-b6e5-076599b1b766
ms:mtpsurl: https://technet.microsoft.com/library/Gg231846(v=AX.60)
ms:contentKeyID: 44080993
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure and manage financial dimension links to sites 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you set up a link between a financial dimension and the site inventory dimension, your legal entity can calculate profit and loss figures for each site. Use the following procedures to configure and manage financial dimension links for sites:

  - Set up a financial dimension link to a site

  - Activate the financial dimension link

  - Lock the financial dimension link

  - Unlock the financial dimension link

  - Deactivate the financial dimension link

## Set up a financial dimension link to a site

When you set up a financial dimension link to a site, the following occurs:

  - A financial dimension is associated with the site inventory dimension.

  - A financial dimension value is associated with each site.

<!-- end list -->

1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Dimension link**.

2.  In the **Reference** field, select the financial dimension to link to the site inventory dimension.

3.  Click **Sites** to open the **Sites** form. The financial dimension that you selected in the previous step is displayed on the **Financial dimensions** FastTab, where you can also select a financial dimension value for the dimension.

4.  Select a site. On the **Financial dimensions** FastTab, select a financial dimension value. The specified financial dimension value is associated with the selected site.
    
    Repeat this step for each site.

## Activate the financial dimension link

When you activate the financial dimension link, the following occurs:

  - When new transactions are created that use both inventory dimensions and financial dimensions, the dimension value that is specified for the site is used as the dimension value for the linked financial dimension.

  - You can post transactions that use both inventory dimensions and financial dimensions, even if the dimension value for the linked financial dimension does not match the value that is specified for the site.

  - On open transactions that use both inventory dimensions and financial dimensions, you can change the dimension value for the linked financial dimension.


> [!NOTE]
> <P>You must assign a financial dimension value to each site before you can complete this procedure.</P>



1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Dimension link**.

2.  Click **Activate link**.

3.  Click **Yes**.
    
    The **Current status:** field displays that the financial dimension link is active, and the color of the button is yellow. The **Reference** field is not available.

## Lock the financial dimension link

When you lock the financial dimension link, the following occurs:

  - New inventory transactions that use both inventory dimensions and financial dimensions are assigned a financial dimension value that is based on the value that is specified for the site.

  - You can post transactions that use both inventory dimensions and financial dimensions only when the dimension value of the linked financial dimension value matches the value that is specified for the site.

  - You cannot change the dimension value of the linked financial dimension on transactions that use both inventory dimensions and financial dimensions.

  - You cannot modify the financial dimension value that is associated with a site.

You must set up a financial dimension link before you can lock the link.

1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Dimension link**.

2.  Click **Lock link**. The **Linked dimension update** form is displayed.

3.  Click **OK**. All open transactions are updated accordingly.
    
    The **Current status:** field displays that the financial dimension link is locked, and the color of the button is green.

## Unlock the financial dimension link

After a financial dimension link is locked, you can unlock it. When it is unlocked, you can complete these tasks:

  - Post transactions that use both inventory dimensions and financial dimensions, even if the dimension value of the linked financial dimension does not match the value that is specified for the site.

  - Modify the dimension value of the linked financial dimension on open transactions that use both financial dimensions and inventory dimensions.

  - Modify the financial dimension values that are set up in the **Sites** form.

<!-- end list -->

1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Dimension link**.

2.  Click **Unlock link**.
    
    The **Current status:** field displays that the financial dimension link is active, and the color of the button is yellow.

## Deactivate the financial dimension link

When you deactivate a financial dimension link, the following occurs:

  - The link between the site inventory dimension and the financial dimension is removed.

  - The linked financial dimension is not assigned the dimension value that is specified for the site inventory dimension.

  - You can select a different financial dimension to link to the site inventory dimension.

<!-- end list -->

1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Dimension link**.

2.  Click **Deactivate link**.
    
    The **Current status:** field displays that the financial dimension link is inactive, and the color of the button is red.

## See also

[Dimension link (form)](https://technet.microsoft.com/library/hh209629\(v=ax.60\))

[Sites (form)](https://technet.microsoft.com/library/hh242661\(v=ax.60\))

  


