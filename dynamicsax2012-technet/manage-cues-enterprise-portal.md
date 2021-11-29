---
title: Manage cues (Enterprise Portal)
TOCTitle: Manage cues
ms:assetid: d9bcbb13-fb60-44e5-9948-4122af5a6240
ms:mtpsurl: https://technet.microsoft.com/library/Hh227402(v=AX.60)
ms:contentKeyID: 36059656
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Manage cues (Enterprise Portal) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A cue is a filtered view of a list that has been saved. You can create your own cues in the Microsoft Dynamics AX client by creating an advanced filter and then click the **Save as cue** button. You can also click the **Save as cue** button from any list page in the Microsoft Dynamics AX client. If you double-click a cue on your Role Center page in the Microsoft Dynamics AX client, the associated page opens and the filtered view is displayed. If you click a cue on your Role Center page in Enterprise Portal for Microsoft Dynamics AX, the associated page opens, but the filtered view is not displayed.

This topic provides information about how to add and modify cues on your Role Center page. For information about how to create cues from a list page or how to import and export a cue, see [Manage Cues on Role Center pages](manage-cues-on-role-center-pages.md).


> [!NOTE]
> <P>If you change a cue, you must refresh the data on your Role Center by clicking <STRONG>Home</STRONG> on the top link bar.</P>



## Add a Cues Web part

1.  Click **\<User name\>** \> **Personalize this Page**.

2.  Click the **Add a Web Part** link in the location where you want to add the Cues Web part.

3.  In the **Categories** section, select **Microsoft Dynamics AX**.

4.  In the **Web Parts** section, click **Cues**, and then click **Add**.

5.  In the Cues Web part, click **Add Cue**.

6.  In the **Cue to add** list, select a Cue.

7.  Click **OK**.

## Modify the display properties for a cue

You can modify the display properties for a cue. Display properties include the caption, and the minimum and maximum number of items that are displayed for the cue.

1.  In the Cues Web part, click **Manage Cues**.

2.  Click the cue that you want to modify, and then click the pencil icon to modify the cue's properties. Depending on the type of cue, you can make the following changes:
    
    1.  Enter the name that is displayed for the cue in the Web part.
    
    2.  Enter the minimum number of items that can be displayed for the cue. If this minimum is not reached, the cue is displayed as having no items.
    
    3.  Enter the maximum number of items that can be displayed for the cue. If this maximum is exceeded, the cue displays only the maximum number of items.
    
    4.  Specify the threshold for the cue. If the criteria that you specify are not met, a warning icon is displayed for the cue.
    
    5.  For cues that display currency information, select the type of total amounts that are displayed for combined records in the cue:
        
          - **None** – No total is displayed.
        
          - **Sum** – The total sum of all record values is displayed.
        
          - **Avg** – The average value of the records is displayed.
        
          - **Min** – The lowest value of the records is displayed.
        
          - **Max** – The highest value of the records is displayed.
        
        You also select the table that is used when the totals are calculated.
    
    6.  Click **OK**.

3.  Click **OK**.

## See also

[About list filters](about-list-filters.md)

[Modify Role center pages (Enterprise Portal)](modify-role-center-pages-enterprise-portal.md)

[Role Centers (Enterprise Portal)](role-centers-enterprise-portal.md)

  


