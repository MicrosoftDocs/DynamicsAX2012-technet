---
title: Review and approve timesheets
TOCTitle: Review and approve timesheets
ms:assetid: 3708cbc7-c85c-4e55-b330-bcef74529caa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242200(v=AX.60)
ms:contentKeyID: 36056600
ms.date: 07/21/2014
mtps_version: v=AX.60
f1_keywords:
- approve timesheet
- review timesheet
- timesheet
---

# Review and approve timesheets [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how project managers who have timesheet approval rights can review and approve timesheets in either the **Timesheet approval** form or the **Timesheet** form.

Depending on your version of Microsoft Dynamics AX, complete one of the following procedures.

### Review and approve timesheets in AX 2012

1.  **Home** \> **Common** \> **Timesheets** \> **Timesheets for my review**.

2.  On the **Timesheets for my review** list page, open a timesheet.
    

    > [!TIP]
    > <P>If you do not want to review the details of a timesheet, you can approve or reject it on the <STRONG>Timesheets for my review</STRONG> list page.</P>



3.  In the **Timesheet approval** form, review the worker’s timesheet entries.
    
    To view additional details about a line item, click the **Details** button. To view comments that were entered for a line item, click the **Comments** button.

4.  In the workflow message bar, click **Actions**, and then click one of the following options:
    
      - **Approve** – Approve the timesheet.
        
        If this is the last step in the timesheet workflow, an hour journal is automatically created for the timesheet. If you have not configured Microsoft Dynamics AX to post timesheets automatically after they have been approved, you can a view and post the hour journals in the **Hour journal** form.
    
      - **Return** – Open the **Return** dialog box, enter comments, and return the timesheet to the worker who entered it.
    
      - **Delegate** – Open the **Delegate** dialog box to assign permission to approve the timesheet to another worker.
    
      - **Recall** – Permanently stop a timesheet workflow. After you recall a timesheet, the system no longer recognizes that it was ever submitted to workflow.
    
      - **View history** – Open the **Workflow history** form to view detailed information about each stage of the workflow for a timesheet.

### Review and approve timesheets in AX 2012 Feature Pack

1.  **Home** \> **Common** \> **Timesheets** \> **Timesheets for my review**.

2.  On the **Timesheets for my review** list page, open a timesheet.
    

    > [!TIP]
    > <P>If you do not want to review the details of a timesheet, you can approve or reject it on the <STRONG>Timesheets for my review</STRONG> list page.</P>



3.  In the **Timesheet approval** form, review the worker’s timesheet entries.
    
    To view additional details about a line item, click the **Details** button. To view comments that were entered for a line item, click the **Comments** button.

4.  In the workflow message bar, click **Actions**, and then click one of the following options:
    
      - **Approve** – Approve the timesheet.
        
        If this is the last step in the timesheet workflow, a subledger journal is automatically created for the timesheet. If you have not configured Microsoft Dynamics AX to post timesheets automatically after they have been approved, you can a view timesheets that have not been posted yet on the **Unposted timesheets** list page. (**Home** \> **Common** \> **Timesheets** \> **Unposted timesheets**.)
    
      - **Return** – Open the **Return** dialog box, enter comments, and return the timesheet to the worker who entered it.
    
      - **Delegate** – Open the **Delegate** dialog box to assign permission to approve the timesheet to another worker.
    
      - **Recall** – Permanently stop a timesheet workflow. After you recall a timesheet, the system no longer recognizes that it was ever submitted to workflow.
    
      - **View history** – Open the **Workflow history** form to view detailed information about each stage of the workflow for a timesheet.

### Review and approve timesheets in AX 2012 R2 and AX 2012 R3

1.  Click **Project management and accounting** \> **Common** \> **Timesheets** \> **Timesheets for my review**.

2.  On the **Timesheets for my review** list page, open a timesheet.
    

    > [!TIP]
    > <P>If you do not want to review the details of a timesheet, you can approve or reject it on the <STRONG>Timesheets for my review</STRONG> list page.</P>



3.  In the **Timesheet approval** form, review the worker’s timesheet entries.
    
    To view additional details about a line item, click the **Details** button. To view comments that were entered for a line item, click the **Comments** button.

4.  In the workflow message bar, click **Actions**, and then click one of the following options:
    
      - **Approve** – Approve the timesheet.
        
        If this is the last step in the timesheet workflow, a subledger journal is automatically created for the timesheet. If you have not configured Microsoft Dynamics AX to post timesheets automatically after they have been approved, you can a view timesheets that have not been posted yet on the **Unposted timesheets** list page. (Click **Project management and accounting** \> **Common** \> **Timesheets** \> **Unposted timesheets**.) On the **Unposted timesheets** list page, you can view timesheet accounting distributions, modify timesheet line details, and manually post timesheet hours. For more information, see [Preview, update and manually post approved timesheets](post-timesheet-hours-and-view-distributions.md).
    
      - **Return** – Open the **Return** dialog box, enter comments, and return the timesheet to the worker who entered it.
    
      - **Delegate** – Open the **Delegate** dialog box to assign permission to approve the timesheet to another worker.
    
      - **Recall** – Permanently stop a timesheet workflow. After you recall a timesheet, the system no longer recognizes that it was ever submitted to workflow.
    
      - **View history** – Open the **Workflow history** form to view detailed information about each stage of the workflow for a timesheet.

## See also

[Preview, update and manually post approved timesheets](post-timesheet-hours-and-view-distributions.md)

[New timesheet (form)](https://technet.microsoft.com/en-us/library/hh227610\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

