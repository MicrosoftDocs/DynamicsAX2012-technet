---
title: Create a project
TOCTitle: Create a project
ms:assetid: 193c2e57-e878-4c54-ac9b-58f2214f511a
ms:mtpsurl: https://technet.microsoft.com/library/Aa569913(v=AX.60)
ms:contentKeyID: 36056109
author: Khairunj
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- create project
- new project
- project copy wizard
audience: Application User
ms.search.region: Global
---

# Create a project 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to create projects in Microsoft Dynamics AX in two ways: by entering formation manually in the **Create project** form and by using the Project Copy Wizard.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, you can create a project by synchronizing data with an existing project in Microsoft Project. For more information, see <A href="create-or-update-a-project-by-using-microsoft-project.md">Create or update a project by using Microsoft Project</A>.</P>



## Create a project manually

For Fixed-price and Investment projects, a companion estimate project is created automatically. Note that an estimate project, despite the name, is not a project in the same sense that other Microsoft Dynamics AX projects are. An estimate project serves as a container for the options that specify how revenue is recognized in a project.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  On the **Action Pane**, on the **Project** tab, in the **New** group, click **Project**.

3.  In the **Create project** form, in the **Project type** field, select the type of project to create.

4.  Enter information in the other fields to set up the project.

5.  Click **OK**.

You can also add subprojects to a project. When you create a subproject, it automatically inherits the project type of the parent project. If necessary, you can change the project type of the subproject. For more information, see [Create a subproject](create-a-subproject.md).

## Copy a project by using a wizard

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  On the **Action Pane**, on the **Project** tab, in the **New** group, click **Copy project**.

3.  Follow the instructions in the wizard to customize your copy of the source project.


> [!NOTE]
> <P>You can use the wizard to copy a single project or a project tree structure that includes a parent project and its subprojects. To make a project available as a source to be copied, select the <STRONG>Project template</STRONG> check box on the <STRONG>Project hierarchy</STRONG> tab in the <STRONG>Projects</STRONG> form. To make a project tree structure available for copying, only the parent project must be defined as a project template.</P>



## See also

[Automatically generate project IDs](automatically-generate-project-ids.md)

[Create or link to a collaboration workspace (Project)](create-or-link-to-a-collaboration-workspace-project.md)

[Create project (form)](https://technet.microsoft.com/library/aa550120\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/library/aa585245\(v=ax.60\))

[Project copy wizard (form)](https://technet.microsoft.com/library/aa556743\(v=ax.60\))

[About using the Time and material project type for a fixed-price project](about-using-the-time-and-material-project-type-for-a-fixed-price-project.md)

  


