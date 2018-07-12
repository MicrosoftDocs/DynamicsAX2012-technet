---
title: (JPN) Fixed asset depreciation
TOCTitle: (JPN) Fixed asset depreciation
ms:assetid: e350ea42-7c24-4f06-843b-8a2d04ca028d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn385849(v=AX.60)
ms:contentKeyID: 56558353
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Japan
---

# (JPN) Fixed asset depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A fixed asset depreciates over the course of its useful life, decreasing the acquisition value of the asset. To regulate the depreciation of a fixed asset, you must assign one of the following depreciation methods to the asset based on the date when the asset was placed into service:

  - **Old straight line** – Depreciate assets that were placed into service prior to April 1, 2007 by using the straight line method.

  - **New straight line** – Depreciate assets that were placed into service on or after April 1, 2007 by using the straight line method.

  - **Old declining balance** – Depreciate assets that were placed into service prior to April 1, 2007 by using the declining balance method.

  - **250% new declining balance** – Depreciate assets that were placed into service prior to April 1, 2012 by using the declining balance method.

  - **200% new declining balance** – Depreciate assets that were placed into service on or after to April 1, 2012 by using the declining balance method.

## What are special depreciation and additional depreciation?

Special depreciation and additional depreciation are depreciation types that are applied to special types of fixed assets, which are summarized in the following list:

  - Fixed assets that are used based on certain industrial policies that promote the supply and development of green energy or new energy, such as wave energy

  - Fixed assets that are purchased for the purpose of safety and sustainability

  - Fixed assets that are used to aid an employee with a disability

  - Fixed assets that are built for the purpose of aiding elderly and sick people

When you use special depreciation, you depreciate fixed assets based on their standard acquisition cost by using the special depreciation rate.

When you use additional depreciation, you depreciate an extra portion of the acquisition cost based on the ordinary depreciation amount.


> [!NOTE]
> <P>If a fixed asset is eligible for both special depreciation and additional depreciation, you can apply only one of them to the asset for a depreciation period.</P>



## What is the allowable limit for depreciation?

The allowable limit for depreciation is the maximum amount of the total depreciation expense that can be permitted as a deductible expense per tax book for each depreciation period.

The allowable limit for depreciation for a fixed asset corresponds with the depreciation types that are used to depreciate your company’s fixed assets.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Depreciation type</p></th>
<th><p>Allowable limit for depreciation</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Ordinary depreciation</p></td>
<td><p>Allowable limit for ordinary depreciation</p></td>
</tr>
<tr class="even">
<td><p>Accelerated depreciation</p></td>
<td><p>Allowable limit for accelerated depreciation</p></td>
</tr>
<tr class="odd">
<td><p>Special depreciation</p></td>
<td><p>Allowable limit for special depreciation</p></td>
</tr>
<tr class="even">
<td><p>Additional depreciation</p></td>
<td><p>Allowable limit for additional depreciation</p></td>
</tr>
</tbody>
</table>


The allowable limit for depreciation for each period for your company’s fixed assets can be calculated by using the following formula.

Allowable limit for depreciation = Allowable limit for ordinary depreciation + Allowable limit for accelerated depreciation + Allowable limit for special depreciation or Allowable limit for additional depreciation

## What is the allowable limit for accumulated depreciation?

The allowable limit for accumulated depreciation is the maximum amount of accumulated depreciation that can be deducted from the acquisition value of a fixed asset for its useful life. You can choose the value of the allowable limit for accumulated depreciation depending on the depreciation method that you apply to the fixed asset and whether the fixed asset is tangible or intangible. There are two kinds of allowable limit for accumulated depreciation:

  - **95% allowable limit for accumulated depreciation** – This limit is applied only to tangible assets that are depreciated by using the old straight line method or the old declining balance method. This limit is restricted to 95% of the acquisition cost of the fixed asset.

  - **Maximum allowable limit for accumulated depreciation** – This limit is applied to both tangible assets and intangible assets that are depreciated by using a deprecation method other than the old straight line method or the old declining balance method. For a tangible asset, the maximum allowable limit for accumulated depreciation is the acquisition cost of the asset. The maximum allowable limit for accumulated depreciation of an intangible asset is the same as the acquisition cost of the asset reduced by JPY 1.

