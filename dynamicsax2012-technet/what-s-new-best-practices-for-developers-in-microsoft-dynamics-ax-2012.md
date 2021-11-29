---
title: "What's New: Best Practices for Developers in Microsoft Dynamics AX 2012"
TOCTitle: Best Practices for Developers
ms:assetid: f7bdd87f-2ee2-4417-9efe-c5199c2901aa
ms:mtpsurl: https://technet.microsoft.com/library/Gg865121(v=AX.60)
ms:contentKeyID: 35253637
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# What's New: Best Practices for Developers in Microsoft Dynamics AX 2012 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The best practice checks that are enforced by the X++ compiler were updated to reflect new features that were added for this release. In addition, focus was put on security, and the existing rules that generated warnings were evaluated.

### ![Gg865121.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg865121.collapse_all(en-us,AX.60).gif")New Best Practice Checks

The following table describes the new best practice rules. The message that occurs for violations of a best practice informational, warning, or error rule occurs when you check best practices. For more information, see [Best Practice Overview](https://technet.microsoft.com/library/aa548778\(v=ax.60\)).

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Message</p></th>
<th><p>Description</p></th>
<th><p>BPError code and label</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>RecID field cannot be part of the NaturalKey index.</p></td>
<td><p>A RecID field was set as the replacement key.</p>
<p>This best practice rule requires an exclusive RecID in the inheritance hierarchy. When you create a new field in a table, the best practice logic iterates through the inheritance hierarchy to make sure that the RecID and ReplacementKey indexes are exclusive.</p>
<p>This best practice rule supports relational application design.</p></td>
<td><p>BPErrorTableNaturalKeyWithRecID</p>
<p>@SYS129768</p></td>
</tr>
<tr class="even">
<td><p>Class is packing element IDs instead of element names.</p></td>
<td><p>You used an element ID in your pack and unpack methods. Examples of element IDs are ClassId, TableId, and FieldId. Instead, use the element name in your pack and unpack methods.</p></td>
<td><p>BPErrorClassSysPackableElementIds</p>
<p>@SYS130592</p></td>
</tr>
<tr class="odd">
<td><p>The form must include a grid that contains ValidFrom and ValidTo fields when that form has a data source with ValidTimeStateAutoQuery set to DateRange.</p></td>
<td><p>When the <strong>ValidTimeStateAutoQuery</strong> property for the data source of a form is set to <strong>DateRange</strong>, a grid must exist that contains the ValidFrom and ValidTo fields. For more information, see <a href="https://technet.microsoft.com/library/gg861781(v=ax.60)">Valid Time State Tables and Date Effective Data</a>.</p></td>
<td><p>BPErrorFormValidTimeStateMissingValidToOrFromDate</p>
<p>@SYS133561</p></td>
</tr>
<tr class="even">
<td><p>Table is using CreatedDateTime or ModifiedDateTime, RecId index needs to be created.</p></td>
<td><p>A table that has a CreatedDateTime or ModifiedDateTime field must have a RecID index.</p></td>
<td><p>BPErrorRecIDNeededCreatedModifiedDateTime</p>
<p>@SYS127410</p></td>
</tr>
<tr class="odd">
<td><p>The class %1 is obsolete. Instead, use the class %2.</p></td>
<td><p>You tried to use a class that is obsolete.</p></td>
<td><p>BPErrorClassDiscontinuedInLaterVers</p>
<p>@SYS69514</p></td>
</tr>
<tr class="even">
<td><p>Do not use braces around the case blocks in a switch statement.</p></td>
<td><p>You used braces around a case block in a switch statement. The braces must be removed. For more information, see <a href="https://technet.microsoft.com/library/aa607181(v=ax.60)">Switch Statements</a>.</p></td>
<td><p>BPErrorMethodNoBracketsInCaseBlocks</p>
<p>@SYS152524</p></td>
</tr>
<tr class="odd">
<td><p>Do not use the &lt;syntax&gt; tag in XML documentation. The syntax is automatically derived from the method declaration, and must not be explicitly provided.</p></td>
<td><p>You used a &lt;syntax&gt; tag in XML documentation. The tag must be removed. XML documentation is denoted by triple slash (///) comments at the start of a method.</p></td>
<td><p>BPErrorXmlDocumentationSyntaxForbidden</p>
<p>@SYS152515</p></td>
</tr>
<tr class="even">
<td><p>Line item workflow '%1' event handler does not reference a valid class implementing the '%2' interface</p></td>
<td><p>This best practice rule supports the event handling that is now supported for approvals and tasks. For more information, see <a href="https://technet.microsoft.com/library/cc606215(v=ax.60)">How to: Create a Workflow Event Handler</a>.</p></td>
<td><p>BPErrorWorkflowLineItemWorkflowEHInvalid</p>
<p>@SYS152823</p></td>
</tr>
<tr class="odd">
<td><p>Line item workflow relation '%1' not found on workflow document query '%2’</p></td>
<td><p>This best practice rule supports the event handling that is now supported for approvals and tasks. For more information, see <a href="https://technet.microsoft.com/library/cc606215(v=ax.60)">How to: Create a Workflow Event Handler</a>.</p></td>
<td><p>BPErrorWorkflowLineItemWorkflowRelationNotFound</p>
<p>@SYS152835</p></td>
</tr>
<tr class="even">
<td><p>Line item workflow relation '%1' is invalid. Relation must be configured with a fetch mode of 1:n on workflow document query '%2'</p></td>
<td><p>This best practice rule supports the event handling that is now supported for approvals and tasks. For more information, see <a href="https://technet.microsoft.com/library/cc606215(v=ax.60)">How to: Create a Workflow Event Handler</a>.</p></td>
<td><p>BPErrorWorkflowLineItemWorkflowRelationInvalid</p>
<p>@SYS152836</p></td>
</tr>
<tr class="odd">
<td><p>Line item workflow relation not defined</p></td>
<td><p>This best practice rule supports the event handling that is now supported for approvals and tasks. For more information, see <a href="https://technet.microsoft.com/library/cc606215(v=ax.60)">How to: Create a Workflow Event Handler</a>.</p></td>
<td><p>BPErrorWorkflowLineItemWorkflowRelationEmpty</p>
<p>@SYS152837</p></td>
</tr>
<tr class="even">
<td><p>Line item workflow type '%1' not found</p></td>
<td><p>This best practice rule supports the event handling that is now supported for approvals and tasks. For more information, see <a href="https://technet.microsoft.com/library/cc606215(v=ax.60)">How to: Create a Workflow Event Handler</a>.</p></td>
<td><p>BPErrorWorkflowLineItemWorkflowTypeNotFound</p>
<p>@SYS152839</p></td>
</tr>
<tr class="odd">
<td><p>Workflow document query not found on line item workflow type '%1'</p></td>
<td><p>This best practice rule supports the event handling that is now supported for approvals and tasks. For more information, see <a href="https://technet.microsoft.com/library/cc606215(v=ax.60)">How to: Create a Workflow Event Handler</a>.</p></td>
<td><p>BPErrorWorkflowLineItemWorkflowTypeQueryNotFound</p>
<p>@SYS152840</p></td>
</tr>
<tr class="even">
<td><p>Line-item workflow relation '%1' does not match root datasource on line item workflow type document query '%2'</p></td>
<td><p>This best practice rule supports the event handling that is now supported for approvals and tasks. For more information, see <a href="https://technet.microsoft.com/library/cc606215(v=ax.60)">How to: Create a Workflow Event Handler</a>.</p></td>
<td><p>BPErrorWorkflowLineItemWorkflowTypeQueryNoMatch</p>
<p>@SYS152841</p></td>
</tr>
<tr class="odd">
<td><p>Line item workflow must have at least one line item workflow type</p></td>
<td><p>This best practice rule supports the event handling that is now supported for approvals and tasks. For more information, see <a href="https://technet.microsoft.com/library/cc606215(v=ax.60)">How to: Create a Workflow Event Handler</a>.</p></td>
<td><p>BPErrorWorkflowLineItemWorkflowNoTypes</p>
<p>@SYS152842</p></td>
</tr>
<tr class="even">
<td><p>The Company association type cannot be used for this workflow type because the table for the primary data source used by the workflow type is not configured to 'Save Data Per Company'.</p></td>
<td><p>Select a different association type. This best practice rule was added to support organizational model types in workflow. For more information, see <a href="associate-a-workflow-with-an-organization.md">Associate a workflow with an organization</a>.</p></td>
<td><p>BPErrorWorkflowInvalidAssociationTypeCompany</p>
<p>@SYS190334</p></td>
</tr>
<tr class="odd">
<td><p>The Global and Other association types cannot be used for this workflow type because the table for the primary data source used by the workflow type is configured to 'Save Data Per Company'.</p></td>
<td><p>This best practice rule supports organizational model types in workflow. For more information, see <a href="associate-a-workflow-with-an-organization.md">Associate a workflow with an organization</a>.</p></td>
<td><p>BPErrorWorkflowInvalidAssociationTypeGlobalOther</p>
<p>@SYS190335</p></td>
</tr>
<tr class="even">
<td><p>An association type relation must be selected when the association type is Other</p></td>
<td><p>This best practice rule supports organizational model types in workflow. For more information, see <a href="associate-a-workflow-with-an-organization.md">Associate a workflow with an organization</a>.</p></td>
<td><p>BPErrorWorkflowMissingAssociationTypeRelation</p>
<p>@SYS190336</p></td>
</tr>
<tr class="odd">
<td><p>A class extending the SysTableExtension class should not have any member variables.</p></td>
<td><p>This best practice rule verifies that the SysTableExtension class does not have any member variables. This best practice rule is used to support the extension of the SysTableExtension base class. Use the SysTableExtension class to override the table data defaults.</p></td>
<td><p>BPErrorSysTableExtensionHasStates</p>
<p>@SYS190373</p></td>
</tr>
<tr class="even">
<td><p>The node's path exceeds the maximum length of 400 characters. Reduce number of nesting levels or rename nodes.</p></td>
<td><p>This best practice rule reports tree node paths that exceed 400 characters.</p></td>
<td><p>BPErrorTreenodePathExceedsMaxLength</p>
<p>@SYS300071</p></td>
</tr>
<tr class="odd">
<td><p>Table is using CreatedDateTime or ModifiedDateTime, RecId index needs to be created.</p></td>
<td><p></p></td>
<td><p>BPErrorRecIDNeededCreatedModifiedDateTime</p>
<p>@SYS127410</p></td>
</tr>
<tr class="even">
<td><p>The upgrade script is missing required attribute %1.</p></td>
<td><p>This best practice rule verifies that the upgrade script has the required <strong>Description</strong> attribute.</p></td>
<td><p>BPErrorMissingReqDesc</p>
<p>@SYS309412</p></td>
</tr>
<tr class="odd">
<td><p>The upgrade script is missing required attribute %1.</p></td>
<td><p>This best practice rule verifies that the upgrade script has the required <strong>Type</strong> attribute.</p></td>
<td><p>BPErrorMissingReqType</p>
<p>SYS309412</p></td>
</tr>
<tr class="even">
<td><p>The upgrade script is missing required attribute %1.</p></td>
<td><p>This best practice rule verifies that the upgrade script has the required <strong>Stage</strong> attribute.</p></td>
<td><p>BPErrorMissingReqStage</p>
<p>SYS309412</p></td>
</tr>
<tr class="odd">
<td><p>The upgrade script is missing required attribute %1.</p></td>
<td><p>This best practice rule verifies that the upgrade script has the required <strong>Table</strong> attribute.</p></td>
<td><p>BPErrorMissingReqTable</p>
<p>SYS309412</p></td>
</tr>
<tr class="even">
<td><p>The upgrade script method cannot be static.</p></td>
<td><p>This best practice rule verifies that the upgrade script is a non-static method.</p></td>
<td><p>BPErrorMethodIsStatic</p>
<p>@SYS309410</p></td>
</tr>
<tr class="odd">
<td><p>The upgrade script method cannot accept parameters.</p></td>
<td><p>This best practice rule verifies that the upgrade script method has no parameters.</p></td>
<td><p>BPErrorMethodHasParams</p>
<p>@SYS309411</p></td>
</tr>
<tr class="even">
<td><p>Table %1 specified in the UpgradeScriptTableAttribute is not valid.</p></td>
<td><p>This best practice rule verifies that the table that is stated in the attribute of an upgrade script exists in the Microsoft Dynamics AX Application Object Tree (AOT).</p></td>
<td><p>BPErrorTableNotFound</p>
<p>@SYS309400</p></td>
</tr>
<tr class="odd">
<td><p>Configuration Key %1 specified in the UpgradeScriptConfigKeyAttribute is not valid.</p></td>
<td><p>This best practice rule verifies that the configuration key that is stated in the attribute of an upgrade script exists in the AOT.</p></td>
<td><p>BPErrorConfigurationKeyNotFound</p>
<p>@SYS309401</p></td>
</tr>
<tr class="even">
<td><p>Class %1 specified in the UpgradeDependsOnModuleAttribute is not valid.</p></td>
<td><p>This best practice rule verifies that the class name that is stated in the attribute of an upgrade script exists in the AOT.</p></td>
<td><p>BPErrorClassNameNotFound</p>
<p>@SYS309404</p></td>
</tr>
<tr class="odd">
<td><p>Method %1 in class %2 specified in the UpgradeDependsOnModuleAttribute is not valid.</p></td>
<td><p>This best practice rule verifies that the method name that is stated in the attribute of an upgrade script exists in the AOT.</p></td>
<td><p>BPErrorMethodNameNotFound</p>
<p>@SYS309403</p></td>
</tr>
<tr class="even">
<td><p>The upgrade script does not have a valid version defined [#define.version(sysReleasedVersion)] in the class declaration.</p></td>
<td><p>This best practice rule verifies that the script version that is stated in the attribute of an upgrade script exists in the AOT.</p></td>
<td><p>BPErrorInvalidScriptVersion</p>
<p>@SYS309415</p></td>
</tr>
<tr class="odd">
<td><p>Return type covariance: Return values must both be either tables or maps (%1.%2).</p></td>
<td><p>This best practice rule verifies that both of the inherited return values are tables, or that both values are maps.</p></td>
<td><p>BPErrorInheritedReturnTypeMustBeTableOrMap</p>
<p>@SYS309721</p></td>
</tr>
<tr class="even">
<td><p>Return type covariance: Methods must return the same map (%1.%2).</p></td>
<td><p>This best practice rule verifies that the inherited methods return the same map.</p></td>
<td><p>BPErrorInheritedReturnTypeMustBeSameMap</p>
<p>@SYS309722</p></td>
</tr>
<tr class="odd">
<td><p>The %1 relation to the %2 table does not have an upgrade script assigned. You must assign an upgrade script or exclude it from upgrade validation.</p></td>
<td><p>The unit of measure table is now global. At upgrade, company-specific units are merged by using user-defined mapping. This merge requires that existing tables that have relations to the unit of measure also apply the mapping.</p>
<p>This best practice rule checks for relations to the unit of measure. The rule then verifies that each relation to the unit of measure is registered with an upgrade script, or that the table is marked for exclusion from the upgrade.</p>
<p>The following code illustrates how to register a unit of measure upgrade job:</p>
<p>UnitOfMeasureUpgradeExecutor::registerUpgradeJobs()</p>
<p>The following code illustrates how to exclude a unit of measure table:</p>
<p>UnitOfMeasureUpgradeValidator::registerExcludedRelations()</p>
<p>For information about pre-upgrade tasks that are related to units of measure, see <a href="units.md">Units</a>, <a href="unit-conversions.md">Unit conversions</a>, <a href="fixed-units.md">Fixed units</a>, and <a href="unit-texts.md">Unit texts</a>.</p></td>
<td><p>BPErrorTableRelationNoUnitUpgrade</p>
<p>@SYS310791</p></td>
</tr>
<tr class="even">
<td><p>A non-surrogate key primary index is not valid for a company-specific table</p></td>
<td><p>This best practice rule verifies that the primary key for a company-specific table is a surrogate key.</p></td>
<td><p>BPErrorNonSurrogateKeyForPerCompanyTable</p>
<p>@SYS315491</p></td>
</tr>
<tr class="odd">
<td><p>Use of labels for developer documentation</p></td>
<td><p>This best practice rule verifies that a description is specified for each table in the <strong>DeveloperDocumentation</strong> property.</p></td>
<td><p>BPErrorDeveloperDocumentationNotDefined</p>
<p>@SYS118413</p></td>
</tr>
<tr class="even">
<td><p>Framework classes must have a disclaimer in the ClassDeclaration to discourage customizations.</p></td>
<td><p>This best practice rule verifies that framework classes that provide platform functionality have a disclaimer message that discourages developers from customizing those classes. Customizing and extending classes that provide platform functionality might cause issues during future upgrades.</p></td>
<td><p>BPErrorClassFrameworkDisclaimer</p>
<p>@SYS316340</p></td>
</tr>
<tr class="odd">
<td><p>The framework class disclaimer must be placed after the XML documentation.</p></td>
<td><p>Framework classes have a disclaimer message that discourages developers from customizing those classes. Customizing and extending classes that provide platform functionality might cause issues during future upgrades.</p>
<p>This best practice rule verifies that the disclaimer is put after the XML documentation. In other words, the disclaimer must be put after the /// comments.</p></td>
<td><p>BPErrorClassFrameworkDisclaimerPosition</p>
<p>@SYS316341</p></td>
</tr>
<tr class="even">
<td><p>Each perspective entity (table or view) must have at most 1 parent.</p></td>
<td><p>This best practice rule verifies that the perspective entity (table or view) has no more than one parent.</p></td>
<td><p>BPErrorPerspectiveEntityMultipleParents</p>
<p>@SYS316698</p></td>
</tr>
<tr class="odd">
<td><p>Each perspective entity (table or view) must have at most 1 child.</p></td>
<td><p>This best practice rule verifies that the perspective entity (table or view) has no more than one child.</p></td>
<td><p>BPErrorPerspectiveEntityMultipleChildren</p>
<p>@SYS316701</p></td>
</tr>
<tr class="even">
<td><p>Each perspective entity (table or view) must have a corresponding child for each parent.</p></td>
<td><p>This best practice rule verifies that the perspective entity (table or view) has a corresponding child for each parent.</p></td>
<td><p>BPErrorPerspectiveEntityMissingChild</p>
<p>@SYS316700</p></td>
</tr>
<tr class="odd">
<td><p>Each perspective entity (table or view) must have a corresponding parent for each child.</p></td>
<td><p>This best practice rule verifies that the perspective entity (table or view) has a corresponding parent for each child.</p></td>
<td><p>BPErrorPerspectiveEntityMissingParent</p>
<p>@SYS316699</p></td>
</tr>
<tr class="even">
<td><p>In each perspective entity the parent type should be the same as the child type if present.</p></td>
<td><p>This best practice rule verifies that, in a perspective entity, the parent type is the same as the child type, if a child type exists.</p></td>
<td><p>BPErrorPerspectiveEntityParentChildTypesNotEqual</p>
<p>@SYS316702</p></td>
</tr>
<tr class="odd">
<td><p>Perspectives where SharedDimensionContainer=Yes cannot have fields where AnalysisUsage is Measure or Both. Perspective %1, table or view %2, field %3.</p></td>
<td><p>When the SharedDimensionContainer property for a perspective is set to <strong>True</strong>, the AnalysisUsage property for fields should not be set to Measure or Both. A setting of <strong>True</strong> for the SharedDimensionContainer property indicates that the perspective will be used to create dimensions only. The perspective will not be used to create a cube, measure group, or measure. For more information, see <a href="https://technet.microsoft.com/library/aa640388(v=ax.60)">Best Practices for Perspectives</a>.</p></td>
<td><p>BPErrorPerspectiveMeasureInSharedDimensionContainer</p>
<p>@SYS322558</p></td>
</tr>
<tr class="even">
<td><p>%1 or %2 must not be used in the sys layer.</p></td>
<td><p>This best practice rule verifies that the UpgradeModuleDependsOnMeAttribute and UpgradeTaskDependsOnMeAttribute attributes are not used in the SYS layer.</p></td>
<td><p>BPErrorExternalUseOnlyAttribute</p>
<p>@SYS327183</p></td>
</tr>
<tr class="odd">
<td><p>Inconsistent usage of AOSAuthorization property for a table in chain of inheritance. Ensure that both tables %1 and %2 have authorization either enabled or disabled.</p></td>
<td><p>This best practice rule verifies that all the tables in the inheritance hierarchy have the same value for authorization: either <strong>Enabled</strong> or <strong>Disabled</strong>.</p></td>
<td><p>BPErrorTableTPFIntegrity</p>
<p>@SYS327320</p></td>
</tr>
<tr class="even">
<td><p>Allowed CacheLookUp values for this TableGroup is %1</p></td>
<td><p>This best practice rule verifies that the cache lookup is valid for the table group.</p></td>
<td><p>BPErrorInvalidCacheLookUpAndTableGroup</p>
<p>@SYS327950</p></td>
</tr>
<tr class="odd">
<td><p>Service group must have a valid description</p></td>
<td><p>This best practice rule verifies that the <strong>Description</strong> property is provided for a service group. The value must be a valid label.</p></td>
<td><p>BPErrorServiceGroupMustHaveDescription</p>
<p>@SYS328359</p></td>
</tr>
<tr class="even">
<td><p>Service must have a valid Namespace property</p></td>
<td><p>This best practice rule verifies that the <strong>Namespace</strong> property for a service is set to a valid namespace. You may not use the default URI, such as http://tempuri.org.</p></td>
<td><p>BPErrorServiceMustHaveNamespace</p>
<p>@SYS328364</p></td>
</tr>
<tr class="odd">
<td><p>Entry point is not in any privilege</p></td>
<td><p>This best practice rule verifies that the entry point is in a privilege. A menu item (display, output, or action), service operation, web URL, web action, and web content managed nodes must be added as an entry point in a privilege.</p></td>
<td><p>BPErrorSecEntryPointNotCoveredByPrivilege</p>
<p>@SYS329300</p></td>
</tr>
<tr class="even">
<td><p>Menu item points to a class that is not a RunBase class; it should probably have a linked permission object</p></td>
<td><p>This best practice rule verifies that the menu item has a linked permission. If the class that is executed from the menu item opens a form, the linked permission should point to the form. If the class executes X++ code that requires access to tables that enable authorization for Microsoft Dynamics AX Application Object Server (AOS), the linked permission should point to a code permission that grants the appropriate access.</p></td>
<td><p>BPErrorSecClassMenuDoesNotHaveLinkedPermission</p>
<p>@SYS329302</p></td>
</tr>
<tr class="odd">
<td><p>All duties should be part of a role</p></td>
<td><p>This best practice rule verifies that a duty is assigned to a process cycle that is assigned to a role.</p></td>
<td><p>BPErrorSecDutyNotCoveredByRole</p>
<p>@SYS329307</p></td>
</tr>
<tr class="even">
<td><p>All duties should be part of a process cycle</p></td>
<td><p>This best practice rule verifies that a duty is assigned to a process cycle that is assigned to a role.</p></td>
<td><p>BPErrorSecDutyNotCoveredByProcessCycle</p>
<p>@SYS329308</p></td>
</tr>
<tr class="odd">
<td><p>A form that is not associated with other forms should be linked to at least one menu item</p></td>
<td><p>This best practice rule verifies that a form is linked to a menu item. A form that is not associated with another form or linked to a menu item cannot be accessed. Forms are opened from a menu item or from another form.</p></td>
<td><p>BPErrorSecFormNotLinkedToMenuItem</p>
<p>@SYS329310</p></td>
</tr>
<tr class="even">
<td><p>Non-system-managed %1 resource with incorrect managed by value %2</p></td>
<td><p>This best practice security rule verifies that the <strong>Managed By</strong> property of a resource that is not system-managed is set to <strong>Manual</strong>.</p></td>
<td><p>BPErrorSecNonSystemResourceDoesNotHaveManagedBy</p>
<p>@SYS329375</p></td>
</tr>
<tr class="odd">
<td><p>Privilege is not in any duty.</p></td>
<td><p>This best practice security rule verifies that the privilege is set to a valid duty.</p></td>
<td><p>BPErrorSecPrivilegeNotPartofDuty</p>
<p>@SYS329303</p></td>
</tr>
<tr class="even">
<td><p>Missing SysEntryPointAttribute on service operation</p></td>
<td><p>This best practice rule verifies that the SysEntryPointAttribute attribute is specified on a service operation that it is exposed externally.</p></td>
<td><p>BPErrorSecServiceOperationDoesNotHaveSEP</p>
<p>@SYS329376</p></td>
</tr>
<tr class="odd">
<td><p>Missing processReport method</p></td>
<td><p>This best practice rule verifies that the report has a processReport method.</p></td>
<td><p>BPErrorSecSSRSRDPPR</p>
<p>@SYS329374</p></td>
</tr>
<tr class="even">
<td><p>Missing SysEntryPointAttribute on SSRS RDP class</p></td>
<td><p>This best practice rule verifies that a processReport method is defined for the report data provider class for Microsoft SQL Server Reporting Services, and that a SysEntryPointAttribute attribute is specified for the method.</p></td>
<td><p>BPErrorSecSSRSRDPSysEP</p>
<p>@SYS329373</p></td>
</tr>
<tr class="odd">
<td><p>Info part not linked to menu items</p></td>
<td><p>This best practice security rule verifies that an Info Part is linked to a menu item. An Info Part is a collection of related data fields that you can associate with a record in a form. You use Info Parts to create a FactBox for a form or the preview pane for a list page. To add an Info Part to a form, you use a menu item that is linked to the Info Part.</p></td>
<td><p>BPErrorSecInfoPartNotInMenuItem</p>
<p>@SYS329309</p></td>
</tr>
<tr class="even">
<td><p>DeveloperDocumentation label should not be marked to be translated.</p></td>
<td><p>This best practice rule verifies that the <strong>DeveloperDocumentation</strong> property will not be translated. The comment for the label that is used in the <strong>DeveloperDocumentation</strong> property should have the {Locked} keyword.</p></td>
<td><p>BPErrorDeveloperDocumentationNotLocked</p>
<p>@SYS330248</p></td>
</tr>
<tr class="odd">
<td><p>The help provider class isn't specified for this online documentation set</p></td>
<td><p>The <strong>HelpProviderClass</strong> property must be set if the <strong>ContentLocation</strong> property is set to <strong>Online</strong> for a Help document set.</p></td>
<td><p>BPErrorHelpProviderClassEmpty</p>
<p>@SYS331955</p></td>
</tr>
<tr class="even">
<td><p>Query %1 cannot be made searchable because it has zero or more than one data sources.</p></td>
<td><p>This best practice rule verifies that a searchable query has exactly one data source. You receive a best practice violation if no data source is specified, or if more than one data source is specified.</p></td>
<td><p>BPErrorSearchableQueryNoDataSource</p>
<p>@SYS333623</p></td>
</tr>
<tr class="odd">
<td><p>Query %1 cannot be made searchable because it does not have the SearchLinkRefName property or the FormRef property set on the root table %2.</p></td>
<td><p>This best practice rule verifies that the <strong>SearchLinkRefName</strong> or <strong>FormRef</strong> property is set on the root table for the searchable query. If one of these properties is not set, no search results appear.</p></td>
<td><p>BPErrorSearchableQueryNoSearchLinkOnTable</p>
<p>@SYS334877</p></td>
</tr>
<tr class="even">
<td><p>Query %1 is searchable but it does not have the SearchLinkRefName property set to a URL menu item on the root table %2. The search results will not appear in Enterprise Portal.</p></td>
<td><p>This best practice rule verifies that the <strong>SearchLinkRefName</strong> property on the root table for the searchable query is set to a URL menu item. If this property is not set to a URL menu item, no search results appear in Enterprise Portal for Microsoft Dynamics AX.</p></td>
<td><p>BPErrorSearchableQueryNoSearchLinkRefUrl</p>
<p>@SYS334878</p></td>
</tr>
<tr class="odd">
<td><p>Query %1 is searchable but it does not have the FormRef property set to a form on the root table %2. The search results will not appear in the Microsoft Dynamics AX client.</p></td>
<td><p>This best practice rule verifies that the <strong>FormRef</strong> property on the root table for the searchable query is set to a form. If the property is not set to a form, no search results appear in the Microsoft Dynamics AX client.</p></td>
<td><p>BPErrorSearchableQueryNoFormRef</p>
<p>@SYS334879</p></td>
</tr>
<tr class="even">
<td><p>Query %1 cannot be made searchable because it does not have the TitleField1 or TitleField2 set on the root table %2.</p></td>
<td><p>This best practice rule verifies that the TitleField1 or TitleField2 field is set on the root table for the valid searchable query.</p></td>
<td><p>BPErrorSearchableQueryNoTitleFields</p>
<p>@SYS334876</p></td>
</tr>
<tr class="odd">
<td><p>Update permissions for the search crawler role</p></td>
<td><p>This best practice rule verifies that the search crawler role has permissions for the table that was used in the query.</p></td>
<td><p>BPErrorSearchableQueryNoTablePermissions</p>
<p>@SYS334872</p></td>
</tr>
<tr class="even">
<td><p>Query %1 cannot be made searchable because it has a root table that is a transaction table with no index on the ModifiedDateTime field.</p></td>
<td><p>This best practice rule verifies that the root table for the searchable query is a transaction table that has an index on the ModifiedDateTime field.</p></td>
<td><p>BPErrorSearchableQueryNoIndexOnTransactionTable</p>
<p>@SYS333624</p></td>
</tr>
<tr class="odd">
<td><p>Element has changed name since previous release. If the rename is intentional then suppress this violation; otherwise, update the LegacyID. Old name was: %1</p></td>
<td><p>This best practice rule verifies that the element had the same name in the previous release of Microsoft Dynamics AX. If the name was intentionally changed, suppress the violation.</p>
<p>This best practice check is not new, but the message has been updated. This check has been modified because of the changes that are related to installation-specific IDs.</p></td>
<td><p>BPErrorObjectNameConflict</p>
<p>@SYS335103</p></td>
</tr>
<tr class="even">
<td><p>The element has an origin value that is different from the origin value in a previous version of Microsoft Dynamics AX.</p></td>
<td><p>This best practice rule verifies that the element had the same origin value in earlier versions of Microsoft Dynamics AX. The origin value is the beginning value of the element. This check was added because of the changes that are related to installation-specific IDs.</p></td>
<td><p>BPErrorObjectOriginMismatch</p>
<p>@SYS335100</p></td>
</tr>
<tr class="odd">
<td><p>Element has no LegacyID assigned and was shipped in a previous version. All ID-based elements already shipped must have a LegacyID. Set Legacy ID to %1.</p></td>
<td><p>This best practice rule verifies that a <strong>LegacyID</strong> property is assigned to the element, because the element was shipped in an earlier version of Microsoft Dynamics AX. This check was added because of the changes that are related to installation-specific IDs.</p></td>
<td><p>BPErrorLegacyIdMissing</p>
<p>@SYS335102</p></td>
</tr>
<tr class="even">
<td><p>Element has a different LegacyID than previous shipped version. Please update LegacyID, old LegacyId was %1.</p></td>
<td><p>This best practice rule verifies that the value that is specified in the <strong>LegacyID</strong> property occurs in the earlier version of Microsoft Dynamics AX. A LegacyID specifies an identifier element from an earlier version of Microsoft Dynamics AX. This check was added because of the changes that are related to installation-specific IDs.</p></td>
<td><p>BPErrorLegacyIDConflict</p>
<p>@SYS335101</p></td>
</tr>
<tr class="odd">
<td><p>The element does not have an origin value. This element must have a non-null origin value.</p></td>
<td><p>This best practice rule verifies that the element has an origin value that is not NULL. This check was added because of the changes that are related to installation-specific IDs.</p></td>
<td><p>BPErrorOriginNull</p>
<p>@SYS335099</p></td>
</tr>
<tr class="even">
<td><p>Do not use a deprecated field as title field. Please select another title field.</p></td>
<td><p>This best practice rule verifies that deprecated fields are not used as title fields.</p></td>
<td><p>BPErrorTableTitleFieldDeprecated</p>
<p>@SYS338823</p></td>
</tr>
<tr class="odd">
<td><p>Do not use deprecated field %1 in non-deprecated index %2. Please remove the field or deprecate the index.</p></td>
<td><p>This best practice rule verifies that deprecated fields are not used as indexes. Replace the deprecated field, or remove the index.</p></td>
<td><p>BPErrorTableIndexFieldDeprecated</p>
<p>@SYS338822</p></td>
</tr>
<tr class="even">
<td><p>Do not use deprecated field %1 in field group %2. Please remove the field from the field group.</p></td>
<td><p>This best practice rule verifies that deprecated fields are not used in a field group. Remove the deprecated field from the field group.</p></td>
<td><p>BPErrorTableTableFieldGroupDeprecated</p>
<p>@SYS338821</p></td>
</tr>
</tbody>
</table>


### ![Gg865121.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg865121.collapse_all(en-us,AX.60).gif")Best Practice Checks Updated for Container Controls

Best practice checks for client forms were updated to verify the name and position for all container controls. The following table describes the changes that were made.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Message</p></th>
<th><p>Description</p></th>
<th><p>BPError code and label</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Control %1 bound to table field group has name that does not match default name of %2, consequently the control requires storage and cannot be optimized</p></td>
<td><p>This best practice rule checks for situations in which the <strong>DataGroup</strong> property is set for a Group or Grid control, but the child control cannot be created automatically when the form is loaded. This situation occurs because the name that is bound to the table field group does not match the default name. Therefore, the control must be saved as metadata. Saving the control as metadata requires storage, and the control cannot be optimized.</p></td>
<td><p>BPErrorFormGroupCannotBeOptimized</p>
<p>@SYS68376</p></td>
</tr>
<tr class="even">
<td><p>The form group and table group have different fields at position %1: '%2' != '%3', consequently the control requires storage and cannot be optimized</p></td>
<td><p>This best practice rule checks for situations in which the <strong>DataGroup</strong> property is set for the Group or Grid control, but the child control cannot be created automatically when the form is loaded. This situation occurs because the controls in the form group do not match the position in the table field group. Therefore, the position must be saved as metadata. Saving the position as metadata requires storage, and the position cannot be optimized.</p></td>
<td><p>BPErrorFormGroupControlDifFieldsAtPos</p>
<p>@SYS68382</p></td>
</tr>
</tbody>
</table>


Because of the changes to best practice rules for container controls, best practices have been removed. The following table lists the best practice checks that were removed.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Message</p></th>
<th><p>BPError code</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Group control bound to Table group has %1 auto-declaration(s), consequently it cannot be AOS optimized</p></td>
<td><p>BPErrorFormCannotBeAOSoptimizedAD</p></td>
</tr>
<tr class="even">
<td><p>Group control bound to Table group has some other properties changed from default, consequently it cannot be AOS optimized</p></td>
<td><p>BPErrorFormCannotBeAOSoptimizedPropChg</p></td>
</tr>
<tr class="odd">
<td><p>Form group (%1) and table group (%2) have different number of fields, consequently they cannot be AOS optimized</p></td>
<td><p>BPErrorFormGroupControlDifNumOfFields</p></td>
</tr>
</tbody>
</table>


### ![Gg865121.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg865121.collapse_all(en-us,AX.60).gif")Best Practice Checks Updated for Workflow Approval on the Web

When you create workflows that will be used only on the web, only thin client menu items are required. Best practice rules were updated to account for this scenario. For more information, see [Workflow Best Practices](https://technet.microsoft.com/library/cc597937\(v=ax.60\)).

The following table describes the messages that were updated so that they now apply to both web menu items and action menu items.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Message</p></th>
<th><p>BPError code and label</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The action menu item is not defined. The action menu item or the action Web menu item must be defined.</p></td>
<td><p>BPErrorWorkflowNoActionMenuItem</p>
<p>BPErrorWorkflowNoWebActionMenuItem</p>
<p>@SYS108556</p></td>
</tr>
<tr class="even">
<td><p>The document menu item is not defined. The document menu item or the document Web menu item must be defined.</p></td>
<td><p>BPErrorWorkflowNoDisplayMenuItem</p>
<p>BPErrorWorkflowNoWebURLMenuItem</p>
<p>@SYS108559</p></td>
</tr>
<tr class="odd">
<td><p>The element outcome '%1' action menu item property is not defined. The action menu item or the action Web menu item must be defined.</p></td>
<td><p>BPErrorWorkflowElementOutcomeNoActionMI</p>
<p>BPErrorWorkflowElementOutcomeNoActionWMI</p>
<p>@SYS108547</p></td>
</tr>
</tbody>
</table>


### ![Gg865121.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg865121.collapse_all(en-us,AX.60).gif")Best Practice Checks Changed from Warnings to Errors

Many of the existing rules that generate warnings were evaluated for the value that they provide. If violations of a best practice warning rule must be addressed, the warning was changed to an error.

The following table provides information about best practice rules that were changed from warning messages to error messages. Violations of these rules must now be fixed.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Message</p></th>
<th><p>BPError code and label</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Display and edit methods must use a base enum or an extended data type as their return type.</p></td>
<td><p>BPErrorTableNoExtendedReturnType</p>
<p>@SYS72489</p></td>
</tr>
<tr class="even">
<td><p>The table %1 has no fields in the AutoReport field group.</p></td>
<td><p>BPErrorTableMissingGroupAutoReport</p>
<p>@SYS55415</p></td>
</tr>
<tr class="odd">
<td><p>The table %1 has no record ID index but does use the record ID field explicitly in relation in %2.</p></td>
<td><p>BPErrorTableNoRecordIdIndex</p>
<p>@SYS60524</p></td>
</tr>
<tr class="even">
<td><p>Tables with only one index must have it defined as a cluster index. Set the ClusterIndex property for the %1 table.</p></td>
<td><p>BPErrorTableOneIndexNotCluster</p>
<p>@SYS68395</p></td>
</tr>
<tr class="odd">
<td><p>The table %1 has no record ID index but uses it %2 times.</p></td>
<td><p>BPErrorTableNoRecordIdIndexButUsed</p>
<p>@SYS60522</p></td>
</tr>
<tr class="even">
<td><p>A display or edit method and a field cannot have the same name. Rename either the %1 field or the display or edit method.</p></td>
<td><p>BPErrorTableFieldHasSameNameAsMethod</p>
<p>@SYS97063</p></td>
</tr>
<tr class="odd">
<td><p>The method %1%2%3 is obsolete. Instead, use the method %4.</p></td>
<td><p>BPErrorMethodDiscontinuedInLaterVers</p>
<p>@SYS68910</p></td>
</tr>
<tr class="even">
<td><p>The method %1 is empty and must be deleted.</p></td>
<td><p>BPErrorMethodIsEmpty</p>
<p>@SYS68904</p></td>
</tr>
<tr class="odd">
<td><p>Do not put parentheses around the case values in a switch statement. Remove the parentheses from %1.</p></td>
<td><p>BPErrorMethodParenthesisRoundCaseConst</p>
<p>@SYS55397</p></td>
</tr>
<tr class="even">
<td><p>Only use braces around code blocks.</p></td>
<td><p>BPErrorMethodNonNeededBlockStyleUsed</p>
<p>@SYS152538</p></td>
</tr>
<tr class="odd">
<td><p>Use double-quotation marks when referring to labels, instead of using single-quotation marks.</p></td>
<td><p>BPErrorMethodLabelInSingleQuotes</p>
<p>@SYS55395</p></td>
</tr>
<tr class="even">
<td><p>%1 and other variable names should not start with an underscore. Only parameter names are required to start with an underscore.</p></td>
<td><p>BPErrorMethodVariableWithUnderscore</p>
<p>@SYS60113</p></td>
</tr>
<tr class="odd">
<td><p>Use a field list in the select statement of %1, because only %2% of the record data is referenced.</p></td>
<td><p>BPErrorSelectUsingFieldList</p>
<p>@SYS91289</p></td>
</tr>
<tr class="even">
<td><p>All tables must have a primary index. Set the PrimaryIndex property for the table %1.</p></td>
<td><p>BPErrorTableNoPrimaryIndex</p>
<p>@SYS107156</p></td>
</tr>
</tbody>
</table>


### ![Gg865121.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg865121.collapse_all(en-us,AX.60).gif")Removed Best Practice Checks

Many of the existing rules that generate warnings were evaluated for the value that they provide. Best practice warning rules that had little value and that were ignored by users were removed. By removing these warning rules, we help users focus on the best practice warnings that should be considered.

The following table provides information about best practice rules that were removed because they are obsolete or were evaluated to be of low value.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Message</p></th>
<th><p>BPError code</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Enum is not referenced in X++ code, in the table field or in an Extended Type.</p></td>
<td><p>BPErrorEnumNotUsed</p></td>
</tr>
<tr class="even">
<td><p>Type is not referenced in X++ code, table field, or as a parent.</p></td>
<td><p>BPErrorTypeNotUsed</p></td>
</tr>
<tr class="odd">
<td><p>Table group is %1.</p></td>
<td><p>BPErrorTableNoTableGroup</p></td>
</tr>
<tr class="even">
<td><p>Table has record ID index but does not use record ID field explicitly.</p></td>
<td><p>BPErrorTableRecordIdIndexNotUseField</p></td>
</tr>
<tr class="odd">
<td><p>Table has a record ID index but does not seem to use the record ID field explicitly for lookup.</p></td>
<td><p>BPErrorTableRecIdFieldUsedUseless</p></td>
</tr>
<tr class="even">
<td><p>Field is not referenced in X++ code.</p></td>
<td><p>BPErrorTableFieldNotUsed</p></td>
</tr>
<tr class="odd">
<td><p>Method is not referenced in X++ code or indirectly.</p></td>
<td><p>BPErrorMethodNotUsed</p></td>
</tr>
<tr class="even">
<td><p>Method contains constant numeric value: %1.</p></td>
<td><p>BPErrorMethodConstantNumericArgUsed</p></td>
</tr>
<tr class="odd">
<td><p>Illegal name %1 %2: %3. Use parent, child or sibling.</p></td>
<td><p>BPErrorMethodIllegalName</p></td>
</tr>
<tr class="even">
<td><p>Consider alternative to single quoted text %1 appearing in %2.</p></td>
<td><p>BPErrorMethodSingleQuotedText</p></td>
</tr>
<tr class="odd">
<td><p>Variable %1 is not written, but read.</p></td>
<td><p>BPErrorMethodVariableReadButNotWritten</p></td>
</tr>
<tr class="even">
<td><p>Method syntax must be autogenerated using the [HEADER] keyword.</p></td>
<td><p>BPErrorDocNodeHardCodedMethodSyntax</p></td>
</tr>
<tr class="odd">
<td><p>No documentation for '%1'.</p></td>
<td><p>BPErrorDocNodeNoDocumentation</p></td>
</tr>
<tr class="even">
<td><p>No unique index set up for the table.</p></td>
<td><p>BPErrorTableNoUniqueIndex</p></td>
</tr>
<tr class="odd">
<td><p>A primary index should be defined if there are a unique index.</p></td>
<td><p>BPErrorTableUniqueIndexNoPrimary</p></td>
</tr>
<tr class="even">
<td><p>Table Field of type InventDimId must be added to the Multisite Activation</p></td>
<td><p>BPErrorTableFieldInventDimIdNotMultiSiteActivated</p></td>
</tr>
<tr class="odd">
<td><p>Security Key = 'NotDecided' (or others!)</p></td>
<td><p>BPErrorSecurityKeySpecific</p></td>
</tr>
<tr class="even">
<td><p>Security Key is unknown (May have been deleted!)</p></td>
<td><p>BPErrorSecurityKeyUnknown</p></td>
</tr>
<tr class="odd">
<td><p>Security Key is not defined</p></td>
<td><p>BPErrorSecurityKeyNotDefined</p></td>
</tr>
<tr class="even">
<td><p>Configuration Key is unknown (May have been deleted!)</p></td>
<td><p>BPErrorSecurityParentKeySpecific</p></td>
</tr>
<tr class="odd">
<td><p>Configuration Key is unknown (May have been deleted!)</p></td>
<td><p>BPErrorSecurityParentKeyUnknown</p></td>
</tr>
<tr class="even">
<td><p>Not Connected to a Security Key</p></td>
<td><p>BPErrorSecurityKeyNotConnected</p></td>
</tr>
<tr class="odd">
<td><p>Security key should not be specified on container controls, as it prevents personalization.</p></td>
<td><p>BPErrorSecurityKeyNotAllowed</p></td>
</tr>
<tr class="even">
<td><p>SecurityKey AnalysisVisibility property should not be Auto if there is no parent security key</p></td>
<td><p>BPErrorSecurityKeyAnalysisVisibilityAuto</p></td>
</tr>
<tr class="odd">
<td><p>No self relation set up for the Table.</p></td>
<td><p>BPErrorTableNoSelfRelation</p></td>
</tr>
<tr class="even">
<td><p>TwC: Validate access to return value from display/edit method.</p></td>
<td><p>BPErrorTwCDisplayEditMethod</p></td>
</tr>
<tr class="odd">
<td><p>Do not use TypeId()</p></td>
<td><p>BPErrorDoNotUseTypeId</p></td>
</tr>
<tr class="even">
<td><p>Object has changed ID since previous release. Old ID = %1.</p></td>
<td><p>BPErrorObjectIdConflict</p></td>
</tr>
<tr class="odd">
<td><p>Set the property AutoDeclaration to Yes for the form control, instead of manually declaring the form control %1.</p></td>
<td><p>BPErrorMethodNotAutoDeclared</p>
<p>@SYS68393</p></td>
</tr>
</tbody>
</table>


## See also

[What's New in Microsoft Dynamics AX 2012 for Developers](https://technet.microsoft.com/library/gg845327\(v=ax.60\))

[Best Practices for Microsoft Dynamics AX Development](https://technet.microsoft.com/library/aa658028\(v=ax.60\))

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

