---
title: Set up tracing for master plans
TOCTitle: Set up tracing for master plans
ms:assetid: eec2762d-98ff-46d8-9bb3-a126bc52e96e
ms:mtpsurl: https://technet.microsoft.com/library/JJ677371(v=AX.60)
ms:contentKeyID: 49384147
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up tracing for master plans 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use event trace data to view details about the outcome of a master planning run. However, you must first set up a Data Collector Set in Windows Performance Monitor to collect event trace data. Then, when you run master planning and want to analyze the run, you can view information about the run in an .etl log file in Event Viewer in Windows. You can also view information about planned orders.

The following procedure describes how to set up a Data Collector Set to collect event trace data for master planning.

1.  From the **Start** menu, open Performance Monitor.

2.  In the tree, expand the **Data Collector Sets** node.

3.  Right-click **User Defined Node**, point to **New**, and then click **Data Collector Set**.

4.  In the **Create new Data Collector Set** wizard, in the **Name** field, enter a name for the Data Collector Set. Select the **Create manually (Advanced)** option, and then click **Next**.

5.  Verify that the **Create data logs** option is selected. Select the **Event trace data** check box, and then click **Next**.

6.  Click **Add** to specify the providers to enable. In the **Event Trace Providers** list, select the **Microsoft-Dynamics AX-Tracing** provider, and then click **OK**.

7.  In the **Create new Data Collector Set** wizard, in the **Properties** table, select the **Keywords (Any)** property. Click **Edit**, and then, in the **Property** dialog box, select the **MRP** option. Click **OK**.

8.  In the **Create new Data Collector Set** wizard, click **Next**.

9.  In the **Root directory** field, enter a location for the log file, and then click **Next**.

10. Verify that the **Save and close** option is selected, and then click **Finish**.

11. In **Performance Monitor**, right-click the Data Collector Set and select **Start**.

## See also

[About using tracing for master plans](about-using-tracing-for-master-plans.md)

  


