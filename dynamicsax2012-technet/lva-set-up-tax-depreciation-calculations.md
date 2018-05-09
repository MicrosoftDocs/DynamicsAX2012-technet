---
title: (LVA) Set up tax depreciation calculations
TOCTitle: (LVA) Set up tax depreciation calculations
ms:assetid: b1955b4e-a716-44ce-8462-eee476820c98
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ911013(v=AX.60)
ms:contentKeyID: 52075324
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- tax depreciation
- tax depreciation for Latvia
- depreciation coefficients
---

# (LVA) Set up tax depreciation calculations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For annual income tax reporting in Latvia, tax depreciation is calculated for either an individual fixed assets or is based on summary information from all fixed assets that are assigned to the same fixed asset tax category.


> [!NOTE]
> <P>Value models are referred to as tax categories.</P>



## Set up fixed asset tax depreciation

The following tasks must be set up to calculate fixed asset tax depreciation:

1.  Click **Fixed assets** \> **Setup** \> **Depreciation** \> **Depreciation profiles**. Use the **Depreciation profiles** form to setup relevant depreciation profiles that are based on the depreciation percentages that are announced by tax authorities.
    
    Select **Reducing balance** in the **Method** field.
    
    For more information see, [(LVA) Set up a depreciation profile for tax depreciation](lva-set-up-a-depreciation-profile-for-tax-depreciation.md)

2.  Click **Fixed assets** \> **Setup** \> **Value models**. Use the **Value models** form to define a tax category.
    

    > [!NOTE]
    > <P>Value models are referred to as tax categories.</P>

    
    To create a value model (tax category), select the depreciation profile that has **Reducing balance** selected in the **Method** field in the **Depreciation profiles** form.

3.  Select **Tax** in the **Posting layer** field.

4.  Select the **Summarize for category** field if tax depreciation should be summarized and calculated for all fixed assets that have this value model selected in the **Category** field in the **Fixed assets** form.

5.  On the **Tax coefficients** FastTab, set up the tax coefficients for each coefficient that is announced by tax authorities to adjust the acquisition price for the fiscal year.

6.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**. Double-click a fixed asset or, on the **Action Pane**, click **Fixed asset** or **Edit**.
    
    On the **General** FastTab, select the value model in the **Category**.

## Calculate fixed asset tax depreciation

1.  Click **Fixed assets** \> **Periodic** \> **Tax depreciation**.

2.  Click **New** to create a tax period to use for reporting.

3.  Enter the period start date and end date.

4.  Select a period status.

5.  On the **Category details** FastTab, select the value model (category) in the **Category** field to calculate tax depreciation for.

6.  Click **Calculate** to calculate tax depreciation.
    
    To view the tax depreciation details, click **Tax depreciation details** to open the **Tax depreciation details** form.

7.  Click **Tax depreciation report** to print the **Tax depreciation report**.

## See also

[(LVA) Tax depreciation (form)](https://technet.microsoft.com/en-us/library/jj911011\(v=ax.60\))

[(LVA) Tax depreciation details (form)](https://technet.microsoft.com/en-us/library/jj911030\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

