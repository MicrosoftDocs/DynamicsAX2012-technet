---
title: About 125 percent reducing balance depreciation
TOCTitle: About 125 percent reducing balance depreciation
ms:assetid: b6b60b09-7f83-4b32-ba55-aa5db52f451c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550598(v=AX.60)
ms:contentKeyID: 36676405
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About 125 percent reducing balance depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you set up a fixed asset depreciation profile and select **125% reducing balance** in the **Method** field in the **Depreciation profiles** form, the depreciation of fixed assets that are assigned to this depreciation profile is by the same percentage in each depreciation period. The percentage will be calculated based on the service life of the asset. For example, if an asset has a service life of five years, the percentage will be calculated as 25% (125% / 5).

To set up 125% reducing balance depreciation, you must also select options in the **Depreciation year** field and the **Period frequency** field in the **Depreciation profiles** form. Depending on the selection in the **Depreciation year** field, the options will change in the **Period frequency** field.

## Selection of depreciation year

You can select either **Calendar** or **Fiscal** in the **Depreciation year** field in the **Depreciation profiles** form. (Click **Fixed assets** \> **Setup** \> **Depreciation** \> **Depreciation profiles**.) This selection defines the options that are available in the **Period frequency** field.

## Calendar

You can keep the default value in the **Depreciation year** field, **Calendar**.

The **Calendar** option updates the depreciation base (typically the net book value minus the scrap value) on January 1 of each year. In the examples later in this topic, the depreciation base is the numerator in the first expression in the calculations in the calculations column.

If you select **Calendar**, you have the following options in the **Period frequency** field, which defines the depreciation accrual posting dates and amounts throughout the calendar year:

  - **Yearly** posts an amount on December 31

  - **Monthly** posts a monthly amount at the end of each calendar month

  - **Quarterly** posts a quarterly amount at the end of each calendar quarter (March 31, June 30, September 30, and December 31)

  - **Half-Yearly** posts a half-yearly amount at the calendar half year (June 30 and December 31)

  - **Daily** posts the depreciation amount for the daily depreciation method using one transaction for each day
    

    > [!NOTE]
    > <P>(THA) This control is available only to legal entities whose primary address is in Thailand.</P>



## Fiscal

If you select **Fiscal** in the **Depreciation year** field, the 125% reducing depreciation is calculated based on the fiscal year for the fiscal calendar that is specified for the value model or depreciation book, or by the fiscal calendar that is selected in the **Ledger** form. Fiscal calendars are set up in the **Fiscal calendars** form. For more information, see [About fiscal calendars, fiscal years, and periods](about-fiscal-calendars-fiscal-years-and-periods.md).

For example, for the fiscal year of July 1 through June 30, the depreciation calculation starts on July 1. The fiscal year can be longer or shorter than 12 months. The depreciation automatically is adjusted for each period, and the length of the next fiscal year is from the setup of periods in the **Fiscal calendars** form.

When you select **Fiscal** as the depreciation year, the following options are available in the **Period frequency** field:

  - **Yearly** posts the total amount of the depreciation calculated for the fiscal year as one amount on the last day of the fiscal year.

  - **Fiscal period** posts the total amount of the depreciation calculated for the fiscal year, which is accrued into the fiscal periods that are defined in the **Fiscal calendars** form.

## Example of 125% reducing balance depreciation

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Acquisition cost</p></td>
<td><p>11,000</p></td>
</tr>
<tr class="even">
<td><p>Salvage value</p></td>
<td><p>1,000</p></td>
</tr>
<tr class="odd">
<td><p>Depreciation base</p></td>
<td><p>10,000</p></td>
</tr>
<tr class="even">
<td><p>Service life years</p></td>
<td><p>5</p></td>
</tr>
<tr class="odd">
<td><p>Yearly depreciation percentage</p></td>
<td><p>25%</p></td>
</tr>
</tbody>
</table>


The 125% reducing balance method will divide 125% by the service life years. That percentage will be multiplied by the net book value of the asset to determine the depreciation amount for the year.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Period</p></th>
<th><p>Calculation of yearly depreciation amount</p></th>
<th><p>Book value</p></th>
<th><p>Net book value at the end of the year</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Year 1</p></td>
<td><p>(11,000 - 1,000) * 25% = 2,500</p></td>
<td><p>(11,000 - 2,500) = 8,500</p></td>
<td><p>(11,000 - 1,000 - 2,500) = 7,500</p></td>
</tr>
<tr class="even">
<td><p>Year 2</p></td>
<td><p>7,500 * 25% = 1,875</p></td>
<td><p>(8,500 - 1,875) = 6,625</p></td>
<td><p>(7,500 - 1,875) = 5,625</p></td>
</tr>
<tr class="odd">
<td><p>Year 3</p></td>
<td><p>5,625 * 25% = 1,406.25</p></td>
<td><p>(6,625 - 1,406.25) = 5,218.75</p></td>
<td><p>(5,625 - 1,406.25) = 4,218.75</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>When the 125% reducing balance depreciation amount becomes less than what would have occurred using the straight line method, there is generally a conversion to straight line for the remaining life.</P>


  


