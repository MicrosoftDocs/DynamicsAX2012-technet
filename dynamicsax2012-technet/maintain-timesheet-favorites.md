---
title: Maintain timesheet favorites
TOCTitle: Maintain timesheet favorites
ms:assetid: 8815a0ad-49fc-4277-81a1-fae9f2e56990
ms:mtpsurl: https://technet.microsoft.com/library/Hh209334(v=AX.60)
ms:contentKeyID: 36058440
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- timesheet
- favorites
audience: Application User
ms.search.region: Global
---

# Maintain timesheet favorites 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use timesheet favorites to save a template of the projects, categories, and activities that you use frequently. Then you can use these entries when you create a new timesheet. You do not have to enter the same information about projects and activities for every new timesheet.

Managers can set up favorites and then assign them to workers or groups of workers. Workers can set up their own timesheet entries as favorites.


> [!NOTE]
> <P>When you create a new timesheet by using favorites, all timesheet favorites are entered in the new timesheet. This is true whether the favorites were created by a manager in the <STRONG>Timesheet favorites</STRONG> form or by a worker in the <STRONG>My favorites</STRONG> form.</P>



### Maintain timesheet favorites for multiple workers

1.  Click **Project management and accounting** \> **Setup** \> **Timesheets** \> **Favorites**.

2.  In the **Timesheet favorites** form, click **New**.

3.  In the **Valid for** field, do one of the following:
    
      - Select **Table** to associate the favorite with a worker.
    
      - Select **Group** to associate the favorite with a worker group.
    
      - Select **All** to associate the favorite with all workers.

4.  Do one of the following:
    
      - If you selected **Group** in the **Worker/project** field, in the **Worker/project** field, select a worker group.
    
      - If you selected **Table** in the **Worker/project** field, in the **Worker** field, select the worker’s ID.

5.  In the **Legal entity** field, select the legal entity for which the project work is performed.
    

    > [!NOTE]
    > <P>The <STRONG>Legal entity</STRONG> field is available only if intercompany timesheet support has been enabled for your legal entity.</P>



6.  In the **Project ID** field, select a project to associate with the favorite.

7.  Optional: In the **Activity number** field, select an activity for the favorite.

8.  In the **Category** field, select a category to associate with the favorite.

9.  Optional: In the **Note** field, enter comments about the favorite.

### Maintain your individual timesheet favorites

1.  Depending on your version of the program, do one of the following:
    
      - If you are using Microsoft Dynamics AX 2012 R2: Click **Project management and accounting** \> **Common** \> **Timesheets** \> **My timesheets**.
    
      - Otherwise, **Home**\> **Common** \> **Timesheets** \> **All timesheets**.

2.  On the **Action Pane**, in the **Maintain** group, click **My favorites**.

3.  In the **My favorites** form, click **New**.

4.  In the **Legal entity** field, select the legal entity for which the project work is performed.
    

    > [!NOTE]
    > <P>The <STRONG>Legal entity</STRONG> field is available only if intercompany timesheet support has been enabled for your legal entity.</P>



5.  In the **Project ID** field, select a project to associate with the favorite.

6.  Optional: In the **Activity number** field, select an activity.

7.  In the **Category** field, select a category to associate with the favorite.

8.  Optional: In the **Notes** field, enter comments about the favorite.

For information about how to create favorites in a timesheet form, see [Create a timesheet](create-a-timesheet.md).

## See also

[Create a timesheet](create-a-timesheet.md)

[Create and generate timesheet periods](create-and-generate-timesheet-periods.md)

[Authorize timesheet delegates](authorize-timesheet-delegates.md)

  


