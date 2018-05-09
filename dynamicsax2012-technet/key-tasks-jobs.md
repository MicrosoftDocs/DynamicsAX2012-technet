---
title: 'Key tasks: Jobs'
TOCTitle: 'Key tasks: Jobs'
ms:assetid: c12c190f-2218-4258-a3b8-30d1794926d1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242830(v=AX.60)
ms:contentKeyID: 36059269
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- job
- create a job
- jobs
- job function
- job task
- job type
---

# Key tasks: Jobs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can create jobs, you must set up some reference information that you can use for jobs. The procedures in this topic are listed in the order in which you should complete them.

## What do you want to do?

Learn more about...

Set up job types

Set up job functions

Set up job titles

Set up areas of responsibility

Set up job tasks

Create a job template

Create a job

Recruit for a job

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About departments, jobs, and positions](about-departments-jobs-and-positions.md)

## Set up job types

Job types can be used to classify jobs into categories and are also useful when you set up compensation management.


> [!NOTE]
> <P>Job types are not required. However, if you plan to use job types when you set up eligibility rules for compensation management, you should set up job types before you set up jobs. When you create jobs, you can then assign job types to the jobs.</P>



1.  Click **Human resources** \> **Setup** \> **Organization** \> **Job types**.

2.  Click **New**.

3.  Enter a name for the job type.

4.  Enter a brief description for the job type.

5.  Select one of the following options to indicate the exempt status of jobs with this job type:
    
      - **Exempt** – Jobs are exempt from overtime under the Fair Labor Standards Act (FLSA).
    
      - **Non-exempt** – Jobs are not exempt from overtime under the FLSA.
    
      - **Does not apply** – FLSA coverage is not applicable.

6.  Complete steps 2 through 5 for each additional job type.

Back to top

## Set up job functions

Job functions are tasks, duties, or responsibilities that are assigned to a job and are useful when you set up compensation management. A job can have one or more job functions assigned to it.


> [!NOTE]
> <P>Job functions are not required However, if you plan to use job functions when you set up eligibility rules for compensation management, you should set up job functions before you set up jobs. When you create jobs, you can then assign job functions to the jobs.</P>



1.  Click **Human resources** \> **Setup** \> **Organization** \> **Job functions**.

2.  Click **New**.

3.  Enter an identification code for the job function.

4.  Enter a brief description of the job function.

5.  Complete steps 2 through 4 for each additional job function.

Back to top

## Set up job titles

Before you create jobs, you must set up titles for those jobs. Positions inherit job titles from the jobs that the positions are associated with.


> [!NOTE]
> <P>Titles are not exclusive to jobs. The titles that you set up in this procedure can also be used for positions and workers.</P>



1.  Click **Human resources** \> **Setup** \> **Workers** \> **Titles**.

2.  Click **New**.

3.  Enter the name of the job title.

4.  Complete steps 2 and 3 for each title in your company or organization.

Back to top

## Set up areas of responsibility

Areas of responsibility are the work roles, processes, products, and actions that a worker is responsible for in a job.

1.  Click **Human resources** \> **Setup** \> **Organization** \> **Areas of responsibility**.

2.  Click **New**.

3.  Enter the name for the area of responsibility.

4.  Enter a brief description of the area of responsibility.

5.  Optional: Enter additional information about the area of responsibility. For example, if the area of responsibility is Sec-1 and the description is Secure area 1, you could list the rooms that are included in the specific section of the building that a person with this area of responsibility is responsible for.

6.  Complete steps 2 through 4 for each area of responsibility in your company or organization.
    
    After you create the areas of responsibilities, they will be available to select from in the **Job** form.

Back to top

## Set up job tasks

Positions inherit job tasks from the jobs that the positions are associated with.

1.  Click **Human resources** \> **Setup** \> **Organization** \> **Job tasks**.

2.  Click **New**.

3.  Enter a name for the job task.

4.  Enter a brief description of the job task.

5.  Optional: Enter additional information about the job task. For example, if the job task is Sec-Equipment and the description is Ensure all security equipment is functioning correctly, you could list specific information about the security equipment.

Back to top

## Create a job template

You can use a job template to define job information that applies to multiple jobs, and then you can create jobs from the template. By using job templates, you do not have to manually enter the same information into jobs that are similar.

1.  Click **Human resources** \> **Setup** \> **Organization** \> **Job templates**.

2.  Click **New**.

3.  Enter a unique name for the job template.

4.  Enter a brief description of the job template.
    
    This description is displayed in the **Description** column in the grid in the **Job templates** form and is available in the **Job template** field in the **Copy from template** form.

5.  Optional: Enter additional information about the job template. For example, you could describe the jobs that this template should be used to create.

