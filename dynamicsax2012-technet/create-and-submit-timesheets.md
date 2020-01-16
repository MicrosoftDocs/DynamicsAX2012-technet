---
title: Create and submit timesheets
TOCTitle: Create and submit timesheets
ms:assetid: 2895a8eb-abff-401f-bfff-7b282b6c1e26
ms:mtpsurl: https://technet.microsoft.com/library/Hh271481(v=AX.60)
ms:contentKeyID: 36384113
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- timesheet
- TSTimesheetsListPageEP
- create timesheet
- edit timesheet
- manage timesheets
audience: Application User
ms.search.region: Global
---

# Create and submit timesheets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Timesheets** list page to create and submit timesheets for the projects that you work on.

You can create new timesheets by entering lines in the **New timesheet** form, by copying lines from an existing timesheet, or by using existing lines that were saved as favorites.


> [!NOTE]
> <P>Before you can submit a timesheet, your user ID must be associated with a worker record. Also, depending on your role or the privileges that are assigned to you, you may need to go to your Employee services site before you complete the procedures in this topic.</P>



## Create a timesheet by adding new lines

1.  Click **Timesheets** on the top link bar.

2.  On the **Timesheets** list page, on the **Action Pane**, in the **New** group, click **New timesheet**.

3.  On the **New timesheet** page, the **Date** field displays the current date. To change the timesheet period, open the calendar, select a date within the period, and then click **Create**.

4.  On the **Edit timesheet** page, the **Work week** field displays the current work week. If the timesheet period covers multiple weeks, you can select another work week in the list.

5.  On the **Timesheet lines** FastTab, click **New line**. Alternatively, click **Copy from**, and then select from the following:
    
      - **Timesheet** – Copy timesheet lines from an existing timesheet.
    
      - **My favorites** – Create new timesheet lines by using the timesheet settings that you have selected as favorites.
    
      - **Assignments** – Create new timesheet lines from previously assigned projects and activities.
        

        > [!NOTE]
        > <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>



6.  In the **Legal entity** field, select the legal entity for which you want to report hours in this line.
    

    > [!IMPORTANT]
    > <P>The <STRONG>Legal entity</STRONG> field is available only if Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 Feature Pack is installed. Also, intercompany timesheet support must be enabled for your legal entity.</P>



7.  In the **Customer** field, select the customer for the project that you worked on. Then, in the **Project** field, select the appropriate project.
    
    You can also select the project first. If you do, the **Customer** field is filled in automatically.

8.  Optional: In the **Activity** field, select an activity.

9.  In the **Category** field, select a category, and then for each day, enter the number of hours worked.
    
    If you have Microsoft Dynamics AX 2012 R2 installed, the **Category** field displays a preselected category for hour transactions. If necessary, you can select another category.
    
    Enter hours in a decimal format. For example, if you worked for two hours and fifteen minutes, enter **2.25**.

10. If necessary, in the **Line property** field, select a property for the task. By default, the field displays the default property that was set up for the task.

11. Click the **Update** button at the right side of the line.
    

    > [!IMPORTANT]
    > <P>You must click the <STRONG>Update</STRONG> button before you can add another timesheet line or save the line as a favorite.</P>



12. Optionally, you can do the following:
    
      - To add information about the line, click **Details**, and then enter information on the **Timesheet line details** page.
    
      - To add comments about the timesheet line, click **Comments**, and then enter comments for an internal audience, an external audience, or both. Internal comments can be viewed by project managers. External comments are included on invoices.
    
      - To save the line as a favorite, select the check box, and then click **Save as favorites**.

13. To add more lines, click **New line**, and then repeat steps 6 through 11.

14. To submit the timesheet, click **Submit**. Depending on how your organization’s timesheet options were configured, your hours are either posted or sent for review.
    
    –or–
    
    To close the timesheet without submitting it, on the **Action Pane**, click **Save and close**.

## Create a timesheet based on previous timesheets

1.  Click **Timesheets** on the top link bar.

2.  On the **Timesheets** list page, click the timesheet that you want to copy lines from.

3.  On the **Action Pane**, in the **New** group, click **Copy selected timesheet**.

4.  On the **New timesheet** page, the **Date** field displays the current date. To change the timesheet period, open the calendar and select a date within the period.

5.  The **Work week** field displays the current work week. If the timesheet period covers multiple weeks, you can select another work week in the list.

6.  Make any necessary changes to the existing lines.

7.  To add new lines to the timesheet, follow steps 5 through 11 in the first procedure in this topic, “Create a timesheet by adding new lines.”

8.  To submit the timesheet, click **Submit**. Depending on how your organization’s timesheet options were configured, your hours are either posted or sent for review.
    
    –or–
    
    To close the timesheet without submitting it, on the **Action Pane**, click **Save and close**.

## Create a timesheet by using favorites

1.  Click **Timesheets** on the top link bar.

2.  On the **Timesheets** list page, on the **Action Pane**, in the **New** group, click **Create from favorites**.

3.  On the **New timesheet** page, the **Date** field displays the current date. To change the timesheet period, open the calendar and select a date within the period.

4.  The **Work week** field displays the current work week. If the timesheet period covers multiple weeks, you can select another work week in the list.

5.  On the **Timesheet lines** FastTab, all timesheet lines that have been saved as favorites are displayed. Make any necessary changes to the existing lines.

6.  To add new lines to the timesheet, follow steps 5 through 11 in the first procedure in this topic, “Create a timesheet by adding new lines.”

7.  To submit the timesheet, click **Submit**. Depending on how your organization’s timesheet options were configured, your hours are either posted or sent for review.
    
    –or–
    
    To close the timesheet without submitting it, on the **Action Pane**, click **Save and close**.

## See also

[Add, edit or delete timesheet delegates](add-edit-or-delete-timesheet-delegates.md)

[Modify or delete a timesheet](modify-or-delete-a-timesheet-in-enterprise-portal.md)

[Add details or comments to a timesheet](add-details-or-comments-to-a-timesheet.md)

  


