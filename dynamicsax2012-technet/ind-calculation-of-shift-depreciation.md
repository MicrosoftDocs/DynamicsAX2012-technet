---
title: (IND) Calculation of shift depreciation
TOCTitle: (IND) Calculation of shift depreciation
ms:assetid: 4065068b-a73b-4f1f-ba7a-569fe2586249
ms:mtpsurl: https://technet.microsoft.com/library/JJ664641(v=AX.60)
ms:contentKeyID: 49385718
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculation of shift depreciation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can calculate shift depreciation for a value model with a **Current** status selected in the **Posting layer** field and a straight line percentage method or reducing balance depreciation method selected in the **Depreciation profile** field in the **Value models** form, per the Companies Act, 1956.

**Example**

The calculation of the number of days that an asset is used for is described below.

An asset is used from December 21, 2012 to March 31, 2013. The days for each period in the fixed asset calendar are as follows:

  - December 21, 2011 to December 31, 2011 = 11 days

  - January 1, 2012 to January 31, 2012 = 31 days

  - February 1, 2012 to February 29, 2012 = 29 days

  - March 1, 2012 to March 31, 2012 = 31 days

The total number of days that the asset is used for is 102 days, which is 11 + 31 + 29 + 31.


> [!NOTE]
> <P>Depreciation for non-working days will be calculated as single shift.</P>
> <UL>
> <LI>
> <P>Single shift depreciation will always calculate on a 365/365 basis. Double and Triple shift depreciation will calculate on regular working days in a year subject to seasonal, 180 days, and non-seasonal, 240 days.</P>
> <LI>
> <P>If the value model that is attached to the&nbsp;depreciation profile contains the “<STRONG>Straight line percentage</STRONG> or <STRONG>Reducing balance</STRONG> depreciation method,&nbsp;and shift a depreciation type is not defined in the value model, then no depreciation will be calculated for shifts.</P>
> <LI>
> <P>If shift depreciation is defined in the value model, but shift depreciation rates are not defined in the depreciation profile, then the standard depreciation rate will apply as single shift. If shift depreciation rates are defined, then shift depreciation rates will prevail over the standard rate. &nbsp;</P>
> <LI>
> <P>The total number of working days for single, double, or triple shift in a period cannot exceed the number of days that are defined in the ledger period.</P>
> <LI>
> <P>Depreciation for non-working days (Calendar days in a period less the days defined in a ledger period) is calculated as single shift.</P></LI></UL>



## Shift depreciation formulas

