---
title: (JPN) Equally divided depreciation method
TOCTitle: (JPN) Equally divided depreciation method
ms:assetid: 9c3d1da8-41b6-4cd2-9bd0-8427b17b9358
ms:mtpsurl: https://technet.microsoft.com/library/Dn716012(v=AX.60)
ms:contentKeyID: 62200255
author: Khairunj
ms.date: 06/07/2014
mtps_version: v=AX.60
f1_keywords:
- depreciation method
- equally divided depreciation method
audience: Application User
ms.search.region: Japan
---

# (JPN) Equally divided depreciation method 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can set up the **Equally divided** depreciation method in the **Depreciation profiles** form to depreciate a deferred, low value, or lump sum fixed asset equally over one or more fiscal periods within the useful life of a fixed asset.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R3.</P>



## What fixed asset types can I depreciate using the equally divided depreciation method?

You can use the equally divided depreciation method to depreciate deferred, low value, and lump sum fixed assets. You can then generate reports to view the depreciation expenses for the assets over one or more fiscal periods.

## How does Microsoft Dynamics AX calculate depreciation using the equally divided depreciation method?

You can set up a depreciation profile by selecting **Equally divided** as the depreciation method in the **Method** field in the **Depreciation profiles** form. When you use the equally divided depreciation profile to depreciate a fixed asset, Microsoft Dynamics AX calculates the depreciation amounts using the following formula:

Depreciation = Remaining amount \* rounding (1/Number of remaining years) \* rounding (1/Number of periods in the current year)

The following formula is used to calculate the remaining amount:

Remaining amount = Acquisition cost – Accumulated depreciation

When you use the equally divided depreciation method to calculate the depreciation amount, the value in the **Number of years to equally divide depreciation amounts** field in the **Depreciation profiles** form indicates the useful life of the fixed asset instead of the service life and the depreciation period that you specified in the **Value models** form.

## Does the depreciation amount that is calculated using the equally divided depreciation method change when it is calculated at the beginning of the month versus the middle of the month?

No. The depreciation value does not change depending upon when it is calculated during the month.

For example, you acquire a lump sum fixed asset:

  - Acquisition value of the lump sum fixed asset = JPY 150,000

  - Acquisition date = April 1, 2013

  - Number of years to equally divide the depreciation amount = 3 years

Using the equally divided depreciation method, the depreciation amount for this fixed asset is JPY 4,166.67 for each month whether you calculate it at the beginning of the month or in the middle of the month.

## How does Microsoft Dynamics AX calculate equally divided depreciation for a low value asset that is acquired midyear?

If you purchase a low value fixed asset in the middle of a fiscal year, Microsoft Dynamics AX considers the current fiscal year to be the first fiscal year for the depreciation calculation.

For example, you acquire a low value fixed asset in the middle of a fiscal year:

  - Fiscal year = April 1 to March 31

  - Acquisition value of the low value fixed asset = JPY 100,000

  - Acquisition date = December 1, 2012

  - Number of years to equally divide the depreciation amount = 1 year

Microsoft Dynamics AX calculates the depreciation for the fiscal year from April 1, 2012 to March 31, 2013 as explained in the following table.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Start date</p></th>
<th><p>End date</p></th>
<th><p>Depreciation amount for the fiscal period</p></th>
<th><p>Accumulated depreciation</p></th>
<th><p>Remaining depreciation amount</p></th>
<th><p>Depreciation amount for the month</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>April 1, 2012</p></td>
<td><p>March 31, 2013</p></td>
<td><p>JPY 100,000</p></td>
<td><p>JPY 100,000</p></td>
<td><p>0</p></td>
<td><p>JPY 100, 000</p></td>
</tr>
</tbody>
</table>


## How does Microsoft Dynamics AX calculate equally divided depreciation for a lump sum asset that is acquired midyear?

If you purchase a lump sum fixed asset in the middle of a fiscal year, Microsoft Dynamics AX calculates the current fiscal year from the purchase date of the fixed asset.

