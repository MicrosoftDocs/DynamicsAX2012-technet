---
title: Changing campaign activity data
TOCTitle: Changing campaign activity data
ms:assetid: bf333012-fd4c-482c-a77a-17467aa504da
ms:mtpsurl: https://technet.microsoft.com/library/Aa498993(v=AX.60)
ms:contentKeyID: 36059256
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Changing campaign activity data 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Changing data in the **Activity details** form that makes specific reference to campaigns does not affect the campaign on which the activity is based. However, changing the actual campaign generally does affect the associated activity.

If you create a campaign but do not specify the person who is responsible for the campaign, a follow-up activity is not created for the campaign, regardless of the value in the **Create activity** field on the **Activities** tab in the **Sales and marketing parameters** form.

If you specify the person who is responsible for the campaign later, the value in the **Create activity** field takes effect. Depending on the value in this field, an activity is automatically created, a dialog box prompts you to create an activity, or an activity is not created.

## Changing the campaign stage

If you change the stage of a campaign to **Closed** or **Canceled**, or if all campaign targets are in the **Response** stage, the follow-up activity for the campaign is automatically closed. But if some activities for the campaign targets have not been closed, because some of the campaign targets have not responded yet, you have the following options:

  - Close the campaign anyway. The follow-up activities that are connected to the campaign and the campaign targets are also closed.

  - Keep the campaign open. The activities for the campaign targets also remain open.

If you change a campaign that is in the **Closed** or **Canceled** stage to the **In process**, **Response**, or **Follow-up** stage, the follow-up activity for the campaign is reopened.

## Deleting the campaign

If you delete a campaign, the follow-up activity for the campaign is automatically deleted.

## Changing the follow-up date

If you change the follow-up date of a campaign, the start date of the follow-up activity for the campaign is also changed. The start date of any activities for the campaign targets is not changed.

## Changing the person who is responsible for the campaign

If you change the person who is responsible for a campaign to another worker, the newly assigned worker becomes responsible for the follow-up activity for the campaign.

If the follow-up activity for the campaign was previously synchronized with Microsoft Outlook, the follow-up activity is deleted. The synchronization log is set to delete the follow-up activity from Outlook during the next synchronization. A new follow-up activity for the campaign is then created for the new person who is responsible for the campaign.

If you delete the person who is responsible for a campaign, the follow-up activity for the campaign is deleted.

## No campaign targets

If there are no campaign targets, or if all campaign targets have been set to the **Response** stage, the follow-up activity for the campaign is closed.

  


