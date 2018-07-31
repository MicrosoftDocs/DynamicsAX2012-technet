---
title: Changing telemarketing activity data
TOCTitle: Changing telemarketing activity data
ms:assetid: ecb04e11-c390-4e92-9379-4e1a412c389f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551529(v=AX.60)
ms:contentKeyID: 36059895
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Changing telemarketing activity data 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Be careful when you change telemarketing data, because your changes can affect the data for the related telemarketing activities. This topic describes the changes that you can make to telemarketing data, and how those changes affect the data for the telemarketing activities.

## Telemarketing targets

If you do not assign a target for the telemarketing call list to a worker, a target activity is not created for the telemarketing call list.

If you assign a worker later, a new target activity is created for the telemarketing call list. The new target activity uses the parameters for the automatic creation of telemarketing activities.

## Changes to the targets of a telemarketing call list

  - Delete a target of the telemarketing call list – If you delete a target of the telemarketing call list, the attached target activity is also deleted.

  - Change the planned date – If you change the planned date, the start date of the target activity for the telemarketing call list is updated.
    
      - If you delete the planned date, and a target activity exists for the telemarketing call list, you are prompted to confirm that you want to delete the activity.
    
      - If you enter a new planned date after you delete the previous planned date and target activity for the telemarketing call list, a new target activity is created. The new target activity uses the parameters for the automatic creation of telemarketing activities.
    
      - If you enter a new planned date after you delete the previous planned date, but you did not delete the target activity for the telemarketing call list, the original target activity is updated. The target activity now uses the parameters for the automatic creation of telemarketing activities.

  - Change the worker who is responsible for the telemarketing call list – If you change the worker who is responsible for the telemarketing call list, the target activity for the telemarketing call list is updated so that is reflects the new worker.
    
      - If the target activity for the telemarketing call list was previously synchronized with Microsoft Outlook, the activity is deleted. The synchronization log is set to delete the target activity from Microsoft Outlook when the next synchronization occurs. A new target activity is created for the new worker.
    
      - If you remove the worker, the target activity is deleted.
    
      - If you enter a new worker after you delete the previous worker, a new target activity is created. The new target activity uses the parameters for the automatic creation of telemarketing activities.

  - If the follow-up activity for the telemarketing call list was previously synchronized with Microsoft Outlook, the activity is deleted. The synchronization log is set to delete the follow-up activity from Microsoft Outlook when the next synchronization occurs. A new follow-up activity is created for the new worker.

  - If you delete the worker who is responsible for the telemarketing call list, the follow-up activity is also deleted.

## Telemarketing callback activity

If you set the target of the call list to **Closed** or **Canceled**, the telemarketing callback activity is closed. If you reopen the call list later, the callback activity is reopened if it still exists.

## Telemarketing call list

If you create a telemarketing call list, but you do not assign a responsible worker, a telemarketing follow-up activity is not created, regardless of the value in the **Create an activity for telemarketing follow-up.** field.

If you add a responsible worker to the telemarketing call list later, the value in the **Create activity** field under **Telemarketing default activity** on the **Activities** FastTab of the **Sales and marketing parameters** form takes effect. If an activity is created, a message confirms that it was created.

  - Delete the telemarketing call list – If you delete the telemarketing call list, the follow-up activity for the telemarketing call list is also deleted.

  - Change the end date – If you change the end date of the telemarketing call list, the date of the target activities for the telemarketing call list is not changed.

  - Change the worker who is responsible for the telemarketing call list – If you change the worker who is responsible for the telemarketing call list, the follow-up activity for the telemarketing call list is updated so that it reflects the new worker.

## Changes to activity data

Changes that you make to the data for the activity for a telemarketing call list do not affect the target of the telemarketing call list on which it is based.

  


