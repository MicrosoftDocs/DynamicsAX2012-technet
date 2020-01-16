---
title: Review and approve timesheets (Enterprise Portal)
TOCTitle: Review and approve timesheets
ms:assetid: 8252d9b6-4576-4b29-a552-2e5ac07241f0
ms:mtpsurl: https://technet.microsoft.com/library/Hh271583(v=AX.60)
ms:contentKeyID: 36384214
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- approve timesheet
- review timesheet
- timesheet
- TSTimesheetSignOff
audience: Application User
ms.search.region: Global
---

# Review and approve timesheets (Enterprise Portal) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **My approvals** page to review timesheets that have been submitted for projects.


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



1.  Click **Approvals** on the top link bar.

2.  On the **My approvals** page, select a timesheet, click **Actions**, and then click one of the following options:
    
      - **Preview** – Open the **Preview** dialog box to view a summary of the timesheet information. You can approve the timesheet in the preview.
    
      - **Approve** – Approve the timesheet. Depending on your version of the product, one of the following things happens:
        
          - Microsoft Dynamics AX 2012: If this is the last step in the timesheet workflow, an hour journal is automatically created for the timesheet. If you have not configured Microsoft Dynamics AX to post timesheets automatically after they have been approved, you can a view and post the hour journals in the **Hour journal** form in the Microsoft Dynamics AX client.
        
          - Microsoft Dynamics AX 2012 Feature Pack or Microsoft Dynamics AX 2012 R2: If this is the last step in the timesheet workflow, a subledger journal is automatically created for the timesheet. If you have not configured Microsoft Dynamics AX to post timesheets automatically after they have been approved, you can a view timesheets that have not been posted yet on the **Unposted timesheets** list page in the Microsoft Dynamics AX client.
    
      - **Return** – Open the **Timesheet doc level workflow – Return** dialog box, enter comments, and return the timesheet to the worker who entered it.
    
      - **Delegate** – Open the **Timesheet doc level workflow – Delegate** dialog box to assign the approval permission for the timesheet to another worker.
    
      - **Recall** – Permanently stop a timesheet workflow. After you recall a workflow, the system no longer recognizes that the timesheet was ever submitted to workflow.
    
      - **View history** – Open the **Workflow history details** page to view detailed information about each stage of the workflow for a timesheet.
    
      - **Mark as read** – Mark the timesheet to indicate that it has been read.
    
      - **Open Timesheet** – Open the **Timesheet approval** page to review the timesheet details and any comments that have been entered. When you are satisfied, approve the timesheet on the **My approvals** page.

## See also

[Create and submit timesheets](create-and-submit-timesheets.md)

  


