---
title: Information technology manager security role (SysServerITManager)
TOCTitle: Information technology manager security role (SysServerITManager)
ms:assetid: 4eb3e209-f8a9-4ccc-a999-7565f3110b56
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527087(v=AX.60)
ms:contentKeyID: 37823139
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Information technology manager security role (SysServerITManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Information technology manager security role represents a user who maintains servers and software for Microsoft Dynamics AX. A user in this role maintains and configures settings for batch servers, load balancing, databases, Enterprise Portal, services, and workflow.

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
<td><p>Maintain and configure integrations</p></td>
<td><p>AIFIntegrationMaintain</p></td>
<td><p>Maintain and configure inbound and outbound services and integrations</p></td>
</tr>
<tr class="even">
<td><p>Configure AIF synchronization</p></td>
<td><p>AifSyncConfigure</p></td>
<td><p>Allows specifying filters on ports</p></td>
</tr>
<tr class="odd">
<td><p>Maintain SQL Server Analysis Services projects</p></td>
<td><p>BIAnalysisProjectsMaintain</p></td>
<td><p>Create or update SQL Server Analysis Services projects</p></td>
</tr>
<tr class="even">
<td><p>Maintain the calendars that are used for business intelligence</p></td>
<td><p>BICalendarsMaintain</p></td>
<td><p>Create or update the calendars that are used for business intelligence</p></td>
</tr>
<tr class="odd">
<td><p>Enable Case Security</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CaseCategorySecurityEnable</p></td>
<td><p>Set up policy data to enable access to case management</p></td>
</tr>
<tr class="even">
<td><p>Maintain Configurator definitions and processes</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ConfiguratorMaintain_BR</p></td>
<td><p>Access to the Definition group, Layout group, Export/import of groups, and Configurator export utility tool</p></td>
</tr>
<tr class="odd">
<td><p>Maintain shared cues</p></td>
<td><p>CueMaintain</p></td>
<td><p>Maintain shared cues</p></td>
</tr>
<tr class="even">
<td><p>Maintain sites solution in accounts receivable module</p></td>
<td><p>CustSitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into global address book master</p></td>
<td><p>DirAddressBookMasterInquire</p></td>
<td><p>Respond to inquiries about global address book master</p></td>
</tr>
<tr class="even">
<td><p>Maintain global address book master</p></td>
<td><p>DirAddressBookMasterMaintain</p></td>
<td><p>Maintain global address book master</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into global address book policies</p></td>
<td><p>DirAddressBookPolicyInquire</p></td>
<td><p>Respond to inquiries about policies governing the global address book process</p></td>
</tr>
<tr class="even">
<td><p>Enable the global address book process</p></td>
<td><p>DirAddressBookProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the global address book process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain online commerce batch jobs</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in versions prior to Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>DOCommerceBatchJobsMaintain</p></td>
<td><p>Run online commerce batch jobs</p></td>
</tr>
<tr class="even">
<td><p>Maintain Commerce Services duty</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in versions prior to Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>DOCommerceMaintain</p></td>
<td><p>Read, write, update Commerce Services duty</p></td>
</tr>
<tr class="odd">
<td><p>Maintain online product item list</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in versions prior to Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>DOCommerceOnlineProductsMaintain</p></td>
<td><p>Adds, updates, and deletes the Commerce Service account and configuration</p></td>
</tr>
<tr class="even">
<td><p>Maintains online sales orders</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in versions prior to Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>DOCommerceOnlineSalesOrdersMaintain</p></td>
<td><p>Maintains the online sales orders</p></td>
</tr>
<tr class="odd">
<td><p>Maintain online services accounts</p></td>
<td><p>DOCommonMaintain</p></td>
<td><p>Read, write, update Commerce Services duty</p></td>
</tr>
<tr class="even">
<td><p>Maintain external access</p></td>
<td><p>ECPExternalAccessMaintain</p></td>
<td><p>Document and record external access</p></td>
</tr>
<tr class="odd">
<td><p>Configure electronic fiscal document</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EFDocumentSetup_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable electronic document exchange</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ElectrDocExchangeEnable_RU</p></td>
<td><p>Set up templates, format, and other information to enable electronic document exchange</p></td>
</tr>
<tr class="odd">
<td><p>Maintain environmental flows</p></td>
<td><p>EMSFlowsMaintain</p></td>
<td><p>Document and record environmental flow transactions</p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic Role center URL</p></td>
</tr>
<tr class="odd">
<td><p>Maintain Enterprise Portal settings</p></td>
<td><p>EPSettingsMaintain</p></td>
<td><p>Enables administrators to maintain Enterprise Portal</p></td>
</tr>
<tr class="even">
<td><p>Inquire into address policies</p></td>
<td><p>LogisticsAddressPolicyInquire</p></td>
<td><p>Respond to inquiries about policies governing the address process</p></td>
</tr>
<tr class="odd">
<td><p>Enable address process</p></td>
<td><p>LogisticsAddressProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the address process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into address reference data</p></td>
<td><p>LogisticsAddressReferenceDataInquire</p></td>
<td><p>Respond to inquiries about address reference data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain KLADR</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MaintainKLADR_RU</p></td>
<td><p>Maintain Russian address classifier (KLADR) files</p></td>
</tr>
<tr class="even">
<td><p>Inquire into organizational model</p></td>
<td><p>OMOrganizationsInquire</p></td>
<td><p>Respond to inquiries about organization and organization hierarchy master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain and configure organizational model</p></td>
<td><p>OMOrganizationsMaintain</p></td>
<td><p>Create or update organizations and organization hierarchies</p></td>
</tr>
<tr class="even">
<td><p>Maintain print management settings</p></td>
<td><p>PrintMgmtPrintManagementSettingsMaintai</p></td>
<td><p>Maintain print management settings</p></td>
</tr>
<tr class="odd">
<td><p>Maintain Microsoft Project Server integration</p></td>
<td><p>ProjProjectServerIntegrationMaintain</p></td>
<td><p>Maintain Microsoft Project Server integration</p></td>
</tr>
<tr class="even">
<td><p>Maintain batch job to create purchase orders from purchase requisition</p></td>
<td><p>PurchReqPurchaseOrderGenBatchEnable</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Service operations for purchase requisitions</p></td>
<td><p>PurchReqPurchaseReqServiceOperations</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain performance of demand forecasting process</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ReqDemPlanPerformanceMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain setup of demand forecasting cubes</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ReqDemPlanSetupCubeMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable retail barcode masks</p></td>
<td><p>RetailBarcodeMasksEnable</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain Retail channels</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in versions prior to Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RetailChannelsMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>View retail channels</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RetailChannelsView</p></td>
<td><p>View retail channels</p></td>
</tr>
<tr class="odd">
<td><p>Commerce Services for Retail upgrade</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in versions prior to Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RetailCommSvcUpgrade</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain inventory availability service</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RetailInventAvailabilityMaintain</p></td>
<td><p>This is a (non-operational) duty which is concerned with handling technical aspects such as inventory calculation.</p></td>
</tr>
<tr class="odd">
<td><p>Manage Retail Store Connect</p></td>
<td><p>RetailSchedulerManage</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain Commerce Data Exchange: Real-time Service profiles</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RetailTransactionServiceProfilesMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain shipping carrier master</p></td>
<td><p>ShipCarrierMasterMaintain</p></td>
<td><p>Maintain master data for shipping carriers</p></td>
</tr>
<tr class="even">
<td><p>Maintain sites service solution, online pages, create new solutions, configuration and view checklist</p></td>
<td><p>SitesSvcMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain Sites service</p></td>
<td><p>SitesSvcMaintainService</p></td>
<td><p>Maintain Sites service and solutions</p></td>
</tr>
<tr class="even">
<td><p>Maintain sites service solution in service management module</p></td>
<td><p>SMASitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable activity process</p></td>
<td><p>smmActivityProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the activity process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into activity reference data</p></td>
<td><p>smmActivityReferenceDataInquire</p></td>
<td><p>Respond to inquiries about activity reference data</p></td>
</tr>
<tr class="odd">
<td><p>Enable the Sales and marketing process</p></td>
<td><p>smmCRMProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the Sales and marketing process</p></td>
</tr>
<tr class="even">
<td><p>Maintain reporting and business intelligence settings</p></td>
<td><p>SRSBISettingsMaintain</p></td>
<td><p>Configure and maintain reporting and business intelligence settings</p></td>
</tr>
<tr class="odd">
<td><p>Maintain Gregorian calendars</p></td>
<td><p>SRSGregorianCalendarsMaintain</p></td>
<td><p>Maintain the properties of Gregorian calendars</p></td>
</tr>
<tr class="even">
<td><p>Maintain Sites Solutions</p></td>
<td><p>SyncSolutionMaintainSolution</p></td>
<td><p>Maintaining Sites service solutions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain and assign role centers</p></td>
<td><p>SysClientRoleCenterMaintain</p></td>
<td><p>Maintain role centers and choose which roles and users should have access to specific role centers</p></td>
</tr>
<tr class="even">
<td><p>Maintain system settings</p></td>
<td><p>SysServerSettingsMaintain</p></td>
<td><p>Maintain and configure system settings such as the batch server</p></td>
</tr>
<tr class="odd">
<td><p>Maintain system parameters master</p></td>
<td><p>SystemParametersMasterMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain number sequence settings</p></td>
<td><p>SystemSequencesMaintain</p></td>
<td><p>Maintain and configure number sequences</p></td>
</tr>
<tr class="odd">
<td><p>Service operations for expense management</p></td>
<td><p>TrvTravelAndExpenseServiceOperations</p></td>
<td><p>Utilize service operations for expense management</p></td>
</tr>
<tr class="even">
<td><p>Maintain user requests</p></td>
<td><p>UserRequestMaintain</p></td>
<td><p>Complete user management tasks for user requests</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sites service solution in account payable module</p></td>
<td><p>VendSitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain workflow and alerts settings</p></td>
<td><p>WorkflowAlertsSettingsMaintain</p></td>
<td><p>Maintain and configure workflow and alerts settings</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into performance of workflow participants</p></td>
<td><p>WorkflowViewWorkflowParticipantsPerf</p></td>
<td><p>Respond to inquiries about status on performance of workflow participants</p></td>
</tr>
<tr class="even">
<td><p>Inquire into workflow performance</p></td>
<td><p>WorkflowViewWorkflowPerf</p></td>
<td><p>View reports about the performance of workflows</p></td>
</tr>
</tbody>
</table>


## Privileges

By default, this security role is assigned the following privileges in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege name</p></th>
<th><p>Privilege AOT name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Run the initialization and upgrade checklists</p></td>
<td><p>SysCheckList_Setup</p></td>
</tr>
</tbody>
</table>

  


