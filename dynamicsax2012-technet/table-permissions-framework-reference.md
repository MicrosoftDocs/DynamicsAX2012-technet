---
title: Table Permissions Framework reference
TOCTitle: Table Permissions Framework reference
ms:assetid: 65cd97c0-279a-4d94-887d-e6cc8545aa82
ms:mtpsurl: https://technet.microsoft.com/library/Dd309699(v=AX.60)
ms:contentKeyID: 46331994
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Table Permissions Framework reference 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Table Permissions Framework (TPF) enables administrators to set restrictions on tables that store data, including sensitive data. To enable TPF, an administrator specifies a value for the AOSAuthorizationProperty on a specific table in the Application Object Tree (AOT). The AOSAuthorizationProperty can be used to authorize Create, Read, Update, and Delete operations.

For more information, see [Manage data access by using the Table Permissions Framework](manage-data-access-by-using-the-table-permissions-framework.md).

## Tables

This section lists all database tables that are TPF-enabled by default in Microsoft Dynamics AX and the authorization requirements for those tables.


> [!IMPORTANT]
> <P>These tables store sensitive data. We recommend that you do not adjust these authorization requirements, especially in a production environment. Test your changes in a test environment so that you can study the impact on user-role permissions and make adjustments as necessary.</P>



<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table name</p></th>
<th><p>Authorization required for</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AifChannel</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>AifSqlCdcEnabledTables</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>AifValueSubstitutionComponentConfig</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>BankAccountTable</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>BankBillOfExchangeTmp</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>BankIBSLog_BE</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>BatchGroup</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>BatchServerConfig</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>BatchServerGroup</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>BIAnalysisServer</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>BIConfiguration</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>BIPerspectives</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>BIUdmTranslations</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>CompanyInfo</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>CreditCardCust</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>CreditCardCustNumber</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>CreditCardMicrosoftSetup</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>CreditCardProcessorsSecurity</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>CustBankAccount</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>CustVendOutTmp</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>EPDocuParameters</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>EPGlobalParameters</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>EPWebSiteParameters</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>ExpressionTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>GeneralJournalAccountEntry</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>HcmPersonIdentificationNumber</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>HcmWorkerBankAccount</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>LedgerActivityZakatTmp_SA</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>LedgerClosingSheet</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>LedgerMainZakatTmp_SA</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>LedgerOpeningSheet_ES</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>LedgerProvisionsTmp_SA</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>LedgerRevenueActivityTmp_S</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>LedgerZakatHeaderTmp_SA</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>NumberSequenceDatatype</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>NumberSequenceScope</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>OMUserRoleOrganization</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>OMUserRoleOrganizationTmp</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>RetailSetupLog</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>ShipCarrierSQLRoleUser</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SIGCertificateUsage</p></td>
<td><p>Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SIGParameters</p></td>
<td><p>Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SIGProcSetup</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SIGProcSetupField</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SIGProdStatusChange</p></td>
<td><p>Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SIGReasonCode</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SIGReportFinished</p></td>
<td><p>Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SIGSignatureDelegation</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SIGSignatureFailure</p></td>
<td><p>Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SIGSignatureLog</p></td>
<td><p>Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SRSAnalysisEnums</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SRSEnabledLanguages</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SRSModelEntityCache</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SRSModelFieldCache</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SRSModelFieldRoleSortCache</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SRSModelForeignKeyCache</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SRSModelIndexCache</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SRSModelPerspectiveCache</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SRSModelPerspectiveEntityCache</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SRSModelPerspectiveFieldCache</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SRSModelPerspectiveForeignKeyCache</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SRSModelPerspectiveRoleCache</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SRSModelRoleCache</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SRSModelRoleGroupsCache</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SRSReportDeploymentSettings</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SRSServers</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SRSUpdateOptions</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SRSUserConfiguration</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysClusterConfig</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysCompileILTable</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysDataBaseLog</p></td>
<td><p>Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysExpImpField</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysExpImpTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysFileStore</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysFileStoreFile</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysMapParameters</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysPerimeterNetworkParams</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysRecordTemplateSystemTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysRemoveConfig</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysRemoveFields</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysRemoveLicense</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysRemoveTables</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysSecurityFormControlTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysSecurityFormTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysServerConfig</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysSetupCompanyLog</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysSetupLog</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysSignatureSetup</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysSortOrder</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysUserInfo</p></td>
<td><p>Create, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysWorkflowElementTable</p></td>
<td><p>Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysWorkflowFaultTable</p></td>
<td><p>Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysWorkflowInstanceTable</p></td>
<td><p>Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysWorkflowTable</p></td>
<td><p>Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>SysWorkflowTrackingEntry</p></td>
<td><p>Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>SysXppAssembly</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>Tax1099BoxDetailHistory</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>Tax1099IRSPayerRec</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>Tax1099TransmitterParameters</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>TmpBankBillofExchangePrintout</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>TmpBankPromissoryNotePrintout</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>TmpChequePrintout</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>TrvCreditCards</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>VendBankAccount</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>VendCoverPageSignature</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>VendRequestProspectiveProfile</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>VendSubcontractorZakatTmp_SA</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>VendTable</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>WorkflowActionTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>WorkflowAssignmentTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>WorkflowAssociation</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>WorkflowElementLinkTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>WorkflowElementNotificationTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>WorkflowElementOutcomeTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>WorkflowElementTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>WorkflowEscalationPathTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>WorkflowEscalationTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>WorkflowMaxRuntimeTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>WorkflowMessageText</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>WorkflowParallelBranchTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>WorkflowStepTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>WorkflowSubWorkflow</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>WorkflowSubWorkflowItem</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>WorkflowSubWorkflowTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>WorkflowTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>WorkflowTimeSpanTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>WorkflowVersionNotificationTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>WorkflowVersionTable</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>WorkflowVersionTableNotes</p></td>
<td><p>Create, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>xRefNames</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>xRefPaths</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>xRefReferences</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="odd">
<td><p>xRefTableRelation</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
<tr class="even">
<td><p>xRefTmpReferences</p></td>
<td><p>Create, Read, Update, Delete</p></td>
</tr>
</tbody>
</table>

  


