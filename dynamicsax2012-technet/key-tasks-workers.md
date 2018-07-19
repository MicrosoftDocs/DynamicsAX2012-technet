---
title: 'Key tasks: Workers'
TOCTitle: 'Key tasks: Workers'
ms:assetid: dd673ce0-e287-4c1b-b6cd-f7c57a144392
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227410(v=AX.60)
ms:contentKeyID: 36059683
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- employee
- worker
- workers
- worker tasks
- employees
- employee task
- employee tasks
- worker task
audience: Application User
ms.search.region: Global
---

# Key tasks: Workers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This information describes common tasks that are associated with maintaining worker records.

## What do you want to do?

Learn more about...

Create a worker record

Modify a worker’s position assignment

View a worker in the position hierarchy

View a worker’s employment history

View a worker’s absence history

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About workers](about-workers.md)

[About departments, jobs, and positions](about-departments-jobs-and-positions.md)

## Create a worker record

You can create a worker record in one of these ways:

  - Hire an applicant – When you hire an applicant, the applicant’s information is used to create a worker record. For information, see [Hire an applicant](hire-an-applicant.md).

  - Hire multiple people – You can create a mass-hire project to hire multiple people for the same job. For information, see [Key tasks: Mass hire projects](key-tasks-mass-hire-projects.md).

  - Hire a person – You can manually create a worker record for a person who isn’t an applicant and who wasn’t part of a mass-hire project. See the following procedures for more information.

### Hire a person for an open position

1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Open positions**.

2.  Select the open position to fill.

3.  On the **Action Pane**, click **Hire**.

4.  Enter the first, middle, and last name of the person you’re hiring to fill the position.

5.  Select the legal entity to associate to the worker. The default legal entity is the legal entity that you’re currently logged on to.

6.  Enter a personnel number for the worker.
    
    If a number sequence code is specified for the personnel number reference in the **Number sequence** area of the **Human resources shared parameters** form, you can’t change the information in this field.

7.  The remaining fields in the form contain default information. This information was specified when the position was created. You can accept the default information or change it.
    
    If a personnel action type is required, your organization has personnel action types enabled. For more information, see [Personnel actions](personnel-actions.md).

8.  Click **Hire new worker** to open the **Worker** form, where you can enter more information about the worker.

### Hire a person without assigning them to a position

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  On the **Action Pane**, on the **Worker** tab, in the **New** group, click **Hire new worker**.

3.  Enter the first, middle, and last name of the person you’re hiring to fill the position.

4.  Select the legal entity to associate to the worker. The default legal entity is the legal entity that you’re currently logged on to.

5.  Enter a personnel number for the worker.
    
    If a number sequence code is specified for the personnel number reference in the **Number sequence** area of the **Human resources shared parameters** form, you can’t change the information in this field.

6.  Select the worker type.

7.  Enter the date and time when the worker will start their employment.

8.  If the worker is a contractor whose affiliation with the company, organization, or legal entity is limited in time, enter the date when the worker’s affiliation will end.
    
    If a personnel action type is required, your organization has personnel action types enabled. For more information, see [Personnel actions](personnel-actions.md).

9.  Click **Hire new worker** to open the **Worker** form, where you can enter more information about the worker.

Back to top

## Modify a worker’s position assignment

To change a position assignment for a worker, add a position assignment to a new worker, transfer a worker from one position to another position, or end a worker’s position assignment, complete one of these procedures.


> [!NOTE]
> <UL>
> <LI>
> <P>As of Microsoft Dynamics AX 2012 R3 Cumulative Update 8, worker positions include a work cycle. If a worker has multiple positions, all positions must have the same work cycle. For more information, see <A href="work-cycle-and-work-period-tasks.md">Work cycle and work period tasks</A>.</P>
> <LI>
> <P>If you use the <STRONG>Applications</STRONG> list page or a mass-hire project to hire a worker, a position is already assigned to the worker.</P>
> <LI>
> <P>You can’t assign a retired or filled position to a worker.</P></LI></UL>



### Add or modify a position assignment for a worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select the worker to assign to a position.

3.  On the **Action Pane**, on the **Worker** tab, in the **Position assignment** group, click **Worker position assignments**.

