---
title: About line property setup
TOCTitle: About line property setup
ms:assetid: 1c2df840-ed06-47e4-8f81-b57f29ad9c64
ms:mtpsurl: https://technet.microsoft.com/library/Aa569935(v=AX.60)
ms:contentKeyID: 42517317
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- line property
- search direction
- search priority
audience: Application User
ms.search.region: Global
---

# About line property setup 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up default line properties for projects and project categories. When you create a new project, you can use the default line properties, or you can modify them for specific lines. You can set up the default line property at the project or project group level, at the category or category group level, or by using any combination of the two types.

Set up line properties that have a **Table**, **Group**, or **All** relation to projects and categories. The relation that you select determines the priority for the line property that is applied when you enter a transaction in a journal.

  - **Table** – The line properties apply only to the specified project.

  - **Group** – The line properties apply to all projects in the specified project group.

  - **All** – The line properties apply to all projects.

When you post journal lines, the system searches for a line property that matches the specified project number and category. If no line properties are defined for the project or category, you must manually enter the line property for each hour, fee, expense, or item registration line.

You can specify whether the search for a default line property is by category or by project in the **Search priority** field on the **Setup** FastTab in the **Project** form. By default, when a new project is created, the line property is derived from the project group.

## Search priority for line property

The system searches for a combination of a specific project and a specific category. If you specify a project but do not specify a category for a line, the system searches for line properties by category group and then by all categories. If you specify a category, but not a project for a line, the system searches for line properties by project group and then by all projects.

## Example

In the **Project/group line properties** form, create a default line property named **Chargeable** and assign a relation of **Table** to the line property. Select project 10000 as the specific project for that line property. Do not select a category for this line property.

Create a project category that is used for expense. The category is not assigned a line property.

Create an expense journal for project 10000. Add a line to the journal and select the expense category. By default, the line property for the expense line is **Chargeable**. The line property is inherited from the project because the category is not assigned a line property.

## Report

To see how the default line property is set up, run the **Line property setup** report. Click **Project management and accounting** \> **Reports** \> **Base data** \> **Setup** \> **Line property setup**.

## See also

[Set up a line property](set-up-a-line-property.md)

[Project/group line properties (form)](https://technet.microsoft.com/library/aa598358\(v=ax.60\))

[Line properties (form)](https://technet.microsoft.com/library/aa590082\(v=ax.60\))

  


