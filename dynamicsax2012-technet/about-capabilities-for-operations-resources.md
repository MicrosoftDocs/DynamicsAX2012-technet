---
title: About capabilities for operations resources
TOCTitle: About capabilities for operations resources
ms:assetid: 31945ac2-ef6c-4dae-b161-54eafbc596c7
ms:mtpsurl: https://technet.microsoft.com/library/Hh208568(v=AX.60)
ms:contentKeyID: 36056342
ms.date: 09/17/2014
mtps_version: v=AX.60
f1_keywords:
- resource
- capabilities
- operation
- capability
- operations resource
- operations
audience: Application User
ms.search.region: Global
---

# About capabilities for operations resources 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A capability is the ability of a resource to perform a given activity relevant to production and the scheduling of resources for production.

## Assigning capabilities to operations resources

Capabilities are assigned to an operations resource. A resource can have more than one capability assigned to it and a capability may be assigned to more than one resource. Capabilities can also be assigned to resources on a temporary basis by defining a start date and expiration date on the capability assignment. Capabilities that have expired on a resource will prevent the resource being scheduled for production if the production requires that capability. A capability that has expired can be subsequently renewed.

Capabilities can be assigned to all kinds of resources, such as a **Tool**, **Vendor**, or **Machine**, or to **Human resources**.

## Deleting capabilities

You can delete capabilities as long as they are not on a route relation or part of a production route of an active production order. In general, use caution when you delete capabilities. Instead, consider whether to adjust the expiration date on the resources that have the capability instead.

## Requirements and Capabilities

When defining resource requirements for a production route, you can specify one or more capabilities as requirements. When production scheduling is performed, the capabilities defined in the resource requirements on the route operation are matched with the capabilities defined for the resources. The resources with capabilities that satisfy the requirements are then selected.

When defining capabilities for different resources, capabilities should be set up so that significantly different processing speeds are set up as different capabilities.

## Example:

  - On a route, the drilling process time is set to 10 units per hour, but the requirement itself is defined as “Drilling”.

  - The capability “Drilling” is assigned to two different machine resources: M1 and M2.

  - M1 can drill two units per hour and M2 can drill 11 units per hour.

Both machines can be picked up by the scheduling engine because both satisfy the requirement: “Drilling”. However, the M1 machine can only drill two units per hour, far less than the 10 units per hour specified on the route. This will cause production problems. To resolve this, two separate capabilities should be created: “Low-speed drilling” and “High speed drilling”. “Low-speed drilling” is defined by a drilling process time of one to nine units per hour. “High speed drilling” is defined by a drilling process time of 10 to 19 units per hour.

In this setup, the M1 machine is given the “Low-speed drilling“ capability and the M2 machine has the “High-speed drilling” capability. The scheduling engine will then select the correct machine (M2).

## Priority

Resources with identical capabilities can be assigned a priority. The scheduling engine can then select multiple resources with capabilities that satisfy the scheduling requirements and the required level. The resource with the lowest numeric value in the **Priority** field (highest priority) will be presented first.

## Capabilities and Human Resources

When defining the requirements for a production route, you can also specify skills, courses, certifications or title as requirements. This does not require a relation to a worker. These values are set up in the Human Resource module and are not defined in the Capabilities form. When defining skills, courses, certifications or title as requirements, you must have the Human Resources module enabled. You can define capabilities in the Capabilities form that resemble or duplicate those from the Human Resources module. However, the Capabilities form does not contain the functionality that is required to maintain skills, courses, certifications or titles.

## See also

[Create and modify capabilities for operations resources](create-and-modify-capabilities-for-operations-resources.md)

  


