---
title: Transfer work breakdown estimates to project forecasts
TOCTitle: Transfer work breakdown estimates to project forecasts
ms:assetid: 0b03c599-ddc1-4159-a4b7-237a54b513ed
ms:mtpsurl: https://technet.microsoft.com/library/Dn631647(v=AX.60)
ms:contentKeyID: 62200033
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.ProjForecastTransferFromWbs
audience: Application User
ms.search.region: Global
---

# Transfer work breakdown estimates to project forecasts 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to create item requirements that derive from product or category estimates in a work breakdown structure (WBS) in AX 2012 R3. These product estimates can be for items, services, or category purchases.

When you create item requirements for projects by using the procedures in this topic, the requested receipt date of the items in the requirements is set to be the same as the start date of the related activity. For example, if a project activity is created for the task of hanging drywall, the requested receipt date for the required items is the same as the scheduled start of the activity. This ensures that the drywall is delivered to the work site on the date that the workers need to install it.


> [!NOTE]
> <P>If you don’t want to set the receipt date of the items in the requirement to match the start date of a related activity, you can change the value in the <STRONG>Delivery date control</STRONG> field in the <STRONG>Item requirements</STRONG> form.</P>



The steps that you follow to transfer WBS estimates to item requirements depend on where you begin the process. You can begin the transfer directly from a list of all item requirements, or you can begin from a work breakdown structure or project.

### Transfer WBS estimates to project forecasts directly from item requirements

1.  Click **Project management and accounting** \> **Common** \> **Item tasks** \> **Item requirements**. In the menu bar, click **Transfer WBS item estimates**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a project, and then, on the **Action Pane**, on the **Plan** tab, in the **Item requirements** group, click **Transfer from WBS estimates**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. On the **Action Pane**, on the **Maintain** tab, in the **Related information** group, click **Item tasks**, and then click **Item requirements**. In the **Item requirements** form, in the menu bar, click **Transfer WBS item estimates**.

2.  In the **Transfer WBS item estimates** form, in the **Activity number** filter, select the activity that you want to view item estimates for, or select **All** to view estimates for all activities.
    
    You can select an activity either from a list of all activities or from a tree view that groups activities according to their types.

3.  Select the check box of each item estimate that you want to transfer.
    

    > [!TIP]
    > <P>To sort the results, click the name of a column header in the results list, such as <STRONG>Item number</STRONG>.</P>



4.  Click **OK**.

### Transfer WBS estimates to project forecasts from a WBS or project

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a project, and then, on the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Work breakdown structure**. In the **Work breakdown structure** form, on the **Action Pane**, on the **WBS** tab, click **Transfer WBS estimates to forecasts**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a project, and then, on the **Action Pane**, on the **Plan** tab, in the **Maintain forecast** group, click **Transfer from WBS**.

2.  In the **Transfer WBS estimates** form, in the **Transaction type** filter, select the type of transaction that you want to transfer, or select **All** to view estimates of all types.

3.  In the list of estimates, select the check box of each estimate that you want to convert to an item requirement in a forecast.
    

    > [!TIP]
    > <P>To sort the results, click the name of a column header in the results list, such as <STRONG>Activity number</STRONG>.</P>



4.  In the **Forecast model** list, select the name of the forecast that you want to transfer estimates to.

5.  If you want to the estimates to transfer to project forecasts as a batch job, select the **Batch processing** check box.

6.  Click **OK**.

## See also

[About work breakdown structures](about-work-breakdown-structures.md)

[Create a work breakdown structure of tasks for a project](create-a-work-breakdown-structure-of-tasks-for-a-project.md)

[About project forecasts](about-project-forecasts.md)

[Manage project forecasts](manage-project-forecasts.md)

  


