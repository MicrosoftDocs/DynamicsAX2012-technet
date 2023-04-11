---
title: Create activities automatically
TOCTitle: Create activities automatically
ms:assetid: 96c4a524-9fab-45c4-b901-8e2532032b1b
ms:mtpsurl: https://technet.microsoft.com/library/Aa498427(v=AX.60)
ms:contentKeyID: 36058642
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create activities automatically 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up Microsoft Dynamics AX to create an activity automatically when you create a sales quotation, campaign, campaign target, or telemarketing call list. You can also set up Microsoft Dynamics AX to create an activity automatically when the status of a target for a telemarketing call list is changed to **Call back**.

If you change a sales quotation, campaign, campaign target, or telemarketing call list, the changes appear in the existing activity records. However, changes to the activity do not affect the sales quotation, campaign, telemarketing call list, or any of the call list's targets.

The activities that you create appear in the **Activities** form. You can synchronize the activities to and from Microsoft Outlook if you have set up synchronization between Microsoft Dynamics AX and Microsoft Outlook.

1.  Click **Sales and marketing** \> **Setup** \> **Sales and marketing parameters**.

2.  On the **Activities** tab, in the **Create activity** field, select whether you want to create activities automatically.
    
    You can select one of the following options for creating an activity automatically:
    
      - **Yes** – An activity is created automatically when a sales quotation is created and a sales employee is defined.
    
      - **No** – An activity is not created for the specific action.
    
      - **Prompt** – A prompt appears, and you can choose to create an activity.
    
      - **Advanced prompt** – A prompt appears, and you can choose either to create an activity, or to create and modify an activity.

3.  In the **Category**, **Type**, and **Phase** fields, select default values for the follow-up activity.

4.  In the **Purpose** fields, enter a default description for each follow-up activity.

5.  Close the form to save your changes.

  