## Can I calculate depreciation for a fixed asset for a fiscal year that has fewer than 12 months?

Yes. Microsoft Dynamics AX supports depreciation calculation if a fiscal year has fewer than 12 months. You can set up multiple depreciation calendars and change between calendars. If the current fiscal year has fewer than 12 months after you change depreciation calendars, Microsoft Dynamics AX will proportionally adjust the depreciation ratio based on the number of months in the current fiscal year and a fiscal year that has 12 months.

Here’s an example of how depreciation is calculated for a fiscal year that has fewer than 12 months.

Assume that the fiscal year spans from April 1, 2010 to March 31, 2011 and the depreciation is calculated for the entire fiscal year. After the change of the fiscal year, the fiscal year period spans from January 1, 2011 to December 31, 2011.

After you change the depreciation calendar, the months of January, February, and March become part of the previous fiscal calendar and the current fiscal year consists of only nine months. The remaining nine months from April 1, 2011 to December 31, 2011 are used to calculate the depreciation by using a prorated method that uses the depreciation rates from the previous fiscal year.

## What is the catch-up rule for depreciation and how does it work?

The catch-up rule for depreciation is used as an effective way to allocate annual depreciation expenses to the depreciation expenses for each period.

You can enable the catch-up rule in Microsoft Dynamics AX by selecting the **Allow catch-up rule for depreciation** check box in the **Fixed assets parameters** form. For more information, see [(JPN) Set up depreciation and depreciation methods](jpn-set-up-depreciation-and-depreciation-methods.md).

## How do I calculate a depreciation expense by using the catch-up rule?

The depreciation expense for each month is calculated and posted in the following month. The following factors are used to calculate the monthly depreciation expense:

  - Total depreciation expense that is incurred starting from the beginning of the year:
    
    Annual depreciation expense \* (Position of current month in the fiscal year / 12) = 100,000 JPY

  - Total depreciation expense that is posted from January through the current month

  - Depreciation expense that is posted for the current month: Total depreciation expense that is incurred starting from the beginning of the year - Total depreciation expense that is posted from January through the current month = 100,000 JPY

The monthly depreciation is calculated as follows:

Annual depreciation expense \* (Position of current month in the fiscal year / Total number of months in the calendar year) - Total depreciation expense that is posted from January through the current month

This calculation method ensures that the total of the monthly depreciation expense is equal to the annual depreciation expense of the asset.

## Can I change the depreciation profile of a fixed asset after posting the depreciation for the asset?

Yes. You can change the depreciation profile of a fixed asset even after you have posted the depreciation for the asset. The following table shows the depreciation method changes that are allowed.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Starting depreciation method</p></th>
<th><p>Allowed depreciation method change</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Old straight line</p></td>
<td><p>Old declining balance</p></td>
</tr>
<tr class="even">
<td><p>Old declining balance</p></td>
<td><p>Old straight line</p></td>
</tr>
<tr class="odd">
<td><p>New straight line</p></td>
<td><p>250% declining balance</p>
<p>–or–</p>
<p>200% declining balance</p></td>
</tr>
<tr class="even">
<td><p>250% declining balance</p></td>
<td><p>200% declining balance</p>
<p>–or–</p>
<p>New straight line</p></td>
</tr>
<tr class="odd">
<td><p>200% declining balance</p></td>
<td><p>250% declining balance</p>
<p>–or–</p>
<p>New straight line</p></td>
</tr>
</tbody>
</table>


You can also use Microsoft Dynamics AX to track the history of the change and to automatically calculate the new useful life of the asset based on undepreciated balance schedules and years passed schedules. For more information, see [(JPN) Configure and calculate fixed asset depreciation](jpn-configure-and-calculate-fixed-asset-depreciation.md).

## What types of schedules can I import for depreciation purposes?

You can import the following schedules to recalculate the depreciation and the service life of a fixed asset:

  - Undepreciated balance schedule

  - Years passed schedule

The depreciation rate schedule that you import depends on the type of depreciation method that you use for a fixed asset. For more information, see [(JPN) Configure and calculate fixed asset depreciation](jpn-configure-and-calculate-fixed-asset-depreciation.md).

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  


