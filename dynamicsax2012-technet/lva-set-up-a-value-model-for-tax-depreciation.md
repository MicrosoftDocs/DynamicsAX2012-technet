---
title: (LVA) Set up a value model for tax depreciation
TOCTitle: (LVA) Set up a value model for tax depreciation
ms:assetid: 2b8694d9-403f-42f2-8910-72a0e453b780
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ910992(v=AX.60)
ms:contentKeyID: 52075316
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- value model
- tax depreciation for Latvia
---

# (LVA) Set up a value model for tax depreciation [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

1.  Click **Fixed assets** \> **Setup** \> **Value models**.

2.  Press CTRL+N to create a new value model, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/en-us/library/aa582567(v=ax.60)">Value models setup (form)</A>.</P>



3.  Select the **Summarize for category** check box to calculate depreciation of all fixed assets that are attached to the value model as a group, instead of as individual assets.
    
    Value models are referred to as categories.
    

    > [!NOTE]
    > <P>The <STRONG>Summarize for category</STRONG> check box must be selected for periodic depreciation to be calculated for a value model.</P>



4.  In the **Posting layer** field, select **Tax**.

5.  On the **Tax coefficients** FastTab, select **New** to create a new tax coefficient that is used to adjust the acquisition amount of the fixed asset.

6.  In the **Starting year** field, enter the starting year.

7.  In the **Tax depreciation coefficient** field, enter the coefficient to adjust the acquisition value of the fixed asset.

## See also

[(LVA) Assign tax categories to fixed assets](lva-assign-tax-categories-to-fixed-assets.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

