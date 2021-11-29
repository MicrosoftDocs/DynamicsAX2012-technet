---
title: 'How to: Configure the Debugger to Debug a Report Data Provider Class'
TOCTitle: 'How to: Configure the Debugger to Debug a Report Data Provider Class'
ms:assetid: a23beaa6-82b8-43e3-be02-958141b5c4f0
ms:mtpsurl: https://technet.microsoft.com/library/Gg724081(v=AX.60)
ms:contentKeyID: 35133438
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# How to: Configure the Debugger to Debug a Report Data Provider Class 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides steps to configure the debugger before you debug a report data provider (RDP) class. This scenario requires special setup because it involves X++ code and code that is managed by the .NET Framework.

By using the Visual Studio reporting tools for Microsoft Dynamics AX, you can bind a report to an X++ RDP class. This allows you to process data using X++ business logic that executes on the Application Object Server (AOS). X++ code is debugged using the MorphX debugger. The RDP class is called with a service that is compiled into Microsoft Intermediate Language (MSIL). MSIL is debugged and managed by the .NET Framework.

The debug process must occur in X++ code and managed code because of the following two conditions:

1.  The X++ code, that is not managed, runs on the AOS.

2.  The X++ code is called using a service and the service is compiled into MSIL.

These steps apply to debug a Microsoft Dynamics AX report executing in the following environments:

  - Visual Studio

  - SQL Server Reporting Services (SSRS) Report Manager

  - Microsoft Dynamics AX client

For more information on debugging, see [Microsoft Dynamics AX Debugger](https://technet.microsoft.com/library/aa569668\(v=ax.60\)). For information on when and how to use an RDP class, see [Defining Report Data](defining-report-data.md).

In the following sections, you determine which AOS service account to debug the RDP class in and add the account to the **Microsoft Dynamics AX Debugging Users** group. You create a server configuration with debug enabled and then you can add breakpoints in your code.

### To determine the AOS service account

1.  From the **Start menu**, point to **All Programs**, click **Administrative Tools**, and then click **Services**.

2.  In **Services**, right-click the **Microsoft Dynamics AX Object Server** service and then click **Properties**.

3.  In the Properties window, on the **Log On** tab, the AOS service account is specified in the **This account** field.

### To add the AOS service account to the debug group

1.  From the **Start menu**, point to **All Programs**, click **Administrative Tools**, click **Computer Management**, and then click **Local Users and Groups**.

2.  In Local Users and Groups, double-click **Groups**, right-click **Microsoft Dynamics AX Debugging Users** and click **Add to Group**.

3.  In the Properties window, click **Add** and add the AOS service account to the group.

4.  Restart the machine.

### To configure for debugging

1.  From the **Start menu**, point to **Administrative Tools** and then click **Microsoft Dynamics AX Server Configuration**.

2.  In Microsoft Dynamics AX Server Configuration Utility, click the **Manage** button, and then click **Create configuration**.

3.  In the Create Configuration window, enter a **Configuration name** like Debug and then click **OK**.

4.  On the **Application Object Server** tab, select **Enable breakpoints to debug X++ code running on this server** and **Enable global breakpoints to debug X++ code running in batch jobs**.

5.  Click **OK** and when prompted to restart the AOS service click **Yes**.

6.  From the **Start menu**, point to **All Programs**, click the **Microsoft Dynamics AX** folder, and then click the **Microsoft Dynamics AX Debugger**.

7.  From the Microsoft Dynamics AX Development Workspace, from the **Tools** menu, click **Options**. On the **Development** tab, click the **Debug mode** dropdown, and then select **When Breakpoint**.

### To add a breakpoint

  - In Code Editor, in the processReport method of the RDP class to debug, add the breakpoint; keyword.


> [!NOTE]
> <P>To stop at the breakpoint you set, AX Debugger must be running when you run the report.</P>



## See also

[Allow debugging](allow-debugging.md)

