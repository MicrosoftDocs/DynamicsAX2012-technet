---
title: Set up staff members
TOCTitle: Set up staff members
ms:assetid: 764a2b67-5542-4b0a-acd9-b987be0602cb
ms:mtpsurl: https://technet.microsoft.com/library/Hh597131(v=AX.60)
ms:contentKeyID: 39519185
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- staff member
- staff members
audience: Application User
ms.search.region: Global
---

# Set up staff members 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Before workers can perform their job duties in the retail store, you must set up the workers in Microsoft Dynamics AX. You must also assign appropriate permissions to the workers, so that they can log on and perform tasks by using the Microsoft Dynamics AX for Retail POS system. You must also set up the jobs and positions that are used in your retail stores, and then link workers to those jobs and positions.

For information about how to configure point of sale (POS) permissions, see [Set up permissions and operations](set-up-permissions-and-operations.md).

## Set up a retail job

After you set up POS permissions to specify the tasks that workers can perform by using the POS system, you must define the jobs that the workers can perform. You must then link POS permissions to those jobs.

1.  Click **Human resources** \> **Common** \> **Organization** \> **Jobs**.

2.  On the **Jobs** list page, on the **Action Pane**, in the **New** group, click **Job** to create a new job.

3.  Enter a job title and description.

4.  Click the **Job classification** FastTab. Then, in the **POS permission group** field, select the POS permissions that apply to the job. When a worker is associated with the job, the POS permissions that are assigned to the job control the actions that the worker can perform in the POS system.

5.  Complete any other fields that you require in the form.
    
    For general information about how to set up a job in Microsoft Dynamics AX, see [Key tasks: Jobs](key-tasks-jobs.md).

## Set up a position

A position is an individual instance of a job. You assign each worker to a position. By linking a worker to a position, you associate that worker with a specific job. Therefore, you also assign the POS permissions that the worker requires to use the POS system in the retail store.

1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Positions**.

2.  On the **Positions** list page, on the **Action Pane**, in the **New** group, click **Position** to create a new position.

3.  In the **Create new position** dialog box, in the **Job** list, select a retail job.

4.  Enter the date that the position becomes active, and then click **Create positions**.

5.  In the **Position** form, complete any other fields that you require in the form.
    
    You can hire a new worker directly from the **Position** form. Alternatively, you can create a worker, and then assign the worker to the retail position.
    
    For information about how to set up a retail worker, see the following procedure. For general information about how to set up a worker in Microsoft Dynamics AX, see [Key tasks: Workers](key-tasks-workers.md).

## Set up a retail worker

1.  Click **Retail** \> **Common** \> **Workers**.
    
    –or–
    
    Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  On the **Workers** list page, on the **Worker** tab, on the **Action Pane**, in the **New** group, click **Hire new worker**.

3.  In the **Create new worker** form, enter the worker’s name. In the **Worker type** field, select whether the worker is an employee or a contractor. Enter the date that the worker’s employment starts. Then click **Hire new worker**.
    

    > [!NOTE]
    > <P>The <STRONG>Personnel number</STRONG> field can be automatically populated based on the number sequence that is set up for the worker. The worker uses this number to log on to the POS system.</P>



4.  In the **Worker** form, on the **Worker summary** FastTab, in the **Address books** field, select the address book to assign the worker to. Retail uses the address book that you select to link the worker to a store.

5.  Click the **Retail** link, and then, in the **Screen layout ID** field, select the POS screen layout if the worker uses a special screen layout on the POS system. If the worker uses the POS screen layout that is assigned to the store, leave this field blank.

6.  In the **Employment type** field, select whether the staff member is a cashier, salesperson, or other type of employee.

7.  Under **POS authentication**, in the **Password** field, specify the password that the worker uses to log on to the POS system.

8.  To select a POS permission group for the worker, click the **POS permissions** link.

9.  In the **POS position permissions** form, do one of the following:
    
      - In the **Position** field, select a position for the worker.
    
      - Select the **Override permissions** check box, and then either select a permission group in the **POS permission group** field, or select the check boxes for the appropriate permissions.
    
    You must assign the worker to a position. Otherwise, the worker does not have appropriate access to the POS system.

10. Enter any other appropriate information in the **Profile**, **Employment**, **Absence**, **Compensation**, **Payroll**, and **Competencies and development** sections. For more information, see [Workers (form)](https://technet.microsoft.com/library/aa583961\(v=ax.60\)).
    
    For general information about how to set up a worker in Microsoft Dynamics AX, see [Key tasks: Workers](key-tasks-workers.md).

## See also

[About setting up staff](about-setting-up-staff.md)

[Set up permissions and operations](set-up-permissions-and-operations.md)

[Job (form)](https://technet.microsoft.com/library/hh209557\(v=ax.60\))

[Positions (form)](https://technet.microsoft.com/library/aa590982\(v=ax.60\))

[Worker (form) (Retail)](https://technet.microsoft.com/library/hh597277\(v=ax.60\))

  


