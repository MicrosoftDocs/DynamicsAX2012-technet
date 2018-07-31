---
title: Product design manager security role (BOMProductDesignManager)
TOCTitle: Product design manager security role (BOMProductDesignManager)
ms:assetid: 8e93bff5-5232-4d7b-a551-dccd01a49cc4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527109(v=AX.60)
ms:contentKeyID: 37823161
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Product design manager security role (BOMProductDesignManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Product design manager security role represents a user who reviews product BOM structures.

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
<td><p>Configure AIF synchronization</p></td>
<td><p>AifSyncConfigure</p></td>
<td><p>Allows specifying filters on ports</p></td>
</tr>
<tr class="even">
<td><p>Approve BOMs</p></td>
<td><p>BOMBillsOfMaterialsApprove</p></td>
<td><p>Approve BOMs</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into BOM master</p></td>
<td><p>BOMBillsOfMaterialsMasterInquire</p></td>
<td><p>Respond to inquiries about BOM master data</p></td>
</tr>
<tr class="even">
<td><p>Enable BOM management process</p></td>
<td><p>BOMBillsOfMaterialsMgmtProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the BOM work process</p></td>
</tr>
<tr class="odd">
<td><p>Review BOM process performance</p></td>
<td><p>BOMBillsOfMaterialsProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve BOM process performance</p></td>
</tr>
<tr class="even">
<td><p>Enable case management</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CaseCaseManagementEnable</p></td>
<td><p>Set up policies and reference data to enable the case management process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into case management policies</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CaseCaseManagementPolicyInquire</p></td>
<td><p>Respond to inquiries about policies governing the case management process</p></td>
</tr>
<tr class="even">
<td><p>Review case process</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CaseCaseProcessReview</p></td>
<td><p>Monitor, analyze, and improve the case process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into case progress</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CaseCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into products for operations master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EcoResProductForOperationsMasterInquire</p></td>
<td><p>Respond to inquiries about products for operations master data</p></td>
</tr>
<tr class="odd">
<td><p>Enable the product management process</p></td>
<td><p>EcoResProductManagementProcessEnable</p></td>
<td><p>Set up policies and reference data for the product management process</p></td>
</tr>
<tr class="even">
<td><p>Maintain release of products</p></td>
<td><p>EcoResProductRelease</p></td>
<td><p>Release products to individual companies</p></td>
</tr>
<tr class="odd">
<td><p>Review release of products process performance</p></td>
<td><p>EcoResProductReleaseProcessPerformRevie</p></td>
<td><p>Monitor, analyze, and improve the product release process</p></td>
</tr>
<tr class="even">
<td><p>Approve and activate product changes</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EngChgCaseApproveAndActivate</p></td>
<td><p>Authorize changes related to a product change case</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into product change cases</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EngChgCaseInquire</p></td>
<td><p>Respond to inquiries about product change cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into related inventory status</p></td>
<td><p>InventRelatedInventoryStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the related inventory</p></td>
</tr>
<tr class="odd">
<td><p>Maintain barcode master</p></td>
<td><p>InventRFIDBarcodeMasterMaintain</p></td>
<td><p>Maintain bar code and GTIN identifiers</p></td>
</tr>
<tr class="even">
<td><p>Enable product builder modeling and configuration process</p></td>
<td><p>PBAProdBuilderModelConfigProcessEnable</p></td>
<td><p>Set up policies and reference data to enable product builder modeling and configuration process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into product builder definitions master</p></td>
<td><p>PBAProductBuilderDefinitionMasterInquir</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approve product builder model master</p></td>
<td><p>PBAProductBuilderModelMasterApprove</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into product builder model master</p></td>
<td><p>PBAProductBuilderModelMasterInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain sites solution in Product information management module</p></td>
<td><p>PBASitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Approve product configuration model version</p></td>
<td><p>PCProductConfigModelVersionApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into product configuration model versions</p></td>
<td><p>PCProductConfigModelVersionInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into product configuration model master</p></td>
<td><p>PCProductConfigurationModelMasterInquir</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable product configuration modeling process</p></td>
<td><p>PCProductConfigurationModelProcessEnabl</p></td>
<td><p>Set up policies and reference data to enable the product configuration modeling process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain inventory setup print management settings</p></td>
<td><p>PrintMgmtInventParametersSetupMaintain</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


