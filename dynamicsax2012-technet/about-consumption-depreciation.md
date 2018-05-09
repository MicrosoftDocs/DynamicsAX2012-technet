---
title: About consumption depreciation
TOCTitle: About consumption depreciation
ms:assetid: 4aa76bd0-811b-44b1-a1bb-0e27701553e3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa497011(v=AX.60)
ms:contentKeyID: 36676386
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# About consumption depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you set up a depreciation profile for fixed assets and you select **Consumption** in the **Method** field in the **Depreciation profiles** form, the fixed assets that are assigned to this depreciation profile are based on the usage of those fixed assets.

You do not have to set up percentages and intervals in the **Depreciation profiles** form. After you create a depreciation profile that uses the **Consumption** method, you can set up the method in a variety of ways.

## To use consumption depreciation

1.  Create the depreciation profile in the **Depreciation profiles** form. For information, see [Depreciation profiles (form)](https://technet.microsoft.com/en-us/library/aa549887\(v=ax.60\)).
    
    For consumption calculations, the depreciation profile must have an ID and a name, and **Consumption** must be selected in the **Method** field.

2.  Set up consumption factors in the **Consumption factors** form. For information, see [Consumption factors (form)](https://technet.microsoft.com/en-us/library/aa571869\(v=ax.60\)).
    
    Each consumption factor must have an ID and a name, and a consumption factor that is specified as either a quantity or percentage.

3.  Set up consumption units in the **Consumption units** form. For information, see [Consumption units (form)](https://technet.microsoft.com/en-us/library/aa576472\(v=ax.60\)).
    
    Each consumption unit must have an ID and a name. Depreciation units are used to calculate consumption depreciation in the **Consumption depreciation** form. Examples of units are kilometer (km), kilogram (kg), and hour.

4.  Set up individual fixed assets in the **Fixed assets** form. For each fixed asset, select value models and depreciation books that have depreciation profiles.
    
    You must set up value models or depreciation books for consumption depreciation, if you have fixed assets that use depreciation profiles that are based on the **Consumption** method. This is set up on the **Depreciation** tab of the **Value models** form, or on the **General** FastTab in the **Depreciation profile** form. You can use the same value model for multiple fixed assets.
    
    Depreciation profiles are part of the value model or depreciation book that you select for each fixed asset. You cannot add or modify depreciation profiles directly in the **Fixed assets** form. You can modify the depreciation profiles only in the **Depreciation books** form.

5.  In the **Value models** form or **Depreciation books** form, enter information in the following fields in the **Consumption depreciation** field group:
    
      - **Consumption factor**
    
      - **Unit**
    
      - **Unit depreciation**
    
      - **Estimated consumption**
    
    The **Posted consumption** field shows the consumption depreciation, in units, that has already been posted for the fixed asset and value model combination, or for the depreciation book. You cannot manually update this field value.

## Examples

## Example 1

The following consumption factor is set up for January 31:

  - The quantity is 1,000.

  - The unit depreciation price that is specified for the fixed asset is 1.5.

The depreciation proposal on January 31 is as follows:

Quantity \* Unit depreciation

1,000 \* 1.5 = 1,500

If the factor that is specified for the fixed asset is a percentage factor, the quantity that is estimated in the **Estimated consumption** field for the value model of the fixed asset is multiplied by the percentage that is set up for the selected ending date. The quantity after the multiplication is suggested as the depreciation quantity for the period.

## Example 2

The following factor for consumption depreciation is set up for January 31:

  - The percentage is 10 percent.

  - The unit depreciation price that is specified for the fixed asset is 1.5.

  - The estimated quantity of the fixed asset is 2,000.

The depreciation proposal on January 31 is as follows:

Estimated quantity \* Percentage \* Unit depreciation

2,000 \* .10 \* 1.5 = 300

## See also

[Set up consumption depreciation](set-up-consumption-depreciation.md)

[Depreciation profiles (form)](https://technet.microsoft.com/en-us/library/aa549887\(v=ax.60\))

[Set up depreciation profiles](set-up-depreciation-profiles.md)

[Consumption factors (form)](https://technet.microsoft.com/en-us/library/aa571869\(v=ax.60\))

[Consumption units (form)](https://technet.microsoft.com/en-us/library/aa576472\(v=ax.60\))

[Fixed assets (form)](https://technet.microsoft.com/en-us/library/aa620341\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

