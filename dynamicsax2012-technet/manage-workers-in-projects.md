---
title: Manage workers in projects
TOCTitle: Manage workers in projects
ms:assetid: 01b493bc-8690-4112-a8ae-4f0c77aa0aa6
ms:mtpsurl: https://technet.microsoft.com/library/Aa569691(v=AX.60)
ms:contentKeyID: 36055922
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- employee
- projects
- category validation
- period code
- worker
audience: Application User
ms.search.region: Global
---

# Manage workers in projects 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the following procedures to set up a worker record and define project-specific information for the worker.


> [!NOTE]
> <P>The procedure for completing this task was changed for Microsoft Dynamics AX 2012 R2. The updated procedure also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



## Create a new worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**. On the **Action Pane**, on the **Human resources** tab, in the **Personnel actions** group, click **Hire new worker**.

2.  In the **Create new worker** form, enter information about the new worker, and then click **Hire new worker**.

## Define a period code for a worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**. On the **Action Pane**, on the **Project management** tab, in the **Setup** group, click **Project setup**.

2.  In the **Project setup** form, in the **Period code** field, select a period code.


> [!NOTE]
> <P>To use timesheet functionality and generate the <STRONG>Missing timesheets</STRONG> report, you must select a period code for the worker.</P>



## Define a default category for hour transactions for a worker in Microsoft Dynamics AX 2012 R2

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**. On the **Action Pane**, on the **Project management** tab, in the **Setup** group, click **Project setup**.

2.  In the **Project setup** form, in the **Default category** field, select the default project category to use when hour transactions are posted for the worker.
    
    The selected category is entered automatically on all timesheet lines when the worker creates or modifies hour transactions on a timesheet. However, the category can be changed on the timesheet lines if a different category is appropriate.

## Set up category validation for a worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**. On the **Action Pane**, on the **Project management** tab, in the **Setup** group, click **Project setup**.

2.  In the **Project setup** form, select the **Category** check box.
    

    > [!IMPORTANT]
    > <P>You must set up category validation only if the validation system is applied in the legal entity. If this check box is not selected, worker/category validation is not enforced for the worker, even if validation is set to mandatory at the legal-entity level.</P>



3.  To continue setting up validation, follow these additional steps:
    
    1.  Select a worker, and then, on the **Action Pane**, click the **Project management** tab.
    
    2.  In the **Setup** group, click **Validation**, and then click **Assign categories**.
    
    3.  In the **Worker validation category assignments** form, select the validation groups or individual categories that the worker can enter hours for.

## Maintain the setup of project validation for a worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**. On the **Action Pane**, on the **Project management** tab, in the **Setup** group, click **Project setup**.

2.  In the **Project setup** form, select the **Project** check box.


> [!IMPORTANT]
> <P>You must set up project validation only if the validation system is applied in the legal entity. If this check box is not selected, project/worker validation is not enforced for the worker, even if validation is set to mandatory at the legal-entity level.</P>



## See also

[Set up validation groups](set-up-validation-groups.md)

[Worker/project validation groups (form)](https://technet.microsoft.com/library/aa615696\(v=ax.60\))

[Project setup (form)](https://technet.microsoft.com/library/hh209540\(v=ax.60\))

[Update worker periods (class form)](https://technet.microsoft.com/library/aa620393\(v=ax.60\))

[Assign and maintain worker periods](assign-and-maintain-worker-periods.md)

[Create and generate timesheet periods](create-and-generate-timesheet-periods.md)

[Workers (form)](https://technet.microsoft.com/library/aa583961\(v=ax.60\))

  