6.  Optional: Add competency requirements to the job template. To do this, complete one or more of the following tasks:
    

    > [!NOTE]
    > <P>Before you complete this step, you must set up competencies.</P>

    
      - On the **Skills** FastTab, add skills that might be required for jobs that are created from this template.
    
      - On the **Certificates** FastTab, add certificates that might be required for jobs that are created from this template.
    
      - On the **Tests** FastTab, add tests that might be required for jobs that are created from this template.
        

        > [!NOTE]
        > <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>

    
      - On the **Education** FastTab, add education information that might be required for jobs that are created from this template.
    
      - On the **Screenings** FastTab, add screenings that might be required for jobs that are created from this template.
        

        > [!NOTE]
        > <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>

    
    The competencies that you add to the job template will be included in the competency requirements for jobs that you create from this template.

7.  Optional: On the **Job tasks** FastTab, add job tasks to the job template.

8.  Optional: On the **Areas of responsibility** FastTab, add areas of responsibility to the job template.

9.  Optional: On the **Action Pane**, click **ADA** to set up or print information about physical requirements associated with jobs that are created from this template.

Back to top

## Create a job

You must create jobs before you can create positions. Only the job name is required to create a job. However, you can also add information to the job record. Some of the additional information will be inherited by the positions that are associated with the job.

1.  Click **Human resources** \> **Common** \> **Organization** \> **Jobs**.

2.  On the **Action Pane**, click **Job**.

3.  Enter a name for the job.
    

    > [!NOTE]
    > <P>The remaining steps in this procedure are optional.</P>



4.  Press CTRL+S to save the new job record.

5.  Use one of the following methods to add information to the job:
    
      - To copy information from a template or from an existing job, complete steps 6 through 9.
    
      - To manually enter information, go to step 10, and then complete steps 10 through 24.

6.  On the **Action Pane**, click **Copy from**, and then select **Copy from template** or **Copy from job**.

7.  Select a job template or an existing job to create the job from.

8.  In the **Copy** field group, select the information to copy information from.
    
    For example, to copy only the areas of responsibility information to the new job, select the **Responsibility** check box.

9.  Click **OK**. The information that you selected to copy is added to the job.
    
    To enter additional information for the job, complete one or more of steps 10 through 24.

10. Enter a brief description of the job.

11. Select a title for the job.

12. Indicate the number of positions that are allowed for the job.
    
      - **Maximum positions** – Select this option and then enter the maximum number of positions that are allowed for the job.
    
      - **Unlimited** – Select this option to indicate that an unlimited number of positions are allowed for the job.

13. Enter an employment factor from 0 to 1. The value 1 indicates a full-time job. For part-time employment, enter a number between 0 and 1. For example, a half-time job can be .5.

14. On the **Job classification** FastTab, select a job type to associate with the job.

15. Enter additional information about the job.

16. Select a job function.

17. On the **Compensation** FastTab, select a wage level for the job. For more information about wage levels, see [About compensation plans](about-compensation-plans.md).

18. Select the survey company that is responsible for the survey that was applied to establish the market-based pay range for this job.

19. Enter the job code that the survey company uses for this job.

20. Enter the market price range information for the job from the following options:
    
      - **Source** – Enter the source of the information for the market-based pay range.
    
      - **Low threshold** – Enter the minimum amount that a worker in this job would get paid.
    
      - **Control point** – Enter the base amount that a worker in this job would get paid.
    
      - **High threshold** – Enter the maximum amount that a worker in this job would get paid.

21. Add competency requirements to the job. To do this, complete one or more of the following tasks:
    

    > [!NOTE]
    > <P>Before you complete this step, you must set up competencies.</P>

    
      - On the **Skills** FastTab, add skills that might be required for the job.
    
      - On the **Certificates** FastTab, add certificates that might be required for the job.
    
      - On the **Tests** FastTab, add tests that might be required for jobs that are created from this template.
        

        > [!NOTE]
        > <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>

    
      - On the **Education** FastTab, add education information that might be required for jobs that are created from this template.
    
      - On the **Screenings** FastTab, add screenings that might be required for jobs that are created from this template.
        

        > [!NOTE]
        > <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>



22. On the **Job tasks** FastTab, add job tasks to the job.

23. On the **Areas of responsibility** FastTab, add areas of responsibility to the job.

24. On the **Action Pane**, click **ADA** to set up or print information about physical requirements associated with the job.

Back to top

## Recruit for a job

After you create jobs, you can create recruitment projects to recruit people to fill the positions for those jobs. For more information, see [Create a recruitment project](create-a-recruitment-project.md).

Back to top

## Find form help

[Job templates (form)](https://technet.microsoft.com/en-us/library/aa583740\(v=ax.60\))

[Job tasks (form)](https://technet.microsoft.com/en-us/library/aa573096\(v=ax.60\))

[Job functions (form)](https://technet.microsoft.com/en-us/library/hh209705\(v=ax.60\))

[Job types and exempt status (form)](https://technet.microsoft.com/en-us/library/hh209312\(v=ax.60\))

[Job (form)](https://technet.microsoft.com/en-us/library/hh209557\(v=ax.60\))

## Find related tasks

[Key tasks: Departments](key-tasks-departments.md)

[Key tasks: New worker positions](key-tasks-new-worker-positions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

