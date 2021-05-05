---
title: "What's new: Role-based security"
TOCTitle: Role-based security
ms:assetid: 5b14294e-bc25-4e06-9759-e75e876fba4c
ms:mtpsurl: https://technet.microsoft.com/library/Dn527126(v=AX.60)
ms:contentKeyID: 59623255
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Role-based security 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In earlier versions of Microsoft Dynamics AX, the management of application security was complex and time-consuming. Administrators had to determine which tables and fields were required for a task, and then grant a user permissions for those tables and fields. In Microsoft Dynamics AX 2012, security management is more intuitive and less time-consuming. Administrators manage security by defining roles and then assigning users to those roles. Developers assign permissions to program artifacts such as tables, forms, and form controls. Permissions are grouped into privileges and duties that are assigned to roles.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required feature</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Product areas affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Technical decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

The system administrator and the developer each manage parts of the new security system. The administrator defines the roles that are used in the organization and assigns users to those roles. The developer defines the duties that are used to grant permission to the tasks that each role performs.

## What’s new in security for system administrators

## What’s new in AX 2012

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Define user groups.</p></td>
<td><p>Security was not defined by default. Administrators had to create their own user groups and grant those groups access to application objects.</p></td>
<td><p>Permissions for all application objects have been grouped into task-based privileges and duties.</p>
<p>Sample security roles and duties are provided for every area of Microsoft Dynamics AX. Relevant privileges are assigned to these roles and duties by default. You can use the sample security roles and duties as they are, modify them to fit the requirements of your business, or create new security roles and duties.</p>
<p>For information about the default roles, see <a href="security-role-reference.md">Security role reference</a>.</p></td>
<td><p>Management of user security has been simplified.</p></td>
</tr>
<tr class="even">
<td><p>Set user group permissions.</p></td>
<td><p>Administrators had to create user groups and manually assign users to those groups. To grant a user group permission to perform a particular operation, the administrator had to identify the application objects, such as tables, fields, and menu items, that were required for the operation. When a person changed jobs, the administrator had to manually update that person's permissions in Microsoft Dynamics AX.</p></td>
<td><p>Many security roles are predefined to make security setup easier. The administrator grants access to the duties that users in a role perform.</p>
<p>The administrator no longer has to identify the application objects that are required for an operation. Instead, the developer now associates the necessary permissions in the Microsoft Dynamics AX Application Object Tree (AOT) on each relevant item.</p>
<p>Because rules can be set up for automatic role assignment, the administrator does not have to be involved every time that a user's responsibilities change. After security roles and rules have been set up, role assignments can be updated based on changes in business data.</p>
<p>For more information about role assignment rules, see <a href="assign-users-to-security-roles.md">Assign users to security roles</a>.</p></td>
<td><p>User security is aligned with your business.</p></td>
</tr>
<tr class="odd">
<td><p>Reuse permissions across companies.</p></td>
<td><p>User groups could not span multiple companies. If the same functional role was required in two companies, the administrator had to create two user groups. Therefore, the number of user groups could grow quickly.</p>
<p>For example, in a business that has 50 functional roles in 50 companies, the administrator had to create and manage 2,500 user groups to appropriately assign permissions.</p></td>
<td><p>A single set of roles applies across all organizations. The administrator no longer has to create and maintain separate user groups for each organization.</p>
<p>Although roles themselves are not specific to an organization, the administrator can still assign a user to a role in specific organizations.</p></td>
<td><p>Management of user security has been simplified.</p></td>
</tr>
<tr class="even">
<td><p>Define permission levels (read only, create, update, and delete).</p></td>
<td><p>Security keys were used to define permission levels for user groups.</p></td>
<td><p>Separate default privileges are defined for each permission level. Security keys are no longer used.</p></td>
<td><p>Management of user security has been simplified.</p></td>
</tr>
<tr class="odd">
<td><p>Enforce regulatory and procedural compliance.</p></td>
<td><p>There were no built-in features to help prevent fraud and guarantee compliance.</p></td>
<td><p>Fewer security objects are assigned to fewer groups of users. You can audit for compliance based on business activities instead of program elements. The administrator can set up rules for segregating duties to make sure that a user does not gain access to conflicting duties. For example, a rule can specify that the same person cannot both acknowledge the receipt of goods and pay the vendor.</p>
<p>For more information about how to segregate duties for regulatory or procedural compliance, see <a href="set-up-segregation-of-duties.md">Set up segregation of duties</a>.</p></td>
<td><p>User security is improved.</p></td>
</tr>
<tr class="even">
<td><p>Allow external users to access Microsoft Dynamics AX through Enterprise Portal for Microsoft Dynamics AX.</p></td>
<td><p>User authentication was based on Active Directory Domain Services. All users were required to be domain users. This requirement applied even to external users of Enterprise Portal. To help secure other data on the network, the administrator had to set up group policies to prevent external users from accessing that data.</p></td>
<td><p>Users can be authenticated by using methods other than Active Directory. Therefore, external users no longer require domain accounts to access Enterprise Portal.</p>
<p>For more information about how to grant external users access to Enterprise Portal, see <a href="deploy-an-enterprise-portal-site-that-uses-forms-based-authentication.md">Deploy an Enterprise Portal site that uses forms-based authentication</a>.</p></td>
<td><p>Management of user security has been simplified, and user security is improved.</p></td>
</tr>
<tr class="odd">
<td><p>Use improved data security filters.</p></td>
<td><p>When data filters were created through the record-level security feature, the fields that the filters were based on had to be in the same table as the data that was filtered.</p></td>
<td><p>A user can create data security policies based on data that is contained in a different table.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/gg847361(v=ax.60)">Security Policies in the AOT for Data Records</a>.</p></td>
<td><p>Data security controls are improved.</p></td>
</tr>
<tr class="even">
<td><p>Use data security that is based on effective dates.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>Administrators can specify whether users have access to past, present, or future records, and can specify different levels of access for each kind of record.</p></td>
<td><p>Data security controls are improved.</p></td>
</tr>
<tr class="odd">
<td><p>Prevent users from accessing unauthorized data.</p></td>
<td><p>All information was sent from the server to the client, and the client hid unauthorized fields from the user.</p></td>
<td><p>The server filters information. Only information that the administrator grants the user access to is sent to the client and to the user.</p></td>
<td><p>Data security controls are improved.</p></td>
</tr>
<tr class="even">
<td><p>Consistently enforce security for all client types.</p></td>
<td><p>The Table Permissions Framework (TPF) was used to deny access to tables. All data was sent to the client, and specific fields in client forms were hidden, based on permissions. Tables that were not protected by TPF were freely accessible by code.</p></td>
<td><p>TPF permissions can be applied at the field level. Because more authorization is performed on the server, permissions are more consistently enforced, regardless of the type of client.</p>
<p>For more information about TPF, see <a href="manage-data-access-by-using-the-table-permissions-framework.md">Manage data access by using the Table Permissions Framework</a>.</p></td>
<td><p>Data security controls are improved.</p></td>
</tr>
<tr class="odd">
<td><p>Make sure that you have the correct Microsoft Dynamics AX licenses for users.</p></td>
<td><p>Licensing was not based on named users.</p></td>
<td><p>Licensing is based on the roles that users perform in the organization.</p>
<p>The <strong>Named user license count</strong> report displays information about the user licenses that are required, based on the security roles that users are assigned to.</p>
<p>For more information, see <a href="named-user-license-count-report-sysuserlicensecountreport.md">Named user license count report (SysUserLicenseCountReport)</a>.</p></td>
<td><p>Verification of licensing compliance is easier.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Feature</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Enhancements to the <strong>Named user license count</strong> report</p></td>
<td><p>The <strong>Named user license count</strong> report can display the user IDs and aliases that are currently assigned to each license type.</p></td>
</tr>
</tbody>
</table>


