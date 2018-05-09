---
title: Set up sequencing parameters for a master plan
TOCTitle: Set up sequencing parameters for a master plan
ms:assetid: 5aa0629f-be35-49aa-ae41-1dbcb88a3773
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838736(v=AX.60)
ms:contentKeyID: 50120619
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up sequencing parameters for a master plan 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up the sequencing parameters for a master plan. You can set up the sequencing time fence, and then set up the sequencing campaign cycle parameters that specify the time period for the cycle. For example, you can specify 60 as the sequencing time fence, and then specify 30 days as the time period for the sequencing campaign cycle. In this scenario, the sequencing campaign cycle runs twice, as the sequencing time fence (60 days) is twice the time period for the sequencing campaign cycle (30 days).

1.  Click **Master planning** \> **Setup** \> **Plans** \> **Master plans**.

2.  Select or create a master plan. For more information, see [(PM) Master plans (form)](https://technet.microsoft.com/en-us/library/jj838759\(v=ax.60\)).

3.  Click the **Time fences** FastTab.

4.  Select the **Sequencing** check box to override the sequencing time fence for the item during master scheduling. If you select this check box, enter the number of days for which the batch orders are sequenced. You must enter a value that is equal to or smaller than the coverage time fence that you specified in the **Coverage** field on the **Time fences** FastTab.

5.  Click the **Sequencing** FastTab.

6.  Select the **Sequencing active** check box to generate sequencing when you use the master plan to regenerate master scheduling.

7.  In the **Bucket type** field, select one of the following options to indicate the period for which the sequencing campaign cycle is configured:
    
      - **Period** – Configure the sequencing campaign cycle starting from the current date. If you select this option, **Day** is updated in the **Period type** field and the **Period type** field is not available.
    
      - **Calendar** – Configure the sequencing campaign cycle for the period that you specify in the **Period type** field.

8.  In the **Period type** field, select **Day**, **Week**, **Month**, or **Quarter** as the type of time period for the sequencing campaign cycle.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Period</STRONG> in the <STRONG>Bucket type</STRONG> field.</P>



9.  In the **Sequencing bucket** field, enter the number of periods of the specified period type (**Day**, **Week**, **Month**, or **Quarter**) for the sequencing campaign cycle.

## See also

[About master scheduling plans](about-master-scheduling-plans.md)

[Run master scheduling](run-master-scheduling.md)

[Sequence planned batch orders](sequence-planned-batch-orders.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

