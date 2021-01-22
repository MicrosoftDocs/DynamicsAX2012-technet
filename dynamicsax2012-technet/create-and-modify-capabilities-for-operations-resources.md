---
title: Create and modify capabilities for operations resources
TOCTitle: Create and modify capabilities for operations resources
ms:assetid: 8aee0253-af9e-4126-8263-aa2aeea4b185
ms:mtpsurl: https://technet.microsoft.com/library/Hh209345(v=AX.60)
ms:contentKeyID: 36058471
author: Khairunj
ms.author: daxcpft
ms.date: 09/16/2014
mtps_version: v=AX.60
f1_keywords:
- resource
- resources
- capabilities
- operation
- capability
- operations
- skill
audience: Application User
ms.search.region: Global
---

# Create and modify capabilities for operations resources 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Define capabilities to organize the resources for your operation. Resource planning and production scheduling depend on correctly defined capabilities because the requirements of a production are matched with the capabilities of a resource.

You must first create and define a capability and then assign it to one or more resources.

You can create new capabilities to assign to operations resources and update existing capabilities, delete them, or reassign them to other resources.

## Create a new capability

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource capabilities**.

2.  Click the **Capability** button or press CTRL+N to create a new capability.

3.  In the **Capability** field, enter the unique name or identifier of the capability.

4.  In the **Description** field, enter a description of the capability.

5.  Click **Save** or press CTRL+S.

## Assign a capability to an operations resource

A capability must be assigned to a resource. Two different resources can have the same capability, but the specifics, such as grade, priority, or effective date for the capability may be different for the two.

For example, a sheet metal press may have the “Aluminum sheet press” capability assigned and have a grade of 50, whereas an older sheet metal press would have the same capability assigned, but the older sheet metal press can only manage a grade of 30.


> [!NOTE]
> <P>A resource can have more than one capability assigned, and a capability can be assigned to more than one resource.</P>



1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource capabilities**.

2.  In the **Capabilities** form, select the capability to assign to a resource.

3.  Click the **Resources** tab, and then click **Add** to assign the selected capability to a resource.

4.  In the **Resource** field, select the resource to assign the capability to.
    

    > [!WARNING]
    > <P>Be sure to assign the correct capabilities to the relevant types of resources, such as <STRONG>Vendor</STRONG>, <STRONG>Human resources</STRONG>, <STRONG>Machine</STRONG>, <STRONG>Tool</STRONG>, or <STRONG>Location</STRONG>.</P>



5.  In the **Expiration** field, set the last date that the resource can be scheduled for production, based on the assigned capability. After this date has passed, you cannot change the other field values for the capability.

6.  In the **Priority** field, define the priority of the capability for the selected resource.

7.  In the **Level** field, set the level of the capability for the selected resource.

## Modify a capability

You can only change the values in the **Level**, **Priority**, and **Expiration** fields if the expiration date is not passed.

To change the level or priority values of a capability with an expiration date that has passed, you must create a new capability and assign it to the resource with the correct values.

## Delete a capability

You can delete existing capabilities that have been assigned to resources and that are effective. However, capabilities that exist on a route relation cannot be deleted.

To delete a capability on a route relation, you must first remove the route relation to the capability. You can only delete a capability from a route if the production order has a status of **Ended**.

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource capabilities**.

2.  In the **Capabilities** form, select the capability to delete.

3.  Click the **Delete** button or press ALT+F9.

## Remove an assigned capability from an operations resource

You can remove a capability that has been assigned to an operations resource even if the date has passed the effective date for the capability. However, capabilities that exist on a route relation cannot be removed.

To remove the capability from a route relation, you must first remove the route relation from the capability. You can only remove a capability from a resource if the capability exists on a production route of a production order if the production order has a status of **Ended**. However, you can set the expiration date on the capability to yesterday’s date. This has the same effect as removing the capability from the route relation.

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource capabilities**.

2.  In the **Capabilities** form, select the capability that should no longer be assigned to a resource.

3.  Click the **Resources** tab and select the resource to remove the capability from.

4.  Click **Remove** or press ALT+F9.

  