## What’s new in security for developers

## What’s new in AX 2012

Many elements in the AOT have properties that are related to role-based security. However, for the developer, the central location of role-based security is under the **Security** node.

Role-based security has mechanisms that help secure both columns and rows in tables. You can help secure the following elements:

  - Tables and table fields – You can often help secure these elements by limiting access through menu items and forms that interact with the tables.

  - Table records – You can help secure these elements based on the data values in the records.

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
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create security permissions on individual AOT elements.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>The system automatically generates sets of permission specifications on forms and other AOT elements. The permission specifications are inferred by the system to match the details of each form. The developer can modify the permission specifications on any given form.</p>
<p>The developer selects the set of permission specifications that applies to each menu item that refers to the form. The developer uses the AOT to activate the selected permission specifications. The developer can combine many active permissions into one privilege. Active permissions are created in the AOT, under the <strong>Security</strong> &gt; <strong>Permissions</strong> node. One privilege can correspond to the various actions that are required to perform one particular business task.</p>
<p>Either the system administrator or the developer can assign a privilege to a user role. All users who are assigned to the role gain that privilege.</p></td>
<td><p>The new security system takes less work to maintain as your business evolves. Security constructs can be reused more easily.</p>
<p>Data that the user does not have permissions to see is never sent from Microsoft Dynamics AX Application Object Server (AOS) to the client. Appropriate security does not rely on forms for enforcement.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/library/gg841928(v=ax.60)">Automatic Inference of Permissions in AOT Security</a>.</p></td>
</tr>
<tr class="even">
<td><p>Implement security policies for table records.</p></td>
<td><p>The <a href="https://technet.microsoft.com/library/aa879172(v=ax.60)">record level security (RLS)</a> feature was used to filter access to table records. RLS security constructs applied only in individual tables.</p>
<p>RLS was applied only if the developer explicitly called RLS to enforce security. Therefore, security enforcement could be accidentally omitted.</p></td>
<td><p>Security policies for table rows behave like a where clause in SQL. A security policy is based on a query under the <strong>Queries</strong> node in the AOT. The details of the policy are specified under the <strong>Data Sources</strong> &gt; <strong>Ranges</strong> node. Therefore, foreign key relations between tables can be part of a security policy.</p>
<p>Security policies are assigned to user roles.</p></td>
<td><p>Security policies can restrict access to table rows, based on foreign key relationships between tables. One security policy can replace several RLS specifications.</p>
<p>After a security policy is created in the AOT and assigned to a user role, the system automatically enforces the policy. Therefore, developers do not have to add calls to a security system in their code.</p>
<p>The RLS feature will be removed from a future version of the product.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/library/gg847361(v=ax.60)">Security Policies in the AOT for Data Records</a>.</p></td>
</tr>
</tbody>
</table>


## Special considerations

If you are using an earlier version of Microsoft Dynamics AX, your existing security setup cannot be directly upgraded to role-based security. You must evaluate your current user groups and determine the best way to implement them in AX 2012. For more information, see [Best practices for upgrading to role-based security](best-practices-for-upgrading-to-role-based-security.md).

To effectively use role-based security, you must plan and set up the roles that are required for your business. Work with the managers who oversee the different groups in the business to determine the appropriate permission levels for roles. For example, work with a manager in the Finance department to determine permission levels for Finance roles.

## More information

For more detailed information about role-based security, see [Role-based security in Microsoft Dynamics AX](role-based-security-in-microsoft-dynamics-ax.md).

For more information about Extensible Data Security (XDS), see the white paper [Developing Extensible Data Security Policies](https://go.microsoft.com/fwlink/?linkid=213139).

  


