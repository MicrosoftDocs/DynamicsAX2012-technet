---
title: (FRA) About RB/SL depreciation
TOCTitle: (FRA) About RB/SL depreciation
ms:assetid: 821e4927-89f8-46c4-8d11-82e8f8ffcd77
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571558(v=AX.60)
ms:contentKeyID: 36058364
ms.date: 04/25/2014
mtps_version: v=AX.60
---

# (FRA) About RB/SL depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

RB/SL reducing balance is a depreciation method that calculates depreciation amounts using the reducing balance depreciation method and the straight-line depreciation method, and then uses the greater of the two calculated depreciation amounts as the RB/SL reducing balance depreciation amount. When you set up a fixed asset depreciation profile and select **RB/SL (France)** in the **Method** field in the **Depreciation profiles** form, the depreciation of the fixed assets that are assigned to the depreciation profile is based on the service life of the assets. For more information about setting up depreciation profiles, see [Set up depreciation profiles](set-up-depreciation-profiles.md).

You can use the **RB/SL factors** form to set up reducing balance factors by service life for fixed assets. For more information, see [(FRA) RB/SL factors (form)](https://technet.microsoft.com/en-us/library/aa574244\(v=ax.60\)).

The reducing balance percentage is calculated for each fixed asset, depending on the service life of the asset. To calculate RB/SL depreciation, the depreciation starting date is always the first day of the month, and the depreciation ending date is always the end of the fiscal year. The RB/SL depreciation is the greater of either the reducing balance depreciation amount or the straight line depreciation amount.

For example, a fixed asset with an acquisition price is placed into service on February 10, 2011, and is depreciated over five years by using the RB/SL method. The following table displays the depreciation amounts and the book value for the asset for each year.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Year</p></th>
<th><p>Straight line</p></th>
<th><p>Reducing balance</p></th>
<th><p>RBSL (largest depreciation amount)</p></th>
<th><p>Book value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>2011</p></td>
<td><p>183.33</p></td>
<td><p>320.83</p></td>
<td><p>320.83</p></td>
<td><p>679.17</p></td>
</tr>
<tr class="even">
<td><p>2012</p></td>
<td><p>169.79</p></td>
<td><p>237.71</p></td>
<td><p>237.71</p></td>
<td><p>441.46</p></td>
</tr>
<tr class="odd">
<td><p>2013</p></td>
<td><p>147.15</p></td>
<td><p>154.51</p></td>
<td><p>154.51</p></td>
<td><p>286.95</p></td>
</tr>
<tr class="even">
<td><p>2014</p></td>
<td><p>143.48</p></td>
<td><p>100.43</p></td>
<td><p>143.48</p></td>
<td><p>143.47</p></td>
</tr>
<tr class="odd">
<td><p>2015</p></td>
<td><p>143.47</p></td>
<td><p>50.21</p></td>
<td><p>143.47</p></td>
<td><p>0.00</p></td>
</tr>
<tr class="even">
<td><p>Total</p></td>
<td><p>N/A</p></td>
<td><p>N/A</p></td>
<td><p>1,000.00</p></td>
<td><p>N/A</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>If you depreciated an asset by using a fixed asset software other than Microsoft Dynamics AX, you must post the acquisition and the accumulated depreciation in Microsoft Dynamics AX for the period before you started using Microsoft Dynamics AX. For example, if you started using Microsoft Dynamics AX on January 1, 2011, you must post the acquisition and accumulated depreciation in Microsoft Dynamics AX for the period ending December 31, 2010.</P>
> <P>After you post the acquisition, you must change the acquisition date to the correct date from your previous software and enter the remaining life of the asset. You can then depreciate the asset as usual, starting January 1, 2011.</P>



## See also

[Depreciation profiles (form)](https://technet.microsoft.com/en-us/library/aa549887\(v=ax.60\))

[Create a depreciation profile](create-a-depreciation-profile.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

