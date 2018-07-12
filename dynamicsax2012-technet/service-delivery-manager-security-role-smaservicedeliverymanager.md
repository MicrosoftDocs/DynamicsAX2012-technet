---
title: Service delivery manager security role (SMAServiceDeliveryManager)
TOCTitle: Service delivery manager security role (SMAServiceDeliveryManager)
ms:assetid: 07f00cf4-c4f2-4233-bc11-b69cfd87ed43
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh544038(v=AX.60)
ms:contentKeyID: 37823119
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Service delivery manager security role (SMAServiceDeliveryManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Service delivery manager security role represents a user who reviews and enables the service order process.

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
<td><p>Approve posting of service orders</p></td>
<td><p>SMAServiceOrdersJournalize</p></td>
<td><p>Journalize service orders</p></td>
</tr>
<tr class="even">
<td><p>Approve posting of service subscriptions</p></td>
<td><p>SMAServiceSubscriptionsJournalize</p></td>
<td><p>Journalize accrued service subscription revenue</p></td>
</tr>
<tr class="odd">
<td><p>Enable calendar management process</p></td>
<td><p>WorkCalendarsEnable</p></td>
<td><p>Set up policies and reference data to enable the use of calendars</p></td>
</tr>
<tr class="even">
<td><p>Enable case management</p></td>
<td><p>CaseCaseManagementEnable</p></td>
<td><p>Set up policies and reference data to enable the case management process</p></td>
</tr>
<tr class="odd">
<td><p>Enable service agreement process</p></td>
<td><p>SMAServiceAgreementProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the service agreement process</p></td>
</tr>
<tr class="even">
<td><p>Enable service order process</p></td>
<td><p>SMAServiceOrderProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the service order process</p></td>
</tr>
<tr class="odd">
<td><p>Enable service subscription process</p></td>
<td><p>SMAServiceSubscriptionProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the service subscription process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into contact master</p></td>
<td><p>smmContactMasterInquire</p></td>
<td><p>Respond to inquiries about contact master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer master</p></td>
<td><p>CustCustomerMasterInquire</p></td>
<td><p>Respond to inquiries about customer master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into inventory status</p></td>
<td><p>InventStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the inventory</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into limited worker information</p></td>
<td><p>HcmLimitedWorkerInquire</p></td>
<td><p>Respond to inquiries about limited worker information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project master</p></td>
<td><p>ProjProjectMasterInquire</p></td>
<td><p>Respond to inquiries about project master information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into service agreement master</p></td>
<td><p>SMAServiceAgreementMasterInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into service event groups</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InquireIntoServiceEventGroups_IN</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into service orders</p></td>
<td><p>SMAServiceOrderProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into service records (Enterprise Portal)</p></td>
<td><p>SMAEPServiceEPInquire</p></td>
<td><p>View current service records for external customers</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into service subscription sales price master</p></td>
<td><p>SMAServiceSubscriptionSalesPriceInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into service subscriptions</p></td>
<td><p>SMAServiceSubscriptionProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain calendar master</p></td>
<td><p>WorkCalendarMasterMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain print management settings</p></td>
<td><p>PrintMgmtPrintManagementSettingsMaintai</p></td>
<td><p>Maintain print management settings</p></td>
</tr>
<tr class="odd">
<td><p>Maintain service agreement master</p></td>
<td><p>SMAServiceAgreementMasterMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain service event groups</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MaintainServiceEventGroups_IN</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain service object master</p></td>
<td><p>SMAServiceObjectMasterMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain service orders</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>SMAServiceOrdersMaintain</p></td>
<td><p>Document and record service business events</p></td>
</tr>
<tr class="odd">
<td><p>Maintain service subscription sales price master</p></td>
<td><p>SMAServiceSubscrSalesPriceMasterMaintai</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain service subscriptions</p></td>
<td><p>SMAServiceSubscriptionSMAintain</p></td>
<td><p>Document and record service subscriptions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sites service solution in service management module</p></td>
<td><p>SMASitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Review service agreement process performance</p></td>
<td><p>SMAServiceAgreementProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve service agreement process performance</p></td>
</tr>
<tr class="odd">
<td><p>Review service order process performance</p></td>
<td><p>SMAServiceOrderProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve service order process performance</p></td>
</tr>
<tr class="even">
<td><p>Review service subscription process performance</p></td>
<td><p>SMAServiceSubscriptionProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve service subscription process performance</p></td>
</tr>
<tr class="odd">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="even">
<td><p>View fiscal document source texts</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>FiscalDocumentSourceTextView_BR</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