For example, you acquire a lump sum fixed asset in the middle of a fiscal year:

  - Fiscal year = April 1 to March 31

  - Acquisition value of the lump sum fixed asset = JPY 150,000

  - Acquisition date = December 1, 2012

  - Number of years to equally divide the depreciation amount = 3 years

Microsoft Dynamics AX calculates the depreciation for the first year from December 1, 2012 to March 31, 2013 as explained in the following table.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Start date</p></th>
<th><p>End date</p></th>
<th><p>Depreciation amount for a fiscal period</p></th>
<th><p>Accumulated depreciation</p></th>
<th><p>Remaining depreciation amount</p></th>
<th><p>Depreciation amount for a month</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>December 1, 2012</p></td>
<td><p>March 31, 2013</p></td>
<td><p>JPY 50,000</p></td>
<td><p>JPY 50,000</p></td>
<td><p>JPY 100,000</p></td>
<td><p>JPY 12,500</p></td>
</tr>
<tr class="even">
<td><p>April 1, 2013</p></td>
<td><p>March 31, 2014</p></td>
<td><p>JPY 50,000</p></td>
<td><p>JPY 100,000</p></td>
<td><p>JPY 50,000</p></td>
<td><p>JPY 4,167</p></td>
</tr>
<tr class="odd">
<td><p>April 1, 2014</p></td>
<td><p>March 31, 2015</p></td>
<td><p>JPY 50,000</p></td>
<td><p>JPY 150,000</p></td>
<td><p>0</p></td>
<td><p>JPY 4,167</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>In AX 2012 R3: The annual depreciation rate is not rounded off for the equally divided depreciation method.</P>



## How does Microsoft Dynamics AX calculate depreciation using the equally divided depreciation method if the asset calendar is changed during an asset life cycle?

Microsoft Dynamics AX calculates depreciation using the equally divided depreciation method based on the fiscal calendar that is selected in the **Calendar** field in the **Depreciation books** form. If an asset calendar is changed during the asset life cycle, Microsoft Dynamics AX calculates the number of fiscal periods, such as months or quarters, in a fiscal year based on the current calendar.

For example, you acquire a lump sum fixed asset:

  - Fiscal calendar = April 1 to March 31

  - Acquisition date of the lump sum fixed asset = 1 April 2012

  - Number of years to equally divide the depreciation amount = 3 years

In April 2013, during the second fiscal year, if you change the fiscal calendar from April 1 through March 31 to January 1 through December 31, Microsoft Dynamics AX calculates the number of depreciation periods for the fiscal years in the following way.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fiscal year</p></th>
<th><p>Number of depreciation periods</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>April 1, 2012 through March 31, 2013</p></td>
<td><p>12 periods</p></td>
</tr>
<tr class="even">
<td><p>April 1, 2013 through December 31, 2013</p></td>
<td><p>9 periods</p></td>
</tr>
<tr class="odd">
<td><p>January 1, 2014 through December 31, 2014</p></td>
<td><p>12 periods</p></td>
</tr>
<tr class="even">
<td><p>January 1, 2015 through March 31, 2015</p></td>
<td><p>3 periods</p></td>
</tr>
</tbody>
</table>


## Can I modify the equally divided depreciation method during the life cycle of a fixed asset?

No. When you depreciate a fixed asset using the equally divided depreciation method, the depreciation amount is equally divided among the fiscal periods within the useful life of the fixed asset. Therefore, you cannot change the depreciation method during the life cycle of the fixed asset.

## Can I change the depreciation period for an equally divided depreciation profile?

No. If you selected an equally divided depreciation profile in the **Depreciation books** form or the **Value models** form, you cannot change the value in the **Number of years to equally divide depreciation amounts** field in the **Depreciation profiles** form for the depreciation profile.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(JPN) Fixed asset depreciation](jpn-fixed-asset-depreciation.md)

  


