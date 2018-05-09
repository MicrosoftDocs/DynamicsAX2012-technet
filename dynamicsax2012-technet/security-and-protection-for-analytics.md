---
title: Security and protection for analytics
TOCTitle: Security and protection for analytics
ms:assetid: f294dd72-5c49-455a-a37f-1a4f15094709
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Ee910037(v=AX.60)
ms:contentKeyID: 28119617
ms.date: 07/15/2014
mtps_version: v=AX.60
---

# Security and protection for analytics 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains the default security model for analysis cubes that are used with Microsoft Dynamics AX, and how you can customize that model to meet your needs.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Hh404117.TopicIcons_Conceptual(AX.60).png" title="Concepts" alt="Concepts" />
<p>The default security model</p>
<p>Customizing security for cubes</p>
<p></p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="default-analysis-services-roles.md">Default Analysis Services roles</a></p>
<p><a href="grant-users-access-to-cubes.md">Grant users access to cubes</a></p></td>
</tr>
</tbody>
</table>


## The default security model

Security for analysis cubes is set up independently from security for Microsoft Dynamics AX. To grant users access to cubes, you must assign the users to database roles in Microsoft SQL Server Analysis Services.

When you deploy the cubes that are included with Microsoft Dynamics AX, default roles are created in the database where you deploy the cubes. The following image shows some of these default roles.

![Roles in Analysis Services](images/Ee910037.BI_RolesInSSAS(AX.60).png "Roles in Analysis Services")

To set up security for the cubes, follow these steps:

1.  Review [Default Analysis Services roles](default-analysis-services-roles.md) to learn more about the roles that are created in Analysis Services when you deploy the cubes that are included with Microsoft Dynamics AX.

2.  Assign users to the Analysis Services roles. For instructions, see [Grant users access to cubes](grant-users-access-to-cubes.md).
    
    Keep in mind that the members of a role have permission to view all data in the cubes that the role has access to. For example, if you assign a user to the **Project supervisor** role, the user has access to all data in the Project accounting cube.

## Customizing security for cubes

The members of an Analysis Services role have permission to view all data in the cubes that the role has access to. To help restrict a role’s access to specific dimensions and cells in a cube, you can perform customizations. The following topics describe customizations that can help secure Microsoft Dynamics AX cubes:

  - [Scenario: Help prevent employees of one company from viewing cube data for another company](scenario-help-prevent-employees-of-one-company-from-viewing-cube-data-for-another-company.md)

  - [Scenario: Help secure cube data so that managers see only the data for their own team](scenario-help-secure-cube-data-so-that-managers-see-only-the-data-for-their-own-team.md)

  - [Scenario: Mapping security in Microsoft Dynamics AX to Analysis Services](scenario-mapping-security-in-microsoft-dynamics-ax-to-analysis-services.md)

The documentation for SQL Server also provides the following topics that explain how to help restrict a role’s access to specific dimensions and cells in a cube:

  - [Granting Dimension Access](http://technet.microsoft.com/en-us/library/ms175421.aspx) explains how to help restrict access to dimensions.

  - [Granting Custom Access to Dimension Data](http://technet.microsoft.com/en-us/library/ms175366.aspx) explains how to help restrict access to dimension attribute members.

  - [Granting Custom Access to Cell Data](http://technet.microsoft.com/en-us/library/ms174847.aspx) explains how to help restrict access to cell data.


> [!WARNING]
> <P>If you modify a default Analysis Services role that is provided by Microsoft Dynamics AX, you may accidentally prevent some members of the role from viewing reports and key performance indicators (KPIs) that those members were intended to view. For more information about the default roles that are included with Microsoft Dynamics AX and the cubes that the roles have access to, see <A href="default-analysis-services-roles.md">Default Analysis Services roles</A>.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

