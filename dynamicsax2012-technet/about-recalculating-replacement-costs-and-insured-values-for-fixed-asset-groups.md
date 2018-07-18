---
title: About recalculating replacement costs and insured values for fixed asset groups
TOCTitle: About recalculating replacement costs and insured values for fixed asset groups
ms:assetid: 6381aa76-a55a-4f4e-b62e-94d7d3b59b77
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231534(v=AX.60)
ms:contentKeyID: 36057682
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About recalculating replacement costs and insured values for fixed asset groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Periodically, you might be notified that the cost to replace or insure specific fixed assets has changed. For example, your manager might inform you that inflation was 3 percent last year, so you need to increase the replacement cost of all fixed assets by 3 percent.

Although you can edit the replacement cost and insured value for individual fixed assets in the **Fixed assets** form, you can use the **Update replacement costs and insured values** form to update these values for a group of assets at one time. This information describes how to update values for fixed asset groups or for specific assets in the groups.

## How values are updated

To recalculate replacement costs and insured values for fixed asset groups, you must first specify the percentage by which to change the existing replacement costs and insured values, and then perform the periodic update to actually recalculate the values. You specify the percentage in the **Replacement cost factor** and **Insured value factor** fields in the **Fixed asset groups** form. Although you specify these factors for the fixed asset group, when you use the **Update replacement costs and insured values** form, you can select to recalculate the replacement cost and insured value for only specific fixed assets in a group.

When you use the **Update replacement costs and insured values** form to recalculate the replacement cost and insured value for the assets, the following formulas are used:

  - \[(Asset group's replacement cost factor / 100) + 1\] \* Asset's existing replacement cost

  - \[(Asset group's insured value factor / 100) + 1\] \* Asset's existing insured value


> [!NOTE]
> <P>When you use the <STRONG>Update replacement costs and insured values</STRONG> form, both the replacement cost and insured value are updated for the selected assets; you cannot specify that only one value be updated. To leave one value the same and update the other value, enter 0 (zero) as the factor in the <STRONG>Fixed asset groups</STRONG> form. A zero or blank factor causes the calculation to be skipped in the update. The book value and net book value of fixed assets are not affected by the periodic update.</P>



## How to use a date to select which items to update

By default, the update process updates the selected assets that have not been updated on the current day, but that might have been updated on previous days. For example, \< current date means “before today.” You can change the date in the **Update replacement costs and insured values** form by clicking the **Select** button. The date criteria that you specify is compared to the date of the last periodic update for the asset (the **Last periodic value/cost update** field in the **Fixed assets** form). Each time that you successfully update the replacement cost or insured value for a fixed asset, the **Last periodic value/cost update** field is automatically updated with the current date.

**Example**

You updated the replacement cost of the Vehicles, Office Furniture, and Buildings groups by 5 percent yesterday, and you now consider these assets to be accurately updated. To exclude these assets when you update all other fixed assets today, you enter a date in the **Last periodic value/cost update** field that is before yesterday (\< yesterday's date), because the last update for the Vehicles, Office Furniture, and Buildings groups occurred outside the date criteria you entered.

## Cumulative effect of each update

Each update has a cumulative effect. Therefore, you should plan your updates carefully. For example, if you increase all assets by 3 percent on Tuesday and then increase office furniture by 4 percent on Friday, office furniture will increase by a total of 7.12 percent.

## Scenario

Your manager notifies you of the following changes to fixed assets:

  - Increase the replacement cost of all fixed assets, except computers, by 3.25 percent.

  - Increase the replacement cost of all office furniture by an additional 1 percent.

  - Decrease the replacement cost and insured value of all computers by 10 percent.

You make the following changes:

1.  In the **Fixed asset groups** form, for all fixed asset groups except the Office Furniture group and Computers group, you type 3.25 in the **Replacement cost factor** field and 0 in the **Insured value factor** field.

2.  For the Office Furniture group, you type 4.25 in the **Replacement cost factor** field and 0 in the **Insured value factor** field.

3.  For the Computers group, you type -10 in the **Replacement cost factor** field and -10 in the **Insured value factor** field.

4.  In the **Update replacement costs and insured values** form, you click **OK** to perform the recalculation for all fixed assets.

The next day, your manager informs you that computers decreased 8 percent instead of 10 percent, so that you have to correct the replacement costs and insured values. To fix the error, you can use either of two methods:

  - Manually change the **Insured value** and **Replacement cost** fields in the **Fixed assets** form for each fixed asset in the Computers fixed asset group. Calculate and manually enter the values as if you had decreased the original amount by 8 percent. By using this method, you do not use the **Update replacement costs and insured values** form.

  - Enter replacement cost and insured value factors for the Computers group in the **Replacement cost factor** and **Insured value factor** fields in the **Fixed asset groups** form. This will both reset the assets back to their original value (before the 10 percent decrease) and apply the 8 percent decrease to the original value. Then use the **Update replacement costs and insured values** form to recalculate the values, depending on the factors that you entered.
    

    > [!NOTE]
    > <P>You cannot reverse the -10 factor by entering a factor of positive 10 (or a factor of 2, the difference between -10 and -8), because the amounts will not be calculated as you intend.</P>



## See also

[Recalculate replacement costs and insured values](recalculate-replacement-costs-and-insured-values.md)

[Update replacement costs and insured values (form)](https://technet.microsoft.com/en-us/library/hh227488\(v=ax.60\))

  


