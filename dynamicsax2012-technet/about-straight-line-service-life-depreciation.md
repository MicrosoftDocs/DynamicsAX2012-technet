---
title: About straight line service life depreciation
TOCTitle: About straight line service life depreciation
ms:assetid: fe3a0dc6-c74d-4303-b886-9d924c31a6b2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa573443(v=AX.60)
ms:contentKeyID: 36060113
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About straight line service life depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you set up a fixed asset depreciation profile and select **Straight line service life** in the **Method** field in the **Depreciation profiles** form, the assets that have this depreciation profile assigned to them are depreciated based on the total service life of the asset. This generally is the same depreciation amount in each depreciation period.

The difference in the depreciation amount that is calculated between straight line service life remaining and straight line service life is when there is an adjustment posted to the asset.

To set up straight line service life depreciation, you must also select options in the **Depreciation year** and **Period frequency** fields in the **Depreciation profiles** form.

## Select a depreciation year

You can select either **Calendar** or **Fiscal** in the **Depreciation year** field in the **Depreciation profiles** form. The selection defines the options that are available in the **Period frequency** field. The default option is **Calendar**.

## Calendar

If you select **Calendar**, a year of January 1 to December 31 is assumed, even if you have defined the fiscal calendar differently.

The **Calendar** option updates the depreciation base, which is typically the net book value minus the salvage value, on January 1 of each year. In the examples later in this topic, the depreciation base is the numerator in the first expression in the calculations column.

If you select **Calendar**, the following options are available in the **Period frequency** field, which defines the depreciation accrual posting dates and amounts throughout the calendar year:

  - **Yearly** posts an amount on December 31.

  - **Monthly** posts a monthly amount at the end of each calendar month.

  - **Quarterly** posts a quarterly amount at the end of each calendar quarter (March 31, June 30, September 30, and December 31).

  - **Half-Yearly** posts a half-yearly amount at the end of each calendar half year (June 30 and December 31).

  - **Daily** posts the depreciation amount for the daily depreciation method using one transaction for each day.
    

    > [!NOTE]
    > <P>(THA) This control is available only to legal entities whose primary address is in Thailand.</P>



For example, if you select **Yearly**, the yearly depreciation is posted only one time, on December 31 of each year. If you select **Monthly**, the monthly depreciation is posted each month as 1/12 of the yearly depreciation amount.

## Fiscal

If you select **Fiscal** in the **Depreciation year** field, the straight line service life depreciation is used. It is calculated based on the fiscal year, which is defined by the fiscal calendar that is specified for the value model or depreciation book, or by the fiscal calendar that is selected in the **Ledger** form. Fiscal calendars are set up in the **Fiscal calendars** form. For more information, see [Key tasks: Fiscal calendars, fiscal years, and periods](key-tasks-fiscal-calendars-fiscal-years-and-periods.md).

For example, for fiscal year July 1 through June 30, the depreciation calculation starts on July 1. The fiscal year can be longer or shorter than 12 months. The depreciation automatically is adjusted for each fiscal period. The length of the next fiscal year is based on the fiscal periods that you set up when you create a new fiscal year in the **Fiscal calendars** form.

If you select **Fiscal**, the following options are available in the **Period frequency** field:

  - **Yearly** posts the total amount of the depreciation that is calculated for the fiscal year as one amount on the last day of the fiscal year.

  - **Fiscal period** calculates the total amount of the depreciation for the fiscal year, which is accrued into the periods that are defined in the **Fiscal calendars** form for the fiscal calendar.

## Example: Straight line depreciation of an unchanged fixed asset

Suppose that a fixed asset has the following characteristics.

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
<td><p>Yearly depreciation</p></td>
<td><p>2,000</p></td>
</tr>
</tbody>
</table>


You get the same depreciation amount each year.

(Acquisition cost - Salvage value) / Service life years

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Period</p></th>
<th><p>Calculation of yearly depreciation amount</p></th>
<th><p>Net book value at the end of the year</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Year 1</p></td>
<td><p>(11,000 - 1,000) / 5 = 2,000</p></td>
<td><p>9,000</p></td>
</tr>
<tr class="even">
<td><p>Year 2</p></td>
<td><p>(11,000 - 1,000) / 5 = 2,000</p></td>
<td><p>7,000</p></td>
</tr>
<tr class="odd">
<td><p>Year 3</p></td>
<td><p>(11,000 - 1,000) / 5 = 2,000</p></td>
<td><p>5,000</p></td>
</tr>
<tr class="even">
<td><p>Year 4</p></td>
<td><p>(11,000 - 1,000) / 5 = 2,000</p></td>
<td><p>3,000</p></td>
</tr>
<tr class="odd">
<td><p>Year 5</p></td>
<td><p>(11,000 - 1,000) / 5 = 2,000</p></td>
<td><p>1,000</p></td>
</tr>
</tbody>
</table>


## Example: Straight line depreciation of a modified fixed asset

Suppose that you add an acquisition adjustment of 4,000 in year 2 to the same fixed asset.

The service life of the acquisition adjustment is the same as that of the fixed asset and starts at the time of its acquisition. A net book value remains at the end of year 5, corresponding to the net book value of the acquisition adjustment. The depreciation by period is calculated as shown in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Period</p></th>
<th><p>Calculation of yearly depreciation amount</p></th>
<th><p>Net book value at the end of the year</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Year 1</p></td>
<td><p>10,000 / 5 = 2,000</p></td>
<td><p>11,000 - 2,000 = 9,000</p></td>
</tr>
<tr class="even">
<td><p>Year 2</p></td>
<td><p>4,000 (acquisition adjustment)</p></td>
<td><p>9,000 + 4,000 =13,000</p></td>
</tr>
<tr class="odd">
<td><p>Year 2</p></td>
<td><p>14,000 / 5 = 2,800</p></td>
<td><p>13,000 - 2,800 = 10,200</p></td>
</tr>
<tr class="even">
<td><p>Year 3</p></td>
<td><p>14,000 / 5 = 2,800</p></td>
<td><p>10,200 - 2,800 = 7,400</p></td>
</tr>
<tr class="odd">
<td><p>Year 4</p></td>
<td><p>14,000 / 5 = 2,800</p></td>
<td><p>7,400 - 2,800 = 4,600</p></td>
</tr>
<tr class="even">
<td><p>Year 5</p></td>
<td><p>14,000 / 5 = 2,800</p></td>
<td><p>4,600 - 2,800 = 1,800</p></td>
</tr>
<tr class="odd">
<td><p>Year 6</p></td>
<td><p>Remaining 800*</p></td>
<td><p>1,800 – 800 = 1,000</p></td>
</tr>
</tbody>
</table>


\*Because the remaining amount is less than the depreciation amount, only the remaining amount minus the salvage value is taken.

## See also

[Set up depreciation profiles](set-up-depreciation-profiles.md)

[Key tasks: Fiscal calendars, fiscal years, and periods](key-tasks-fiscal-calendars-fiscal-years-and-periods.md)

  


