---
title: Dispatcher security role (SMADispatcher)
TOCTitle: Dispatcher security role (SMADispatcher)
ms:assetid: ebb587d2-60ca-4e72-bd89-a73fc53ab1e3
ms:mtpsurl: https://technet.microsoft.com/library/Hh527148(v=AX.60)
ms:contentKeyID: 37823199
author: tonyafehr
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Dispatcher security role (SMADispatcher) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Dispatcher security role represents a user who organizes service technicians and prioritizes service orders.

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
<td><p>Change service order stages</p></td>
<td><p>SMAServiceOrderStageMaintain</p></td>
<td><p>Change the stage of the service order</p></td>
</tr>
<tr class="even">
<td><p>Inquire into BOM calculations</p></td>
<td><p>BOMBillsOfMaterialsCalcStatusInquire</p></td>
<td><p>Inquire into BOM calculations</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into contact master</p></td>
<td><p>smmContactMasterInquire</p></td>
<td><p>Respond to inquiries about contact master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer master</p></td>
<td><p>CustCustomerMasterInquire</p></td>
<td><p>Respond to inquiries about customer master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into service agreement master</p></td>
<td><p>SMAServiceAgreementMasterInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into service case progress</p></td>
<td><p>CaseServiceCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of service cases</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into service event groups</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InquireIntoServiceEventGroups_IN</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into service order reference data</p></td>
<td><p>SMAServiceOrderReferenceDataInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into service orders</p></td>
<td><p>SMAServiceOrderProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain project sales packing slips</p></td>
<td><p>ProjProjectSalesPackingSlipMaintain</p></td>
<td><p>Document and record project sales packing slip</p></td>
</tr>
<tr class="odd">
<td><p>Maintain service event groups</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MaintainServiceEventGroups_IN</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain service orders</p></td>
<td><p>SMAServiceOrdersMaintain</p></td>
<td><p>Document and record service business events</p></td>
</tr>
<tr class="odd">
<td><p>Maintain technician access to service (Enterprise Portal)</p></td>
<td><p>SMAEPTechServiceMaintain</p></td>
<td><p>Maintain service data for field service technicians</p></td>
</tr>
<tr class="even">
<td><p>Maintain web service orders</p></td>
<td><p>SMAWebServiceOrdersMaintain</p></td>
<td><p>Maintain and transfer service orders created in the Enterprise Portal</p></td>
</tr>
<tr class="odd">
<td><p>Perform service order periodic jobs</p></td>
<td><p>SMAServiceOrderPeriodicMaintain</p></td>
<td><p>Periodic batch-oriented service order maintenance</p></td>
</tr>
<tr class="even">
<td><p>View fiscal document</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>FiscalDocumentInquire_BR</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


