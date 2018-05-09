---
title: Configure project budget overrun settings
TOCTitle: Configure project budget overrun settings
ms:assetid: 11137a2f-8a8a-4cf9-a9be-26f783bb4808
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242140(v=AX.60)
ms:contentKeyID: 36056031
ms.date: 09/21/2015
mtps_version: v=AX.60
f1_keywords:
- project
- budget
- budget overrun
- budget settings
- overrun
- overrun option
- overrun settings
- project budget
- project budget overrun option
- project budget settings
- project overrun
- project budget overrun settings
---

# Configure project budget overrun settings 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The default setting for project budgets enables users to post a transaction even if the transaction will cause a budget overrun. However, when you create a budget for a project, you can override the default overrun selections.


> [!NOTE]
> <P>When you change the default overrun option, the change applies only to new projects. The overrun option on existing projects is not affected.</P>



## Define the default overrun option for all new projects

1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**.

2.  In the **Project management and accounting parameters** form, click **Cost control**.

3.  In the **Budget control** section, in the **Budget overrun default** field, select the overrun option that you want to use as the default for all new projects from the following options:
    
      - **Disallow overruns** – Users cannot enter a transaction.
    
      - **Warn of overruns** – Users receive a warning when they enter a transaction. The transaction is processed normally.
    
      - **Allow overruns** – Users do not receive a warning when they enter a transaction. The transaction is processed normally.

## Define an overrun option for specific user groups and projects or project groups

If you define overrun options for specific user groups or projects in the **Project budget settings for user groups** form, those selections override the selections that you make in the **Project management and accounting parameters** form.


> [!IMPORTANT]
> <P>If a user is a member of two groups that have different options for the same project or project group, the user is granted the more permissive option.</P>



1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**.

2.  In the **Project management and accounting parameters** form, click **Cost control**.

3.  In the **Budget control** section, click **Settings...**.

4.  In the **Project budget settings for user groups** form, in the **User group** field, select a user group to define the overrun option for.

5.  In the **Valid for** column, select a project option for the selected user group:
    
      - **Table** – The overrun option applies only to a specific project.
    
      - **Group** – The overrun option applies only to a specific project group.
    
      - **All** – The overrun option applies to all projects that do not have a different option specified in the **Projects** form.

6.  In the **Project/Project group** column, select the project or project group to define the overrun option for.
    

    > [!NOTE]
    > <P>This field is not available if <STRONG>All</STRONG> is selected in the <STRONG>Valid for</STRONG> column.</P>



7.  In the **Overrun option** column, select the option for the specified user group in the selected project or project group:
    
      - **Disallow overruns** – Users cannot enter a transaction.
    
      - **Warn of overruns** – Users receive a warning when they enter a transaction. The transaction is processed normally.
    
      - **Allow overruns** – Users do not receive a warning when they enter a transaction. The transaction is processed normally.

## See also

[About setting up a project budget](about-setting-up-a-project-budget.md)

[Configure project budget control](configure-project-budget-control.md)

[Create and submit an original project budget](create-and-submit-an-original-project-budget.md)

[Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\))

[Project budget settings for user groups (form)](https://technet.microsoft.com/en-us/library/hh242598\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

