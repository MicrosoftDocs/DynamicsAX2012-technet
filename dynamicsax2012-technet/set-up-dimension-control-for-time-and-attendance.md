---
title: Set up dimension control for time and attendance
TOCTitle: Set up dimension control for time and attendance
ms:assetid: d44960f4-e506-4eb0-a824-822ef8109809
ms:mtpsurl: https://technet.microsoft.com/library/Aa551087(v=AX.60)
ms:contentKeyID: 36059519
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up dimension control for time and attendance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can configure dimension parameters for different types of jobs. Project activities and absence registrations are examples of job types. For each job type, select one of the following settings:

  - **Job** - Dimension can only be taken from the **Job** field.

  - **Worker** - Dimension can only be taken from the **Worker** field.

  - **Job -\> worker** - Dimension will be taken from the **Job** field. If no dimension is provided in the **Job** field, it is taken from the **Worker** field.

  - **Worker -\> job** - Dimension will be taken from the **Worker** field. If no dimension is provided in the **Worker** field, it is taken from the **Job** field.

## Project jobs

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Time and attendance parameters**. In the upper left part of the form, click **Project**.

2.  Select a dimension parameter in the **Dimension** field.

## Indirect activities

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Time and attendance parameters**. In the left pane, click **Indirect activities**.

2.  In the **Job** and **Break** fields, select the relevant dimensions.

## Absence registrations

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Time and attendance parameters**. In the left pane, click **General**.

2.  In the **Absence** field, select the relevant dimension.

## See also

[About dimension control for time and attendance](about-dimension-control-for-time-and-attendance.md)

  