Refer to the following table for different formulas that are used to calculate the shift depreciation.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of depreciation method</p></th>
<th><p>Type of industry</p></th>
<th><p>Number of working days for the industry</p></th>
<th><p>Formula</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Straight-line percentage method</p></td>
<td><p>Seasonal</p></td>
<td><p>More than the number of days that are defined in the <strong>Min. working days for seasonal industries</strong> field. Click <strong>Fixed assets</strong> &gt; <strong>Common</strong> &gt; <strong>Fixed assets</strong> &gt; <strong>Fixed assets</strong>.</p></td>
<td><p>[(Cost of acquisition – Scrap value) * Percentage that is defined for the type of shift] * Number of days that the asset is used for during the period ÷ Total number of working days in a year</p></td>
</tr>
<tr class="even">
<td><p>Straight-line percentage method</p></td>
<td><p>Seasonal</p></td>
<td><p>Less than the number of days that are defined in the <strong>Min. working days for seasonal industries</strong> field Click <strong>Fixed assets</strong> &gt; <strong>Common</strong> &gt; <strong>Fixed assets</strong> &gt; <strong>Fixed assets</strong>.</p></td>
<td><p>[(Cost of acquisition – Scrap value) * Percentage that is defined for the type of shift] * Number of days that the asset is used for during the period ÷ Minimum number of working days for seasonal industries (180 days)</p></td>
</tr>
<tr class="odd">
<td><p>Straight-line percentage method</p></td>
<td><p>Non-seasonal</p></td>
<td><p>More than the number of days that are defined in the <strong>Min. working days for non-seasonal industries</strong> field Click <strong>Fixed assets</strong> &gt; <strong>Common</strong> &gt; <strong>Fixed assets</strong> &gt; <strong>Fixed assets</strong>.</p></td>
<td><p>[(Cost of acquisition – Scrap value) * Percentage that is defined for the type of shift] * Number of days that the asset is used for during the period ÷ Total number of working days in a year</p></td>
</tr>
<tr class="even">
<td><p>Straight-line percentage method</p></td>
<td><p>Non-seasonal</p></td>
<td><p>Less than the number of days that are defined in the <strong>Min. working days for non-seasonal industries</strong> field Click <strong>Fixed assets</strong> &gt; <strong>Common</strong> &gt; <strong>Fixed assets</strong> &gt; <strong>Fixed assets</strong>.</p></td>
<td><p>[(Cost of acquisition – Scrap value) * Percentage that is defined for the type of shift] * Number of days that the asset is used for during the period ÷ Minimum number of working days for non-seasonal industries (240 days)</p></td>
</tr>
<tr class="odd">
<td><p>Reducing-balance method</p></td>
<td><p>Seasonal</p></td>
<td><p>More than the number of days that are defined in the <strong>Min. working days for seasonal industries</strong> field Click <strong>Fixed assets</strong> &gt; <strong>Common</strong> &gt; <strong>Fixed assets</strong> &gt; <strong>Fixed assets</strong>.</p></td>
<td><p>[(Written-down value – Scrap value) * Percentage that is defined for the type of shift] * Number of days that the asset is used for during the period ÷ Total number of working days in a year</p></td>
</tr>
<tr class="even">
<td><p>Reducing-balance method</p></td>
<td><p>Seasonal</p></td>
<td><p>Less than the number of days that are defined in the <strong>Min. working days for seasonal industries</strong> field Click <strong>Fixed assets</strong> &gt; <strong>Common</strong> &gt; <strong>Fixed assets</strong> &gt; <strong>Fixed assets</strong>.</p></td>
<td><p>[(Written-down value – Scrap value) * Percentage that is defined for the type of shift] * Number of days that the asset is used for during the period ÷ Minimum number of working days for seasonal industries (180 days)</p></td>
</tr>
<tr class="odd">
<td><p>Reducing-balance method</p></td>
<td><p>Non-seasonal</p></td>
<td><p>More than the number of days that are defined in the <strong>Min. working days for non-seasonal industries</strong> field Click <strong>Fixed assets</strong> &gt; <strong>Common</strong> &gt; <strong>Fixed assets</strong> &gt; <strong>Fixed assets</strong>.</p></td>
<td><p>[(Written-down value – Scrap value) * Percentage that is defined for the type of shift] * Number of days that the asset is used for during the period ÷ Total number of working days in a year</p></td>
</tr>
<tr class="even">
<td><p>Reducing-balance method</p></td>
<td><p>Non-seasonal</p></td>
<td><p>Less than the number of days that are defined in the <strong>Min. working days for non-seasonal industries</strong> Click <strong>Fixed assets</strong> &gt; <strong>Common</strong> &gt; <strong>Fixed assets</strong> &gt; <strong>Fixed assets</strong>.</p></td>
<td><p>[(Written-down value – Scrap value) * Percentage that is defined for the type of shift] * Number of days that the asset is used for during the period ÷ Minimum number of working days for non-seasonal industries (240 days)</p></td>
</tr>
<tr class="odd">
<td><p>Straight-line percentage or Reducing-balance method</p></td>
<td><p>Seasonal or Non-seasonal</p></td>
<td><p>Click <strong>Fixed assets</strong> &gt; <strong>Setup</strong> &gt; <strong>Value models</strong>. Select the <strong>Override fixed asset calendar days?</strong> check box and specify the number of days in the <strong>Asset working days</strong> field.</p></td>
<td><p>[(Cost of acquisition or Written-down value – Scrap value) * Percentage that is defined for the type of shift] * Number of days that the asset is used for during the period ÷ Asset working days</p></td>
</tr>
</tbody>
</table>


Full depreciation is calculated if the value of an asset is less than or equal to the value that is specified in the **Max. acquisition value to avail full depreciation** Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**. In this case, the days that are specified in the **Min. working days for seasonal industries** field or the **Min. working days for non-seasonal industries** field are not considered for calculation of depreciation.

  


