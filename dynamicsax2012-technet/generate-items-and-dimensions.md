---
title: Generate items and dimensions
TOCTitle: Generate items and dimensions
ms:assetid: d0cbd4c1-1628-4f7b-969e-3ba6356d0c85
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551012(v=AX.60)
ms:contentKeyID: 36059491
ms.date: 06/13/2017
mtps_version: v=AX.60
f1_keywords:
- product builder
- product builder dimensions
- product builder items
---

# Generate items and dimensions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

For some types of production, it might be convenient to save each configured item under a separate item number so that it is stored in the **Released product details** form, along with its configured BOM and route.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Double-click a product model.

3.  Click **Setup** \> **Generate items and dimensions**.

4.  On the **General** tab page in the **Activate** field group, select **Generate item number**, **Generate size**, or **Generate color** to specify that a new item number, color identification, or size identification must be generated whenever an item is configured.

5.  For each selected check box, you can specify how the new item number, color identification, or size identification will be generated in the associated **Format** field group fields.
    
    If you do not to enter anything in these fields, the identification is set to the next number in the attached number sequence. Use % in the format field, followed by a number, to refer to any one of the variables that you select on the **General**, **Size variables**, or **Color variables** tab pages.
    

    > [!NOTE]
    > <P>These tab pages appear after you select the appropriate check boxes.</P>

    
    The variables are numbered in the order that they appear in on the relevant tab page. Any variable of the types **Modeling variables**, **Variable**, **Simple**, or **Data type** can be used. To avoid generating the same item number for two different item configurations, the formatted item number will always be extended with a number from the attached number sequence.

## See also

[Product models (form)](https://technet.microsoft.com/en-us/library/aa572853\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

