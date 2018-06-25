---
title: 'Key tasks: Courses'
TOCTitle: 'Key tasks: Courses'
ms:assetid: 8f5d3c5d-c3b6-4742-8de6-716c3defc6c6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677350(v=AX.60)
ms:contentKeyID: 49384124
ms.date: 09/02/2014
mtps_version: v=AX.60
f1_keywords:
- classes
- Courses
- training courses
- employee classes
- employee courses
---

# Key tasks: Courses [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information about creating courses and items related to courses such as agendas, sessions, and tracks.

## What do you want to do?

Learn more about...

Create a course record

Create a course agenda

Specify a course description for a course

Create a course track

Create a course session

Assign an instructor to a course

Update the status of a course

Register a person for a course

Drop a participant from a course

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About courses](about-courses.md)

 

## Create a course record

Before workers can register for courses, you must create a course record for each course. Complete the following steps to create a course record.

1.  Click **Human resources** \> **Common** \> **Courses** \> **Courses**.

2.  On the **Action Pane**, click **Courses**.

3.  Select the type of course and organizer for the course. For more information about course types, see [Course types (form)](https://technet.microsoft.com/en-us/library/aa618160\(v=ax.60\)).

4.  In the **Setup** field, select the course setup. You can select from the following options:
    
    1.  **Standard**
    
    2.  **Agenda**
    
    3.  **Agenda + session**
    
    For more information about course setups, see [About courses](about-courses.md).

5.  If you want workers to be able to register for the course using Enterprise Portal for Microsoft Dynamics AX, select the **Display on Enterprise Portal** check box.

6.  Select the location and classroom for the course.

7.  Enter the starting and ending dates for the course. You can also enter a registration deadline for the course.

8.  To enforce restrictions on the number of participants who can register for the course, enter values in the following fields:
    
    1.  **Minimum number of participants**
    
    2.  **Max. number of participants**

9.  Review the remaining procedures in this topic to enter additional information about the course.

Back to top

 

## Create a course agenda

To enter more specific information about what the course will teach participants, you can create an agenda for the course. For more information about course agendas, see [About courses](about-courses.md).


> [!NOTE]
> <P>You cannot create course agendas for a course with a setup of <STRONG>Standard</STRONG>.</P>



1.  Click **Human resources** \> **Common** \> **Courses** \> **Courses**.

2.  In the **Courses** list, select the course to create an agenda for.

3.  On the **Action Pane**, in the **Related information** group, click **Agenda**.
    

    > [!NOTE]
    > <P>If the <STRONG>Agenda</STRONG> option is not available, open the <STRONG>Courses</STRONG> form, and then, on the <STRONG>General</STRONG> FastTab, select one of the following in the <STRONG>Setup</STRONG> field: To create an agenda only, select <STRONG>Agenda</STRONG>; to create an agenda in addition to breakout sessions, select <STRONG>Agenda + session</STRONG>.</P>



4.  In the **Agenda** form, click **New**, and then enter the **Date** for the first agenda item.

5.  Enter a **Start time** and an **End time** for the agenda item.

6.  Enter a **Description** of the agenda item.

7.  Repeat steps 4 through 6 for each additional item on the agenda.

Back to top

 

## Specify a course description for a course

You can enter a unique description for a course or you can use the description entered for the type of course. The course description for active courses is displayed on Enterprise Portal.

1.  Click **Human resources** \> **Common** \> **Courses** \> **Courses**.

2.  Select the course to create a course description for.

3.  On the **Action Pane**, in the **Related information** group, click **Descriptions**.

4.  In the left pane, select **Note**.

5.  To enter a unique description for the selected course, type your text in the **Courses** field.
    
    To reuse the description from the course type of the selected course, click **Retrieve from type** to copy the text that is specified for the course type. For more information, see [Course types (form)](https://technet.microsoft.com/en-us/library/aa618160\(v=ax.60\)).

Back to top

 

## Create a course track

Use course tracks to divide a course into separate areas of interest. For example, you can divide a course that introduces a new product line into a sales track in which sales representatives learn key selling points, and a service and support track that instructs support personnel on common or known product support issues.


> [!NOTE]
> <P>You can only create tracks for course with a setup of <STRONG>Agenda + session</STRONG>.</P>



1.  Click **Human resources** \> **Common** \> **Courses** \> **Courses**.

2.  Select a course to create a track for.

3.  On the **Action Pane**, in the **Related information** group, click **Track**.

4.  Click **New**, and then enter a name and a description for the track.

Back to top

 

## Create a course session

You can create course sessions to define one or more breakout sessions covering different areas of learning in a course track. You must create one or more tracks before you can create a course session.


> [!NOTE]
> <P>You can only create sessions for course with a setup of <STRONG>Agenda + session</STRONG>.</P>



1.  Click **Human resources** \> **Common** \> **Courses** \> **Courses**.

2.  In the **Courses** list, select the course to create a session for.

3.  On the **Action Pane**, in the **Related information** group, click **Sessions**.

4.  In the **Sessions** form, click **New**.

5.  Enter the name of the session and select the track that the session is associated with.

Back to top

 

## Assign an instructor to a course

Before you can assign an instructor to a course or to a track and session, you must set up instructors. For more information, see [Set up course instructors](set-up-course-instructors.md). Complete the following steps to assign an instructor to a course:

1.  Click **Human resources** \> **Common** \> **Courses** \> **Courses**.

2.  Select the course to assign an instructor to.

3.  On the **Action Pane**, in the **Related information** group, click **Course instructors** to open the **Course instructors** form.

4.  Click **New**.

5.  Select the instructor to assign to the course.

Back to top

 

## Update the status of a course

The status of a course determines the actions that you or participants can complete for the course. For more information, see [About courses](about-courses.md). Use the following steps to update the status of a course:

1.  Click **Human resources** \> **Common** \> **Courses** \> **Courses**.

2.  In the **Courses** list, select the course to change the status of.

3.  On the **Action Pane**, in the **Status** group, click the status for the course.

Back to top

 

## Register a person for a course

You can register workers, contacts, and applicants for a course. Use the following steps to register a person for a course.

1.  Click **Human resources** \> **Common** \> **Courses** \> **Courses**.

2.  Select the course for which you want to register people.
    

    > [!NOTE]
    > <P>The course status must be <STRONG>Open</STRONG> before you can register people for the course.</P>



3.  Click **Course participants** to open the **Course participants** form.

4.  Click **New**.

5.  In the **Person** field, select the person to register for the course.
    
    Participants automatically have the status of **Registered** unless the number of registered participants exceeds the maximum number of participants defined for the course. If this occurs, the excess participants will be automatically assigned the status of **Waiting list**.

6.  If the course has tracks and sessions, click **Registration list** to open the **Registration list** form where you can select the sessions in the course to register the participant for.

Back to top

 

## Drop a participant from a course

Periodically, participants who are registered for a course must drop the course. Complete the following steps to drop a participant from a course:

1.  Click **Human resources** \> **Common** \> **Courses** \> **Courses**.

2.  Select the course to drop a participant for.

3.  On the **Action Pane**, click **Course participants** to open the **Course participants** form.

4.  Select the participant to drop from the course.

5.  Click **Status** \> **Drop**.

Back to top

## Find form help

[Course types (form)](https://technet.microsoft.com/en-us/library/aa618160\(v=ax.60\))

[Course groups (form)](https://technet.microsoft.com/en-us/library/aa585035\(v=ax.60\))

[Course locations (form)](https://technet.microsoft.com/en-us/library/aa616795\(v=ax.60\))

[Course participants (form)](https://technet.microsoft.com/en-us/library/aa558397\(v=ax.60\))

## Find related tasks

[Set up course instructors](set-up-course-instructors.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

