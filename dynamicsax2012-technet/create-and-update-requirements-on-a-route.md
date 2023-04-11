---
title: Create and update requirements on a route
TOCTitle: Create and update requirements on a route
ms:assetid: fa560e4b-6970-4fb3-a415-ebbe431b2ca2
ms:mtpsurl: https://technet.microsoft.com/library/Hh545539(v=AX.60)
ms:contentKeyID: 37832552
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create and update requirements on a route 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can define requirements based on the resource type, the resource group, or the individual resource itself. You can also define requirements based on resource capabilities. Additionally, you can specify whether a requirement is available for operations scheduling and job scheduling.

## Define resource requirements for operations on a route

Follow these steps to define requirements on a route.

1.  Click **Production control** \> **Common** \> **Routes** \> **All routes**. Select the route that you want to define requirements for, and click **Edit**.

2.  In the upper pane of the **Route** form, select the operation that you want to define requirements for.

3.  In the lower pane of the **Route** form, click the **Resource requirements** tab. Click **New** to create a new requirement.

4.  In the **Requirement type** field, select the requirement type.

5.  In the **Requirement** field, select the requirement you want to assign. The requirement options depend on the requirement type you selected in the previous step.

6.  Select the **Operation scheduling** check box if the route is to be operations scheduled.
    

    > [!NOTE]
    > <P>Requirement types <STRONG>Resource type</STRONG>, <STRONG>Resource group</STRONG>, and <STRONG>Capability</STRONG> can be operations scheduled and job scheduled.</P>



7.  Select the **Job scheduling** check box if the route is to be job scheduled.
    

    > [!NOTE]
    > <P>Requirement types <STRONG>Resource</STRONG>, <STRONG>Skill</STRONG>, <STRONG>Courses</STRONG>, <STRONG>Certificate</STRONG>, and <STRONG>Title</STRONG> can only be job scheduled.</P>



## Additional notes

If you selected the requirement type **Capability** in the **Requirement type** field, the **Minimum level needed** field is displayed under **Options**. You can define the level requirement in the **Minimum level needed** field. If more than one resource is found that satisfies the minimum level needed, the resources with the highest value are selected.

If you selected the requirement type **Skill** in the **Requirement type** field, the **Level** field is displayed under **Options**. You can define the skill level requirement in the **Level** field. Only the exact value in the **Level** field is used to select requirement skills. If you entered a skill level of 4, only those workers with a skill level of exactly 4 are selected. Those workers with higher skill levels, such as 5 or 6, are not selected.

## Defining more than one requirement on a route

You can define more than one requirement on a route, but the resource types you define must be consistent with other requirements.

For example, you cannot define one requirement for a resource of the type **Tool**, and then define a second requirement for a skill, because a tool cannot have a skill. The correct resource type is **Human resources**, because human resources can have skills.

You can, however, define requirements that take into account potential changes in the future. For example, you can first define a resource group, and then define a resource that is not presently a member of that resource group. You only get an error if the resource is not a member of the resource group when the production is planned. This is because resources can be moved from one resource group to another after requirements have been defined.

You can also do this when you are defining resources and capabilities. It may be that when the requirements are defined, the required resource does not have the required capability. However, when the production is planned, the resource has obtained the required capability, so that the production can be planned successfully.

## Delete requirements on a route

Follow these steps to delete a requirement from a route.

1.  Click **Production control** \> **Common** \> **Routes** \> **All routes**. Select the route that you want to delete requirements for, and click **Edit**.

2.  In the upper pane of the **Route** form, select the operation on which you want to delete requirements.

3.  In the lower pane of the **Route** form, click the **Resource requirements** tab.

4.  Select the requirement you want to delete, and click **Delete**.

  


