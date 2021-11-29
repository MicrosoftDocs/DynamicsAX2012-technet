---
title: Search for projects
TOCTitle: Search for projects
ms:assetid: 43de98c1-ca28-41db-a1d3-6bc414fd22c2
ms:mtpsurl: https://technet.microsoft.com/library/Aa496968(v=AX.60)
ms:contentKeyID: 36056881
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project search
- search for projects
audience: Application User
ms.search.region: Global
---

# Search for projects 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can search for project numbers at all levels in the project hierarchy. For example, to search for projects (parent projects and subprojects) whose project IDs start with 9003, do the following:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Select a project in the grid, and the press CTRL+F3 to open the **Inquiry** form.

3.  Remove existing filters: On the **Range** tab, select the lines in the grid, and then click the **Remove** button.

4.  In the **Field** list, select **Project ID**.
    

    > [!NOTE]
    > <P>This example is searching for projects based on project ID. If you want to search for projects according to other criteria, such as project manager or projected end date, choose one of those values in the <STRONG>Field</STRONG> list.</P>



5.  Type 9003\* in the criteria field, and then click **OK**. Only projects and subprojects whose IDs begin with 9003 are displayed in the project list.

6.  To show all projects again, press CTRL+SHIFT+F3.

## See also

[Finding, filtering, and sorting records](finding-filtering-and-sorting-records.md)

[Projects (form)](https://technet.microsoft.com/library/aa585245\(v=ax.60\))

[Inquiry (form)](https://technet.microsoft.com/library/aa575929\(v=ax.60\))

  


