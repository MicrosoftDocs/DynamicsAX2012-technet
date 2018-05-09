---
title: About service templates
TOCTitle: About service templates
ms:assetid: e5427f26-b808-4970-a86c-23ab40d85054
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa573166(v=AX.60)
ms:contentKeyID: 36059788
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About service templates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can define a service agreement as a template and copy the lines of the template later into another service agreement or into a service order.

## Example

A customer for whom you provide service has identical service elevators at five different locations.

You want to set up five service agreements for the customer, one for each site. To limit repetitive setup work, and to make sure that the setup information in the service agreements is identical, you create a service agreement and specify it as a template for the service work on the elevators.

You can now copy the template lines into the five new service agreements, so that each service agreement is populated with the lines from the template.

## Creating a template

When you create a service template, you create a service agreement, create the required lines on it, and attach the service agreement to a service-template group.


> [!NOTE]
> <P>A service agreement can be defined as a template only if it has no service orders attached to it. Also, no service orders can be generated from a service agreement that is defined as a template.</P>



## Copying template lines

You can copy template lines from a service template into another service agreement or into a service order.

When you copy template lines into your service orders or service agreements, your template groups are displayed in a tree view in which each group can be expanded. This display lets you view each template and template line.

It is easier to determine the service-template lines that you want to copy if you have grouped the templates under names that reflect the use of the templates.

## See also

[Copy service templates lines](copy-service-templates-lines.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

