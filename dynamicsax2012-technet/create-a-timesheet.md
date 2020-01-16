---
title: Create a timesheet
TOCTitle: Create a timesheet
ms:assetid: 991dcea3-93a8-4aa2-93cf-eedc029b87d0
ms:mtpsurl: https://technet.microsoft.com/library/Hh209420(v=AX.60)
ms:contentKeyID: 36058687
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- timesheet
- Favorites template
- timesheet template
- timesheet detail
audience: Application User
ms.search.region: Global
---

# Create a timesheet 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create a timesheet by using an empty timesheet form. You can also base a new timesheet on information from a previous timesheet, saved lines, or project and activity assignments in the **My favorites** form. If you are designated as a delegate, you can also enter a timesheet for another worker.

By default, the **All timesheets** list page displays all your timesheets for the current period. Use the **Show** field to filter your timesheet list by time period or project, or to view timesheets that you created on behalf of other workers.

### Create a timesheet by using an empty timesheet form

1.  Depending on your version of the program, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R2: Click **Project management and accounting** \> **Common** \> **Timesheets** \> **My timesheets**.
    
      - Otherwise: **Home**\> **Common** \> **Timesheets** \> **All timesheets**.

2.  On the **All timesheets** list page, on the **Action Pane**, on the **Timesheets** tab, click **New timesheet**.

3.  In the **New timesheet** form, the **Date** field displays the current date. To change the timesheet period, open the calendar and select a date within the period.
    

    > [!TIP]
    > <P>The <STRONG>Work week</STRONG> field displays the current work week. If the timesheet period covers multiple weeks, you can select another work week in the list.</P>



4.  Click **New line** or **Copy from** and select one of the following options:
    
      - **Timesheet** – Copy timesheet lines from an existing timesheet.
    
      - **My favorites** – Create new timesheet lines by using the timesheet settings that you selected as favorites.
    
      - **Assignments** – Create new timesheet lines from assigned projects and activities that are included in the time period that you are creating a timesheet for.
        

        > [!NOTE]
        > <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>



5.  In the **Legal entity** field, select the legal entity for which you performed project work.
    

    > [!NOTE]
    > <P>The <STRONG>Legal entity</STRONG> field is available only if intercompany timesheet support has been enabled for your legal entity.</P>



6.  In the **Project** field, select the project that you are entering time for. The **Customer** field is filled in automatically.

7.  Select information in the **Category** and **Activity** fields as required.
    
    In Microsoft Dynamics AX 2012 R2, the default category is the category that was selected in the **Project setup** form. You can select another category. For more information, see [Project setup (form)](https://technet.microsoft.com/library/hh209540\(v=ax.60\)).

8.  Enter the number of hours that you worked each day. Enter hours in a decimal format. For example, if you worked for two hours and fifteen minutes, enter 2.25.

9.  Optionally, you can do the following:
    
      - To add information about taxes and financial dimensions, click **Details**, and then enter information in the **Timesheet line details** form.
    
      - To add comments about the timesheet line, click **Comments**, and then enter comments for an internal audience, an external audience, or both. Internal comments can be viewed by project managers. External comments are included on invoices.
    
      - To save the line as a favorite, select the check box, and then click **Save as favorites**.

10. If multiple combinations of project, activity, and category are to be associated with this timesheet, repeat steps 4 through 9 as required.

11. Click **Submit** to send the timesheet to the approval workflow.

### Create a timesheet based on previous timesheets

1.  Depending on your version of the program, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R2: Click **Project management and accounting** \> **Common** \> **Timesheets** \> **My timesheets**.
    
      - Otherwise: **Home**\> **Common** \> **Timesheets** \> **My timesheets**.

2.  On the **All timesheets** list page, select the timesheet that you want to copy.

3.  On the **Action Pane**, on the **Timesheets** tab, click **Copy selected timesheet**.

4.  Confirm your selections, and then enter the number of hours that you worked each day. Enter hours in a decimal format. For example, if you worked for two hours and fifteen minutes, enter 2.25.

5.  Optionally, you can do the following:
    
      - To add information about taxes and financial dimension, click **Details**, and then enter information in the **Timesheet line details** form.
    
      - To add comments about the timesheet line, click **Comments**, and then enter comments for an internal audience, an external audience, or both. Internal comments can be viewed by project managers. External comments are included on invoices.
    
      - To save the line as a favorite, select the check box, and then click **Save as favorites**.

6.  If you want to add lines to this timesheet, click **New line**, and follow steps 4 through 9 in the first procedure in this topic, “Create a timesheet by using an empty timesheet form.”

7.  Click **Submit** to send the timesheet to the approval workflow.

### Create a timesheet based on favorites

1.  Depending on your version of the program, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R2: Click **Project management and accounting** \> **Common** \> **Timesheets** \> **My timesheets**.
    
      - Otherwise: **Home**\> **Common** \> **Timesheets** \> **My timesheets**.

2.  On the **All timesheets** list page, on the **Action Pane**, on the **Timesheets** tab, click **Create from favorites**.

3.  Confirm your selections, and then enter the number of hours that you worked each day. Enter hours in a decimal format. For example, if you worked for two hours and fifteen minutes, enter 2.25.

4.  Optionally, you can do the following:
    
      - To add information about taxes and financial dimension, click **Details**, and then enter information in the **Timesheet line details** form.
    
      - To add comments about the timesheet line, click **Comments**, and then enter comments for an internal audience, an external audience, or both. Internal comments can be viewed by project managers. External comments are included on invoices.
    
      - To save the line as a favorite, select the check box, and then click **Save as favorites**.

5.  If you want to add lines to this timesheet, click **New line**, and follow steps 4 through 9 in the first procedure in this topic, “Create a timesheet by using an empty timesheet form.”

6.  Click **Submit** to send the timesheet to the approval workflow.

## See also

[Authorize timesheet delegates](authorize-timesheet-delegates.md)

[Maintain timesheet favorites](maintain-timesheet-favorites.md)

[Modify or delete a timesheet (Project)](modify-or-delete-a-project-timesheet.md)

[About intercompany timesheets](about-intercompany-timesheets.md)

[New timesheet (form)](https://technet.microsoft.com/library/hh227610\(v=ax.60\))

[Timesheet favorites (form)](https://technet.microsoft.com/library/hh209717\(v=ax.60\))

[Timesheet line details (form)](https://technet.microsoft.com/library/hh209688\(v=ax.60\))

[Timesheet line comments (form)](https://technet.microsoft.com/library/hh208812\(v=ax.60\))

  