4.  To create a position assignment for the worker, click **Add assignment**.
    
    To change an existing position assignment for the worker, select the position assignment to change, and then click **Edit assignment**. Go to step 6.

5.  Select the position to assign to the worker.

6.  Enter the starting and ending dates and times for the position assignment.

7.  Select a reason code that indicates why you’re changing or adding a position assignment for the worker. For example, if the worker is being assigned to a different position because of low performance, you could select a reason code that indicates that.

8.  If the position assignment is the worker’s primary position assignment, select the **Make primary** check box.

9.  Click **Create position assignment** or **Update worker assignment**.

### Transfer a worker to another position

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select the worker to transfer.

3.  On the **Action Pane**, on the **Worker** tab, in the **Personnel actions** group, click **Transfer worker**.

4.  Enter the ending date and time for the worker’s current position assignment.

5.  Select a reason code that indicates why you’re transferring the worker from their current position.

6.  If the worker’s current position should be retired, select the **Retire position** check box. However, if another worker will fill the position that the current worker is transferring from, don’t select the check box.

7.  Select the job and position to transfer the worker to.

8.  Select the **Primary** check box for the new position assignment if the position is the worker’s primary position.

9.  Enter or accept the default employment factor for the new position assignment. To indicate that the position assignment for the worker is part-time, enter a number that is less than 1.

10. Enter the starting date and time for the new position assignment.

11. If the worker is a contractor whose affiliation with the company, organization, or legal entity is limited in time, enter the date when the worker’s position assignment will end.

12. Select the reason code that indicates why you’re transferring the worker to the new position.

13. Click **Transfer worker**.

### End a position assignment for a worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker.

3.  On the **Action Pane**, on the **Worker** tab, in the **Position assignment** group, click **Worker position assignments**.

4.  Click **End**.

5.  Enter the ending date and time of the position assignment.

6.  Select the reason code that indicates why you’re ending the position assignment.

7.  Click **Retire worker assignment**.
    

    > [!NOTE]
    > <P>When you end a position assignment for a worker, you don’t terminate the worker’s employment. To terminate a worker’s employment, see <A href="terminate-employment.md">Terminate employment</A>.</P>



Back to top

## View a worker in the position hierarchy

If a worker is assigned to a position, you can use the **Position hierarchy** form to view the worker’s location in an organizational hierarchy.

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select the worker to view in the hierarchy.

3.  On the **Action Pane**, on the **Worker** tab, in the **Related information** group, click **View in hierarchy**.

Back to top

## View a worker’s employment history

Complete these steps to display the **Employment history** form, where you can view a worker’s employment history or add employment information for a worker. For more information about worker employment, see [About employment affiliations](about-employment-affiliations.md).

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker.

3.  On the **Action Pane**, on the **Worker** tab, in the **Versions** group, click **Employment history**.

Back to top

## View a worker’s absence history

Complete these steps to display the **Absence history** form, where you can view the absence journals and the absence transactions in each journal for a worker.

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker.

3.  On the **Action Pane**, on the **Worker** tab, in the **Related information** group, click **Absence** \> **Absence history**.

Back to top

## Find form help

[Worker (form)](https://technet.microsoft.com/en-us/library/hh209054\(v=ax.60\))

[Position assignments (form)](https://technet.microsoft.com/en-us/library/hh450759\(v=ax.60\))

[Transfer worker (form)](https://technet.microsoft.com/en-us/library/hh335182\(v=ax.60\))

[Organization hierarchies (form)](https://technet.microsoft.com/en-us/library/hh209427\(v=ax.60\))

[Employment history (form)](https://technet.microsoft.com/en-us/library/hh781091\(v=ax.60\))

[Absence history (form)](https://technet.microsoft.com/en-us/library/aa582545\(v=ax.60\))

## Find related tasks

[Approve or reject absences](approve-or-reject-absences.md)

[(USA) Key tasks: Form I-9 verification](usa-key-tasks-form-i-9-verification.md)

[Key tasks: Compensation plans](key-tasks-compensation-plans.md)

[(USA) Grant or deny an accommodation request](usa-grant-or-deny-an-accommodation-request.md)

[Loan an item to a worker, contact, or applicant](loan-an-item-to-a-worker-contact-or-applicant.md)

[Terminate employment](terminate-employment.md)

  


