---
title: Cost accountant security role (InventCostAccountant)
TOCTitle: Cost accountant security role (InventCostAccountant)
ms:assetid: 859b19f6-8921-46e4-9971-f6b5f340c350
ms:mtpsurl: https://technet.microsoft.com/library/Hh527105(v=AX.60)
ms:contentKeyID: 37823157
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Cost accountant security role (InventCostAccountant) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Cost accountant security role represents a user who documents and responds to costs, inventory valuations, and cost accounting events and inquiries.

## Duties

By default, this security role is assigned the following duties in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty name</p></th>
<th><p>Duty AOT name</p></th>
<th><p>Duty description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Enable financial reports generator</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RRGEnable</p></td>
<td><p>Set up templates, report format, and other information to enable the financial reports generator</p></td>
</tr>
<tr class="even">
<td><p>Enable the lean costing process</p></td>
<td><p>LeanCostingProcessEnable</p></td>
<td><p>Set up policies and reference data to enable costing for lean manufacturing</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about accounting data</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>LedgerRRGGInquire</p></td>
<td><p>Respond to inquiries about accounting data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into Absorption Costs</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ACOInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cost accounting calculation status</p></td>
<td><p>COSCostAccountingCalcStatusInquire</p></td>
<td><p>Inquire into status information within the process of cost accounting</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cost accounting master</p></td>
<td><p>COSCostAccountingMasterInquire</p></td>
<td><p>Respond to inquiries about cost accounting master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cost accounting status</p></td>
<td><p>COSCostAccountingStatusInquire</p></td>
<td><p>Respond to inquiries about the performance of the cost accounting process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cost master</p></td>
<td><p>InventItemPriceCostMasterInquire</p></td>
<td><p>Respond to inquiries about cost master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cost status</p></td>
<td><p>InventCostCostStatusInquire</p></td>
<td><p>Respond to inquiries about the performance of the cost process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into inventory valuation policies (cur.)</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InvStdCostInvValuatPoliciesSecInquire_RU</p></td>
<td><p>Respond to inquiries about the policies governing the inventory valuation in the second currency</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into inventory valuation status</p></td>
<td><p>InventValueInvValuationStatusInquire</p></td>
<td><p>Respond to inquiries about the performance of the inventory valuation process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into inventory valuation status</p></td>
<td><p>InvValueInvValuatStatusSecCurInquire_RU</p></td>
<td><p>Respond to inquiries about the performance of the inventory valuation process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into related inventory status</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventRelatedInventoryStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the related inventory</p></td>
</tr>
<tr class="even">
<td><p>Maintain Absorption Costs</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ACOMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain activation of cost</p></td>
<td><p>InventPriceActivationOfCostAuthorize</p></td>
<td><p>Authorize the activation of costing versions</p></td>
</tr>
<tr class="even">
<td><p>Maintain cost accounting calculation</p></td>
<td><p>COSCostAccountingCalculationMaintain</p></td>
<td><p>Maintain the cost accounting calculation versions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain inventory valuation</p></td>
<td><p>InventClosingInventoryValuationMaintain</p></td>
<td><p>Document and record inventory valuation</p></td>
</tr>
<tr class="even">
<td><p>Maintain inventory valuation (cur.)</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InvClosingInventValuatSecCurMaintain_RU</p></td>
<td><p>Document and record inventory valuation in the second currency</p></td>
</tr>
<tr class="odd">
<td><p>Review inventory valuation process performance (cur.)</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InvValueInvValuatProcPerfSecCurReview_RU</p></td>
<td><p>Monitor inventory valuation in the second currency</p></td>
</tr>
<tr class="even">
<td><p>Inquire into BOM calculations</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>BOMBillsOfMaterialsCalcStatusInquire</p></td>
<td><p>Inquire into BOM calculations</p></td>
</tr>
</tbody>
</table>

  


