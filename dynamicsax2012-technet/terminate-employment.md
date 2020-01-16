---
title: Terminate employment
TOCTitle: Terminate employment
ms:assetid: 3571972e-5a4c-4192-b6e4-81e363929208
ms:mtpsurl: https://technet.microsoft.com/library/Aa570121(v=AX.60)
ms:contentKeyID: 36056562
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- employment
- terminate employment form
- termination
- terminations
audience: Application User
ms.search.region: Global
---

# Terminate employment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to terminate employment for a worker. When you terminate a worker’s employment, you end all position assignments and employment affiliations for the worker. To end only a position assignment, but not the employment affiliation for a worker, see [Key tasks: Workers](key-tasks-workers.md).

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker.

3.  On the **Action Pane**, on the **Worker** tab, in the **Personnel actions** group, click **Terminate**.

4.  If personnel actions are *not* enabled by your organization, specify the following information:
    
      - Enter the date and time when the termination is effective.
    
      - Enter the date and time of the worker’s last day of work.
    
      - Select a reason for the termination of employment. Resource codes for Human resources are maintained in the **Reason codes** form. (Click **Human resources** \> **Setup** \> **Parameters** \> **Reason codes**.)
    
      - To retire the position that is currently assigned to the worker, select the **Retire position** check box.
    
      - Click **Continue**. A confirmation message will appear.

5.  If personnel actions **are** enabled by your organization, specify the following information:
    
      - Enter the date and time when the termination is effective.
    
      - Enter the date and time of the worker’s last day of work.
    
      - Select a reason for the termination of employment. Resource codes for Human resources are maintained in the **Reason codes** form. (Click **Human resources** \> **Setup** \> **Parameters** \> **Reason codes**.)
    
      - If your organization has not set up personnel action number sequences, enter a unique personnel action number.
        

        > [!NOTE]
        > <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>

    
      - Select a personnel action type. The values for this field are entered in the **Personnel action types** form. Action types of **Modify positions** are displayed.
        

        > [!NOTE]
        > <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>

    
      - Click **Continue**. A confirmation message will appear.
    
      - Enter any additional information about the termination.
    
      - If your organization uses workflow for this kind of action, you must submit the change for approval before it is completed.
    
      - Click **Complete**.

## See also

[About workers](about-workers.md)

[About employment affiliations](about-employment-affiliations.md)

[Add or modify an employment affiliation](add-or-modify-an-employment-affiliation.md)

[Worker (form)](https://technet.microsoft.com/library/hh209054\(v=ax.60\))

  


