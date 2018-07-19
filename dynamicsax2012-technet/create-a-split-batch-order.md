---
title: Create a split batch order
TOCTitle: Create a split batch order
ms:assetid: 1c3d88ad-94e1-44cb-b96f-20d871f9c7a5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352187(v=AX.60)
ms:contentKeyID: 36687820
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a split batch order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create a batch order by using the split function.

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  Double-click the batch order to be split. The **Batch order** form is displayed.
    

    > [!NOTE]
    > <P>You can split a batch only if the status is <STRONG>Created</STRONG>, <STRONG>Estimated</STRONG>, <STRONG>Scheduled</STRONG>, or <STRONG>Released</STRONG>. The maximum quantity that you can split is that quantity that has not yet started production.</P>



3.  On the **Action Pane**, on the **Production order** tab, in the **Maintain** group, click **Split**.

4.  In the **Split quantity** field, enter the quantity to be split to create this batch order.

5.  If the ship date differs from the current date, select the date in the **Ship date** field. This date can be different from the ship date for the original batch order.

6.  Optionally, enter any remaining information or change default values as necessary for the particular production.

7.  Click **OK**. The **Batch order** form is redisplayed and the new batch order appears in the list.

## See also

[About batch orders](about-batch-orders.md)

[Batch order (form)](https://technet.microsoft.com/en-us/library/hh352323\(v=ax.60\))

[Split (form)](https://technet.microsoft.com/en-us/library/aa588617\(v=ax.60\))

  


