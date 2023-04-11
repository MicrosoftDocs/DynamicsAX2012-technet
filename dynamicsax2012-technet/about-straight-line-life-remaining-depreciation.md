---
title: About straight line life remaining depreciation
TOCTitle: About straight line life remaining depreciation
ms:assetid: 8f267249-1322-49fc-b827-71c7c4e775f9
ms:mtpsurl: https://technet.microsoft.com/library/Aa498361(v=AX.60)
ms:contentKeyID: 36058519
author: tonyafehr
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About straight line life remaining depreciation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you set up a fixed asset depreciation profile and select **Straight line life remaining** in the **Method** field in the **Depreciation profiles** form, the depreciation of fixed assets that are assigned to this depreciation profile is based on the remaining service life of the asset. This generally is the same depreciation amount in each depreciation period.

To set up straight line life remaining depreciation, you also must select options in the **Depreciation year** field and the **Period frequency** field in the **Depreciation profiles** form. Depending on the selection in the **Depreciation year** field, the options will change in the **Period frequency** field.

## Select a depreciation year

You can select either **Calendar** or **Fiscal** in the **Depreciation year** field in the **Depreciation profiles** form. Your selection defines the options that are available in the **Period frequency** field. The default option is **Calendar**.

## Calendar

When you select **Calendar**, a year of January 1 to December 31 is assumed, even if you have defined the fiscal calendar differently.

The **Calendar** option updates the depreciation base, which is typically the net book value minus the salvage value, on January 1 of each year. In the example later in this topic, the depreciation base is the numerator in the first expression in the calculations column.

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

If you select **Fiscal** in the **Depreciation year** field, the straight line life remaining depreciation is used. It is calculated based on the fiscal years remaining.

For example, for fiscal year July 1, 2014, through June 30, 2015, the depreciation calculation starts on July 1. The fiscal year can be longer or shorter than 12 months. The depreciation is adjusted for each fiscal period. The length of the next fiscal year is determined by the fiscal periods that are set up in the **Fiscal calendars** form.

If you select **Fiscal** as the depreciation year, the following options are available in the **Period frequency** field:

  - **Yearly** posts the total amount of the depreciation calculated for the fiscal year as one amount on the last date of the fiscal year.

  - **Fiscal period** calculates the total amount of the depreciation for the fiscal year, which is accrued into the fiscal periods that are defined in the **Fiscal calendars** form for the fiscal calendar that is specified for the value model or depreciation book.

## Example of straight line depreciation of an unchanged fixed asset

A fixed asset has the following characteristics.

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
<td><p>(9,000 - 1,000) / 4 = 2,000</p></td>
<td><p>7,000</p></td>
</tr>
<tr class="odd">
<td><p>Year 3</p></td>
<td><p>(7,000 - 1,000) / 3 = 2,000</p></td>
<td><p>5,000</p></td>
</tr>
<tr class="even">
<td><p>Year 4</p></td>
<td><p>(5,000 - 1,000) / 2 = 2,000</p></td>
<td><p>3,000</p></td>
</tr>
<tr class="odd">
<td><p>Year 5</p></td>
<td><p>(3,000 - 1,000) / 1 = 2,000</p></td>
<td><p>1,000</p></td>
</tr>
</tbody>
</table>


## See also

[Set up depreciation profiles](set-up-depreciation-profiles.md)

  


