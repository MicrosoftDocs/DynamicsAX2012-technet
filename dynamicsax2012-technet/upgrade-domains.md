---
title: Upgrade domains
TOCTitle: Upgrade domains
ms:assetid: d39a7913-2f90-4afc-8305-8b0b79b92d16
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh575251(v=AX.60)
ms:contentKeyID: 39555414
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Upgrade domains 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In previous releases of Microsoft Dynamics AX, you could create a collection of companies that was known as a domain. You could use domains to set up user permissions for a group of company accounts. The concept of a domain was removed in Microsoft Dynamics AX 2012. Instead, we recommend that you use an organizational hierarchy that has a purpose of **Security**.

Domains are not upgraded to Microsoft Dynamics AX 2012. However, companies are automatically upgraded. Each company in the previous release is upgraded to a company in Microsoft Dynamics AX 2012, and a corresponding legal entity is created. A legal entity is also created for the predefined DAT company.


> [!NOTE]
> <P>The client and application require the DAT company to start for the first time. In general, we do not recommend that you use the DAT company in a production environment.</P>



In Microsoft Dynamics AX 2012, security roles are defined one time for all organizations. Therefore, when you upgrade, you should combine user groups that have the same permissions in different domains. You can control the access that individual users have to organizations by using the organizational hierarchy. You can give users access to individual legal entities, or to organizations that belong to an organization hierarchy that has a purpose of **Security**. If an operating unit is not part of a hierarchy that has a purpose of **Security**, data security policies must be created to restrict user access to that operating unit.

There are multiple ways to convert a domain to an organizational hierarchy. We recommend that you use a structure that accurately represents the structure of your organization.

The following sections describe some options for upgrading domains to organizational hierarchies in Microsoft Dynamics AX 2012.

## Example domain settings in Microsoft Dynamics AX 2009

The following illustration shows an example of a domain setup in Microsoft Dynamics AX 2009. Security is assigned per domain. User groups are specific to each domain.

![Example AX 2009 domain implementation](images/Hh575251.DomainUpgrade2009(AX.60).png "Example AX 2009 domain implementation")

## Option 1: Create business units to structure companies in a domain-like hierarchy

Often, domains can be represented as business units, and legal entities can be nested under each business unit. The following illustration shows an example.

![Example domain upgrade to business units](images/Hh575251.DomainUpgradeBU(AX.60).png "Example domain upgrade to business units")

## Option 2: Nest legal entities to accurately represent the organizational structure

Alternatively, if this setup more accurately represents your organization, you can create a hierarchy in which one company from the domain is at the top level. The other companies from the domain are under that company. Companies, which are represented by legal entities in Microsoft Dynamics AX 2012, can be nested under other companies to depict the actual organizational structure. The following illustration shows an example.

![Example domain upgrade to actual structure](images/Hh575251.DomainUpgradeActual(AX.60).png "Example domain upgrade to actual structure")

## See also

[About organizations and organizational hierarchies](about-organizations-and-organizational-hierarchies.md)

[Create or modify an organization hierarchy](create-or-modify-an-organization-hierarchy.md)

  


