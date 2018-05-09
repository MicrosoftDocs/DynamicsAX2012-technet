---
title: About requirement types for operations resources
TOCTitle: About requirement types for operations resources
ms:assetid: 824b39e3-0cd6-4c4d-8e8a-5d3bdb062ca9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh545525(v=AX.60)
ms:contentKeyID: 37832514
ms.date: 09/16/2014
mtps_version: v=AX.60
f1_keywords:
- resource
- operations resource
- requirement types
---

# About requirement types for operations resources 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you are defining requirements for a route, you can select from eight requirement types. The following table provides information about each requirement type, and specifies whether the requirement type is available for the operations scheduling and job scheduling methods.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Requirement type</p></th>
<th><p>Description</p></th>
<th><p>Operations scheduling</p></th>
<th><p>Job scheduling</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Resource type</strong></p></td>
<td><p>Specify the resource type that is required. There are five resource types:</p>
<ul>
<li><p><strong>Vendor</strong></p></li>
<li><p><strong>Human resources</strong></p></li>
<li><p><strong>Machine</strong></p></li>
<li><p><strong>Tool</strong></p></li>
<li><p><strong>Location</strong></p></li>
</ul></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p><strong>Resource group</strong></p></td>
<td><p>Any resource from the resource group can be scheduled for production.</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p><strong>Resource</strong></p></td>
<td><p>A specific resource must be scheduled for production.</p>
<p>By default, the <strong>Operations scheduling</strong> check box is not selected when a resource requirement is specified. You can select the check box manually.</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p><strong>Capability</strong></p></td>
<td><p>Any resource with the selected capability is scheduled for production. You can also specify a minimum level of proficiency in the <strong>Minimum level needed</strong> field. Setting the minimum level of proficiency is optional.</p>
<p>The scheduling engine selects all resources that satisfy the capability requirement and the minimum level of proficiency needed.</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p><strong>Skill</strong></p></td>
<td><p>This requirement type is relevant when you specify <strong>Human resources</strong> as a requirement.</p>
<p>Only human resources that have the selected skill are scheduled. You can also specify the rating level that is required. Setting the required rating level is optional.</p>
<p>The scheduling engine only selects human resources with a skill rating level that matches the rating level specified on the route. Human resources with higher or lower rating levels are not selected.</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p><strong>Courses</strong></p></td>
<td><p>This requirement type is relevant when you specify <strong>Human resources</strong> as a requirement.</p>
<p>Only human resources that have the selected course are scheduled.</p>
<p>When you run a scheduling, the start and end dates of the course are not considered. This is because companies often have different policies about how to use these dates. For example, some companies allow operators to drill if they have started a course but not yet completed it, whereas other companies require only operators who have completed the course.</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p><strong>Certificate</strong></p></td>
<td><p>This requirement type is relevant when you specify <strong>Human resources</strong> as a requirement.</p>
<p>Only human resources that have obtained the defined certificate can be scheduled.</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p><strong>Title</strong></p></td>
<td><p>This requirement type is relevant when you specify <strong>Human resources</strong> as a requirement.</p>
<p>Only human resources that have the defined title can be scheduled.</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


## See also

[Create and maintain operations resources](create-and-maintain-operations-resources.md)

[Resources (operations resources)(form)](https://technet.microsoft.com/en-us/library/aa557962\(v=ax.60\))

[Resource groups (operations resources)(form)](https://technet.microsoft.com/en-us/library/hh227450\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

