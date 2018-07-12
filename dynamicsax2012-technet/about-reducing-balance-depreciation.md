---
title: About reducing balance depreciation
TOCTitle: About reducing balance depreciation
ms:assetid: dd47c83e-b38a-4acc-8066-5bfd498a49a6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551268(v=AX.60)
ms:contentKeyID: 36931884
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About reducing balance depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you set up a fixed asset depreciation profile and select **Reducing balance** in the **Method** field in the **Depreciation profiles** form, the assets that have this depreciation profile assigned to them are depreciated by the same percentage in each depreciation period.

To set up reducing balance depreciation, you must also make selections in fields on the **General** FastTab of the **Depreciation profiles** form. First, select a year in the **Depreciation year** field. Depending on the selection, different options appear in the **Period frequency** field, as explained in the following sections.

You must also enter a value in the **Percentage** field for the depreciation profile. If you select the **Full depreciation** check box, the remaining depreciation basis is taken in the last depreciation period and could be a large amount. Some countries/regions do not use a switchover to a straight line method. Switchover occurs when the alternative depreciation method amount is greater than or equal to the primary depreciation profile amount, and the depreciation amount taken is the alternative method amount.

Because an asset will never be fully depreciated based on a percentage calculation, you must select the **Full depreciation** check box to fully depreciate an asset.

## Select a depreciation year

You can select either **Calendar** or **Fiscal** in the **Depreciation year** field in the **Depreciation profiles** form. The selection defines the options that are available in the **Period frequency** field. The default option is **Calendar**.

## Calendar

The **Calendar** option updates the depreciation base, which is typically the net book value minus the scrap value, on January 1 of each year. In the reducing balance depreciation example later in this topic, the depreciation base is the numerator in the first expression in the calculations column.

If you select **Calendar**, the following options are available in the **Period frequency** field, which defines the depreciation accrual posting dates and amounts throughout the calendar year:

  - **Yearly** posts on December 31.

  - **Monthly** posts a monthly amount at the end of each calendar month.

  - **Quarterly** posts a quarterly amount at the end of each calendar quarter (March 31, June 30, September 30, and December 31).

  - **Half-Yearly** posts a half-yearly amount at the end of each calendar half-year (June 30 and December 31).

  - **Daily** posts the depreciation amount for the daily depreciation method using one transaction for each day.
    

    > [!NOTE]
    > <P>(THA) This control is available only to legal entities whose primary address is in Thailand.</P>



For example, if you select **Yearly**, the yearly depreciation is posted only one time, on December 31 of each year. If you select **Monthly**, the monthly depreciation is posted each month as 1/12 of the yearly depreciation amount.

## Fiscal

If you select **Fiscal** in the **Depreciation year** field, the straight line depreciation method is used. It is calculated based on the fiscal year, which is set up in the **Fiscal calendars** form for the fiscal calendar that is selected in the **Ledger** form.

For example, for fiscal year July 1 through June 30, the depreciation calculation starts on July 1. The fiscal year can be longer or shorter than 12 months. The depreciation is adjusted for each fiscal period. The length of the next fiscal year is based on the fiscal periods that you set up when you create a new fiscal year in the **Fiscal calendars** form.


> [!NOTE]
> <P>You can select a fiscal calendar for a value model in the <STRONG>Value models</STRONG> form. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa582567(v=ax.60)">Value models setup (form)</A>. You can select a fiscal calendar for a depreciation book in the <STRONG>Depreciation books</STRONG> form. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa597721(v=ax.60)">Depreciation books setup (form)</A>.</P>



If you select **Fiscal**, the following options are available in the **Period frequency** field:

  - **Yearly** posts the total amount of the depreciation calculated for the fiscal year as one amount on the last day of the fiscal year.

  - **Fiscal period** posts the total amount of the depreciation calculated for the fiscal year, which is accrued into the fiscal periods that are defined for the fiscal calendar that is selected in the **Ledger** form, or for the fiscal calendar that is selected for the value model or depreciation book for a fixed asset.

## Example of reducing balance depreciation

Suppose that the fixed asset acquisition price is 11,000, the scrap value is 1,000, and the depreciation percentage factor is 30.

Using the **Reducing balance** method, 30 percent of the depreciation base (net book value minus scrap value) is calculated at the end of the previous depreciation period. Depreciation for the first three years is shown in the following table.

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
<td><p>(11,000 - 1,000) * 30% = 3,000</p></td>
<td><p>(11,000 - 1,000) - 3,000 = 7,000</p></td>
</tr>
<tr class="even">
<td><p>Year 2</p></td>
<td><p>(7,000 - 1,000) * 30% = 1,800</p></td>
<td><p>(7,000 -1,800) = 5,200</p></td>
</tr>
<tr class="odd">
<td><p>Year 3</p></td>
<td><p>(5,200 - 1,000) * 30% = 1,260</p></td>
<td><p>(5,200 - 1,260) = 3,940</p></td>
</tr>
</tbody>
</table>


## Calculating depreciation rates for Germany

The depreciation rates for Germany are calculated as follows:

If triple the depreciation rate of the straight line method is less than the given maximum percentage for the reducing balance, triple the straight line rate must be used for calculating the depreciation amount.

If triple the depreciation rate of the straight line method is greater than the given maximum percentage for the reducing balance, this given percentage must be used for calculating the depreciation amount.

## See also

[Set up depreciation profiles](set-up-depreciation-profiles.md)

[Key tasks: Fiscal calendars, fiscal years, and periods](key-tasks-fiscal-calendars-fiscal-years-and-periods.md)

  


