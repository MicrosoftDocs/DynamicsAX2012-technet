---
title: Changing campaign target activity data
TOCTitle: Changing campaign target activity data
ms:assetid: 743d27a9-8d69-46ad-ad0a-1add1d1f8d95
ms:mtpsurl: https://technet.microsoft.com/library/Aa550019(v=AX.60)
ms:contentKeyID: 36058155
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Changing campaign target activity data 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can change the information in the **Activities** form so that it references specific campaign targets. These changes to an activity do not affect the campaign target on which the activity is based. However, in general, changes to the campaign target do affect the associated activity.

If you create a campaign target but do not specify a person who is responsible for it, an activity is not created for the campaign target. In this situation, the value of the **Create activity** field on the **Activities** tab of the **Sales and marketing parameters** form has no effect.

If you assign a person who is responsible for the campaign target later, the value of the **Create activity** field takes effect. Depending on the value of this field, an activity is created automatically, a dialog box prompts you to create an activity, or an activity is not created.

## Changing the campaign stage

If you select the **Responded** check box for a campaign target, the activity for the campaign target is closed. If you later clear the **Responded** check box, the activity is reopened.

## Deleting a campaign target

If you delete a campaign target, the activity for the campaign target is automatically deleted.

## Changing the follow-up date

If you change the follow-up date of a campaign, the start dates of the activities for the campaign targets are not changed.

## Changing the worker who is responsible for a campaign target

If you change the worker who is responsible for a campaign target, the activity for the campaign target is deleted. A new activity is created for the new worker who is responsible for the campaign target.

If you delete the worker who is responsible for a campaign target, the activity for the campaign target is deleted.

  


