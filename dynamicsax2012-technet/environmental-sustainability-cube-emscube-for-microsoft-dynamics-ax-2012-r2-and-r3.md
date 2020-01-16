---
title: Environmental sustainability cube (EMSCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Environmental sustainability cube (EMSCube)
ms:assetid: 0febff0a-7c34-49d5-a85b-34d890ac702d
ms:mtpsurl: https://technet.microsoft.com/library/JJ710383(v=AX.60)
ms:contentKeyID: 49384275
author: Khairunj
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Environmental sustainability cube (EMSCube) for Microsoft Dynamics AX 2012 R2 and R3 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Environmental sustainability cube for Microsoft Dynamics AX provides data that can help you track your organization’s energy consumption and greenhouse gas emissions. Therefore, your organization can take a more proactive approach to environmental issues. This article provides details about the cube.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/JJ710380.TopicIcons_Reference(AX.60).png" title="Reference" alt="Reference" />
<p>Deployment</p>
<p>Configuration keys</p>
<p>Tables and views</p>
<p>Measures</p>
<p>Calculated measures</p>
<p>Key performance indicators</p>
<p>Security</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-r2-and-r3.md">Cube and KPI reference for Microsoft Dynamics AX 2012 R2 and R3</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md">Cube and KPI reference for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack</a></p></td>
</tr>
</tbody>
</table>


## Deployment

The Environmental sustainability cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Environmental sustainability cube:

  - Environmental sustainability (EMS)

## Tables and views

The Environmental sustainability cube uses data from the following tables and views:

  - EMSProcess table

  - EMSSubstance table

  - EMSSubstanceCategory table

  - EMSDailyFlowView view

## Measures

The Environmental sustainability cube includes the following measure groups.

## Substance flow details

This measure group is based on the EMSDailyFlowView view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Substance flow details count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The count of flow transactions.
  </p> </td>
    <td rowspan="6"> <p>
   
	 Company
  </p> <p>
   
	 Substance flows
  </p> <p>
   
	 Process (process – destination)
  </p> <p>
   
	 Substance
  </p> <p>
   
	 Substance category
  </p> <p>
   
	 Process (process – source)
  </p> <p>
   
	 Date (transaction date)
  </p> <p>
   
	 Date (date – date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Accounting currency amount by day
  </p> </td>
    <td> <p>
   
	 EMSDailyFlowView.AccountingCurrencyAmountByDay
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The sum of flow monetary values, in the accounting currency.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Total mass
  </p> </td>
    <td> <p>
   
	 EMSDailyFlowView.TotalMass
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total mass, expressed as the sum of quantities of substance flows of a given substance, multiplied by the value in the <strong xmlns="http://www.w3.org/1999/xhtml">Mass (Unknown) per unit</strong> field on the <strong xmlns="http://www.w3.org/1999/xhtml">Substances</strong> form (<strong xmlns="http://www.w3.org/1999/xhtml">Compliance and internal controls</strong> &gt; <strong xmlns="http://www.w3.org/1999/xhtml">Setup</strong> &gt; <strong xmlns="http://www.w3.org/1999/xhtml">Environmental sustainability</strong> &gt; <strong xmlns="http://www.w3.org/1999/xhtml">Substances</strong>).
  </p> <p>
   
	 The default value is zero. Not changing the value will result in zero values for this measure.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Total volume
  </p> </td>
    <td> <p>
   
	 EMSDailyFlowView.TotalVolume
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total volume, expressed as the sum of quantities of substance flows of a given substance, multiplied by the value in the <strong xmlns="http://www.w3.org/1999/xhtml">Volume (Unknown) per unit</strong> field on the <strong xmlns="http://www.w3.org/1999/xhtml">Substances</strong> form (<strong xmlns="http://www.w3.org/1999/xhtml">Compliance and internal controls</strong> &gt; <strong xmlns="http://www.w3.org/1999/xhtml">Setup</strong> &gt; <strong xmlns="http://www.w3.org/1999/xhtml">Environmental sustainability</strong> &gt; <strong xmlns="http://www.w3.org/1999/xhtml">Substances</strong>).
  </p> <p>
   
	 The default value is zero. Not changing the value will result in zero values for this measure.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Total recycled
  </p> </td>
    <td> <p>
   
	 EMSDailyFlowView.TotalMassRecycled
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total mass of recycled material. The value is the product of the Total mass value, found above, multiplied by the sum of the <strong xmlns="http://www.w3.org/1999/xhtml">Percent post-consumer</strong> and <strong xmlns="http://www.w3.org/1999/xhtml">Percent pre-consumer</strong> fields on the <strong xmlns="http://www.w3.org/1999/xhtml">Substances</strong> form (<strong xmlns="http://www.w3.org/1999/xhtml">Compliance and internal controls</strong> &gt; <strong xmlns="http://www.w3.org/1999/xhtml">Setup</strong> &gt; <strong xmlns="http://www.w3.org/1999/xhtml">Environmental sustainability</strong> &gt; <strong xmlns="http://www.w3.org/1999/xhtml">Substances</strong>).
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Base quantity
  </p> </td>
    <td> <p>
   
	 EMSDailyFlowView.SubstanceBaseQtyByDay
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the raw quantity of a set of flow transactions.
  </p> </td>
  </tr>
</table>


## Exchange rates by day

This measure group is based on the BIExchangeRateView view and includes the following measures.

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
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Exchange rate</p></td>
<td><p>BIExchangeRateView.CrossRate</p></td>
<td><p>Max</p></td>
<td><p>The exchange rate.</p></td>
<td><p>Currency</p>
<p>Date (exchange rate date)</p>
<p>Analysis currency</p></td>
</tr>
</tbody>
</table>


## Calculated measures

The Environmental sustainability cube contains the following calculated measures.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Calculated measure</p></th>
<th><p>Aggregation</p></th>
<th><p>Associated measure group</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Direct energy</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The amount of direct energy (such as gasoline or natural gas) consumed by the organization.</p>
<p>The value is found by identifying substance categories (<strong>Compliance and internal controls</strong> &gt; <strong>Setup</strong> &gt; <strong>Environmental sustainability</strong> &gt; <strong>Substance categories</strong>) which have a value of <strong>Direct energy</strong> in the <strong>Category type</strong> field. Also required is that the source process is either Scope Secondary or Tertiary, and that the destination process is Scope Primary.</p></td>
</tr>
<tr class="even">
<td><p>Indirect energy</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The amount of indirect energy (such as electricity or heating services) consumed by the organization.</p>
<p>The value is found by identifying substance categories (<strong>Compliance and internal controls</strong> &gt; <strong>Setup</strong> &gt; <strong>Environmental sustainability</strong> &gt; <strong>Substance categories</strong>) which have a value of <strong>Indirect energy</strong> in the <strong>Category type</strong> field. Also required is that the source process is either Scope Secondary or Tertiary, and that the destination process is Scope Primary.</p></td>
</tr>
<tr class="odd">
<td><p>Direct and indirect GHGs</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The mass of direct and indirect greenhouse gas emissions produced by the organization’s processes.</p>
<p>The value is found by identifying substance categories (<strong>Compliance and internal controls</strong> &gt; <strong>Setup</strong> &gt; <strong>Environmental sustainability</strong> &gt; <strong>Substance categories</strong>) which have a value of <strong>Greenhouse gas</strong> in the <strong>Category type</strong> field, and where the scope of the substance flow is either Primary or Secondary.</p>
<p>The sum of quantities is multiplied by the total mass value found for the substance.</p></td>
</tr>
<tr class="even">
<td><p>Other indirect GHGs</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The mass of other indirect greenhouse gas emissions (such as employee commuting or business travel) produced by the organization’s processes.</p>
<p>The value is found by identifying substance categories (<strong>Compliance and internal controls</strong> &gt; <strong>Setup</strong> &gt; <strong>Environmental sustainability</strong> &gt; <strong>Substance categories</strong>) which have a value of <strong>Greenhouse gas</strong> in the <strong>Category type</strong> field. Also required is that the scope of the substance flow is Tertiary, and that the destination process of the substance flow is Sphere: Ecosphere.</p>
<p>The sum of quantities is multiplied by the total mass value found for the substance.</p></td>
</tr>
<tr class="odd">
<td><p>Water consumption</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The volume of water consumed by the organization.</p>
<p>The value is found by identifying substance categories (<strong>Compliance and internal controls</strong> &gt; <strong>Setup</strong> &gt; <strong>Environmental sustainability</strong> &gt; <strong>Substance categories</strong>) which have a value of <strong>Water</strong> in the <strong>Category type</strong> field. Also required is that the source process is either Scope Secondary or Tertiary, and that the destination process is Primary.</p>
<p>The sum of quantities is multiplied by the total mass value found for the substance.</p></td>
</tr>
<tr class="even">
<td><p>Materials consumption</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The mass of materials consumed by the organization.</p>
<p>The value is found by identifying substance categories (<strong>Compliance and internal controls</strong> &gt; <strong>Setup</strong> &gt; <strong>Environmental sustainability</strong> &gt; <strong>Substance categories</strong>) which have a value of <strong>Raw materials</strong> in the <strong>Category type</strong> field. Also required is that the source process is either Scope Secondary or Tertiary, and that the destination process is Primary.</p>
<p>The sum of quantities is multiplied by the total mass value found for the substance.</p></td>
</tr>
<tr class="odd">
<td><p>Recycled content</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The mass of recycled materials consumed by the organization.</p>
<p>The value is found by identifying substance categories (<strong>Compliance and internal controls</strong> &gt; <strong>Setup</strong> &gt; <strong>Environmental sustainability</strong> &gt; <strong>Substance categories</strong>) which have a value of <strong>Raw materials</strong> in the <strong>Category type</strong> field. Also required is that the source process is either Scope Secondary or Tertiary, and that the destination process is Primary.</p>
<p>The sum of quantities is multiplied by the recycled percentage value of the total mass value found for the substance.</p></td>
</tr>
<tr class="even">
<td><p>Waste water</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The volume of waste water produced by the organization.</p>
<p>The value is found by identifying substance categories (<strong>Compliance and internal controls</strong> &gt; <strong>Setup</strong> &gt; <strong>Environmental sustainability</strong> &gt; <strong>Substance categories</strong>) which have a value of <strong>Water</strong> in the <strong>Category type</strong> field. Also required is that the source process is Primary, and that the destination process is either Secondary or Tertiary.</p>
<p>The resulting value is multiplied with the total volume value for the substance.</p></td>
</tr>
<tr class="odd">
<td><p>Solid waste</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The mass of solid waste produced by the organization.</p>
<p>The value is found by identifying substance categories (<strong>Compliance and internal controls</strong> &gt; <strong>Setup</strong> &gt; <strong>Environmental sustainability</strong> &gt; <strong>Substance categories</strong>) which have a value of <strong>Solid waste</strong> in the <strong>Category type</strong> field. Also required is that the source process is Primary, and that the destination process is either Secondary or Tertiary.</p>
<p>The resulting value is multiplied with the total mass value for the substance.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The following sections describe the key performance indicators (KPIs) in the Environmental sustainability cube.

## KPI calculations

The following table lists the KPIs that are associated with the Environmental sustainability cube. You can use the information in the following table to help verify the information in your KPIs.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>KPI</p></th>
<th><p>Associated measure group</p></th>
<th><p>Calculation</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Direct energy</p></td>
<td><p>All</p></td>
<td><p>The amount of direct energy (such as gasoline or natural gas) consumed by the organization.</p></td>
</tr>
<tr class="even">
<td><p>Indirect energy</p></td>
<td><p>All</p></td>
<td><p>The amount of indirect energy (such as electricity or heating services) consumed by the organization.</p></td>
</tr>
<tr class="odd">
<td><p>Direct and indirect GHGs</p></td>
<td><p>All</p></td>
<td><p>The mass of direct and indirect greenhouse gas emissions produced by the organization’s processes.</p></td>
</tr>
<tr class="even">
<td><p>Other indirect GHGs</p></td>
<td><p>All</p></td>
<td><p>The mass of other indirect greenhouse gas emissions (such as employee commuting or business travel) produced by the organization’s processes.</p></td>
</tr>
<tr class="odd">
<td><p>Water consumption</p></td>
<td><p>All</p></td>
<td><p>The volume of water consumed by the organization.</p></td>
</tr>
<tr class="even">
<td><p>Materials consumption</p></td>
<td><p>All</p></td>
<td><p>The mass of materials consumed by the organization.</p></td>
</tr>
<tr class="odd">
<td><p>Recycled content</p></td>
<td><p>All</p></td>
<td><p>The mass of recycled materials consumed by the organization.</p></td>
</tr>
<tr class="even">
<td><p>Waste water</p></td>
<td><p>All</p></td>
<td><p>The volume of waste water produced by the organization.</p></td>
</tr>
<tr class="odd">
<td><p>Solid waste</p></td>
<td><p>All</p></td>
<td><p>The mass of solid waste produced by the organization.</p></td>
</tr>
</tbody>
</table>


## Role Centers

The following table lists the Role Centers and web parts that display the KPIs associated with the Environmental sustainability cube.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Role Center</p></th>
<th><p>Web parts and KPIs</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Environmental manager</p></td>
<td><p>KPI list:</p>
<ul>
<li><p>Direct energy</p></li>
<li><p>Indirect energy</p></li>
<li><p>Direct and indirect GHGs</p></li>
<li><p>Other indirect GHGs</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Security

The Environmental sustainability cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Chief executive officer

  - Environmental manager

  


