---
title: About line properties
TOCTitle: About line properties
ms:assetid: c66e71ff-46f2-4273-ace9-60fe95d96e4b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh696880(v=AX.60)
ms:contentKeyID: 42517338
ms.date: 10/06/2014
mtps_version: v=AX.60
---

# About line properties 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the line property to set up default information about hour, fee, expense, and item transaction lines. You can use the line property to set up additional cost and sales price percentages for project hour transactions. When you create transactions for projects, the default line properties are automatically added to the lines in journals, invoices, and other postings. By setting up default line properties, you can minimize repetitive tasks when you work with projects.

The purpose of the line property depends on the project type:

  - Time and material projects – The line property controls whether transactions are chargeable or nonchargeable, whether the sales amount is accruable or nonaccruable, and whether the cost amount is capitalized as a fixed asset.

  - Fixed-price projects – The line property affects only whether the cost amount is capitalized as a fixed asset.

You can set up default line properties for projects, project groups, categories and category groups. If you have not set up default line properties, you must enter a line property on each line when you enter transactions. If you specify a default line property for an individual project, that specification takes precedence over any group line property or a line property that is assigned to all projects.

## See also

[About line property setup](about-line-property-setup.md)

[Set up a line property](set-up-a-line-property.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

