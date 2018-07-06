---
title: Customer service manager security role (TradeCustomerServiceManager)
TOCTitle: Customer service manager security role (TradeCustomerServiceManager)
ms:assetid: d359fc6f-544a-4ec6-b9fb-f2497bd127f0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527139(v=AX.60)
ms:contentKeyID: 37823190
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Customer service manager security role (TradeCustomerServiceManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Customer service manager security role represents a user who reviews customer service process performance and enables the customer service process.

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
<td><p>Enable case management</p></td>
<td><p>CaseCaseManagementEnable</p></td>
<td><p>Set up policies and reference data to enable the case management process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into case management policies</p></td>
<td><p>CaseCaseManagementPolicyInquire</p></td>
<td><p>Respond to inquiries about policies governing the case management process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into case management reference data inquiries</p></td>
<td><p>CaseCaseManagementReferenceDataInquire</p></td>
<td><p>Respond to inquiries about case management reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into case progress</p></td>
<td><p>CaseCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of cases</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales case progress</p></td>
<td><p>CaseSalesCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of sales cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into service case progress</p></td>
<td><p>CaseServiceCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of service cases</p></td>
</tr>
<tr class="odd">
<td><p>Activate, deactivate, update sites solution in Home module</p></td>
<td><p>CaseSitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain document service operation</p></td>
<td><p>CaseWebServiceMaintain</p></td>
<td><p>Read and create cases and inquire about category and priority information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer master</p></td>
<td><p>CustCustomerMasterInquire</p></td>
<td><p>Respond to inquiries about customer master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into related inventory status</p></td>
<td><p>InventRelatedInventoryStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the related inventory</p></td>
</tr>
<tr class="odd">
<td><p>Process catalog requests</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRCatalogRequestMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Merge and unmerge customers</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRCustMergeMaintain</p></td>
<td><p>Merge and unmerge customer records</p></td>
</tr>
<tr class="odd">
<td><p>Maintain customer service</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRCustomerServiceMaintain</p></td>
<td><p>Maintain customer service</p></td>
</tr>
<tr class="even">
<td><p>Inquire into order events</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCREventInquire</p></td>
<td><p>Respond to inquiries about order events</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sales return order</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRReturnSalesReturnOrderMaintain</p></td>
<td><p>Document and record sales return order</p></td>
</tr>
<tr class="even">
<td><p>Maintain sales order holds</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRSalesHoldMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain sales order</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRSalesOrderMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales return order progress</p></td>
<td><p>ReturnSalesReturnOrderProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the sales return order process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into activities</p></td>
<td><p>smmActivityInquire</p></td>
<td><p>Respond to inquiries about activity data</p></td>
</tr>
<tr class="even">
<td><p>Enable activity process</p></td>
<td><p>smmActivityProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the activity process</p></td>
</tr>
<tr class="odd">
<td><p>Review activity process</p></td>
<td><p>smmActivityProcessReview</p></td>
<td><p>Monitor, analyze, and improve the activity process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into activity reference data</p></td>
<td><p>smmActivityReferenceDataInquire</p></td>
<td><p>Respond to inquiries about activity reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into prospect master</p></td>
<td><p>smmBusinessRelationMasterInquire</p></td>
<td><p>Respond to inquiries about prospects master data</p></td>
</tr>
<tr class="even">
<td><p>Review prospects</p></td>
<td><p>smmBusinessRelationMasterReview</p></td>
<td><p>Monitor, analyze, and improve the prospects</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into contact master</p></td>
<td><p>smmContactMasterInquire</p></td>
<td><p>Respond to inquiries about contact master data</p></td>
</tr>
<tr class="even">
<td><p>Enable contact process</p></td>
<td><p>smmContactProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the contact process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into contact reference data</p></td>
<td><p>smmContactReferenceDataInquire</p></td>
<td><p>Respond to inquiries about contact master reference data</p></td>
</tr>
<tr class="even">
<td><p>Maintain knowledge articles</p></td>
<td><p>smmKnowledgeArticlesMaintain</p></td>
<td><p>Configure and maintain knowledge articles</p></td>
</tr>
<tr class="odd">
<td><p>Prospect turnover</p></td>
<td><p>smmProspectsTurnoverGenerate</p></td>
<td><p>Create turnover report for prospects</p></td>
</tr>
<tr class="even">
<td><p>Maintain sites service solution in sales and marketing module</p></td>
<td><p>smmSitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

