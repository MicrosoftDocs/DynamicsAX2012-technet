---
title: Example organizational hierarchies
TOCTitle: Example organizational hierarchies
ms:assetid: d68676fc-9fdf-4f08-a934-064dbb9a259b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh801194(v=AX.60)
ms:contentKeyID: 43976728
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Example organizational hierarchies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides examples of organizational hierarchies for small, midsized, and large organizations.

These examples include suggestions and guidance about how to model organizational hierarchies. However, business requirements should be the primary factor that determines your approach. The size and complexity of the business are important considerations. Microsoft Dynamics AX is primarily used by small and midsized businesses, which compose the segment of the market that is known as the midmarket segment. Therefore, the examples in this topic also focus on that market segment.

For more information about what to consider when you create an organizational hierarchy, see [Plan the organizational hierarchy](plan-the-organizational-hierarchy.md).

## Organization modeling for a small organization

Small organizations typically have just one or very few legal entities. The legal structure is often also used as the operating structure, because the business includes a very limited number of product lines or groups. A small organization can use the legal structure to measure performance and control operations for product lines.

An organizational hierarchy is not required for a small organization, if the business does not require complex internal control policies and data security access that are based on hierarchies. Simple policies and data security can be based on a list of legal entities that is not organized in a hierarchy. However, we recommend that you always create a single mixed hierarchy to support the organization as it grows. If more complex scenarios for internal control, such as audit control and invoice control, become necessary, a small organization must define additional hierarchies that consist of legal entities only.

A typical small organization has a single mixed hierarchy that has a legal entity at the top. Departments and cost centers roll up to the legal entity.

![Organization hierarchy for a small business](images/Hh801194.SmallBusinessHierarchy(AX.60).png "Organization hierarchy for a small business")

## Organization modeling for a midsized organization

Midsized organizations may require complex internal control policies, and therefore may require separate hierarchies for legal entities and operating units.

The structure of the legal entities might be based on industries, consumers, or product lines. In the following illustration, the legal entity structure is based on geographic regions.

![Hierarchy of legal entities for midsized business](images/Hh801194.MidsizedHierarchyLE(AX.60).png "Hierarchy of legal entities for midsized business")

The hierarchy of operating units might have a legal entity at the top and business units under the legal entity. Each business unit might contain departments, and each department might consist of cost centers. Departments that are under a single legal entity in the legal entity hierarchy can roll up to different business units in the operating hierarchy, as in the following illustration.

![Business unit hierarchy for midsized business](images/Hh801194.MidsizedHierarchyBU(AX.60).png "Business unit hierarchy for midsized business")

## Organization modeling for a large organization

Large organizations grow through mergers and acquisitions. Leaders of these organizations typically want to analyze the business based on operating structures such as industries, consumers, or product lines. Additionally, leaders typically restructure their businesses to meet the requirements of the marketplace in an agile manner. A large organization requires an organizational structure that supports internal controls, effective performance measurement, and efficient delivery of goods and services. Large organizations must model multiple hierarchies to measure the effectiveness of restructuring, and to compare old and new organizational structures.

Larger organizations may require some hierarchies that are based on business units and other hierarchies that are based on shared services, such as human resources and IT. However, when you design hierarchies, make sure that cost centers are created in shared service departments, and that the cost centers are positioned under business units, so that the costs of shared services are appropriately allocated.

## See also

[About organizations and organizational hierarchies](about-organizations-and-organizational-hierarchies.md)

[Create or modify an organization hierarchy](create-or-modify-an-organization-hierarchy.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

