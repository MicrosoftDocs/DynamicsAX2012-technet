---
title: Tips to help prevent long-running reports from timing out
TOCTitle: Tips to help prevent long-running reports from timing out
ms:assetid: 6f9481a2-9b56-4726-9eba-209e6d964ba9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ969577(v=AX.60)
ms:contentKeyID: 51554197
ms.date: 06/04/2014
mtps_version: v=AX.60
---

# Tips to help prevent long-running reports from timing out [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX uses Microsoft SQL Server Reporting Services to render reports. Reporting Services retrieves report data from the Microsoft Dynamics AX Application Object Server (AOS) by using a custom extension that uses Windows Communication Foundation (WCF) to communicate with the AOS.

The size of the data set and the complexity of the report that is rendered can affect the time that is required to display the report. Additionally, if various time-outs and other thresholds are reached, the report rendering may fail. This topic provides tips that can help you prevent reports that run for a long time from timing out.

## Use pre-processed RDP classes

If the report uses the Report Data Provider (RDP) to retrieve data, the report should be modified to use a pre-processed RDP class as the data source, so that processing logic is invoked before a call is made to Reporting Services. For more information about RDP classes, see [Using Report Data Provider Classes to Access Report Data](using-report-data-provider-classes-to-access-report-data.md) and [Report Programming Guide](report-programming-guide.md).

## Specify the report execution time-out period

Reporting Services has a *report execution time-out* period, which defines the number of seconds after which the reporting processing times out. The default value for this period is 30 minutes. If report execution requires more time, report execution fails.

You can specify the report execution time-out period for all reports by configuring the time-out settings at the level of the Reporting Services site. Alternatively, you can specify the report execution time-out period for a specific report.

## Specify the report execution time-out period for all reports

The report execution timeout period at the level of the Reporting Services site should be set to a value that is more than the time that is required to render your largest report. Alternatively, report execution can be set so that it never times out. You can specify the report execution time-out period in Report Manager or SQL Server Management Studio.

If you want to specify the report execution time-out period by using Report Manager, follow these steps.

1.  Open the Report Manager website for the Reporting Services instance. By default, the URL is http://\[SSRSServerName\]:80/Reports.

2.  Click **Site Settings**. The **Properties** page is displayed.

3.  In the **Report Timeout** section, specify a time-out period by entering the number of seconds. Alternatively, you can choose not to have a time-out period.

4.  Click **Apply** to save your changes.

If you want to specify the report execution time-out period by using SQL Server Management Studio, follow these steps.

1.  Open SQL Server Management Studio, and connect to your Reporting Services instance.

2.  In the **Object Explorer** pane, right-click the name of your report server, and then select **Properties**. The **Server Properties** window is displayed.

3.  In the **Select a page** area, click **Execution**.

4.  Specify a time-out period by entering the number of seconds. Alternatively, you can choose not to have a time-out period.

5.  Click **OK** to save your changes.

## Specify the report execution time-out period for a specific report

To specify the report execution time-out period for a specific report, follow these steps.

1.  Open the Report Manager website for the Reporting Services instance. By default, the URL is http://\[SSRSServerName\]:80/Reports.

2.  Click the **DynamicsAX** folder. The Microsoft Dynamics AX reports are listed.

3.  Hover over a specific report, click the drop-down arrow, and then click **Manage**. The properties page is displayed.

4.  Click the **Processing Options** tab.

5.  In the **Report Timeout** section, specify a time-out period by entering the number of seconds. Alternatively, you can choose not to have a time-out period.

6.  Click **Apply** to save your changes.

## Specify the user session time-out period

Reporting Services maintains a user session, which may time out if report execution requires a long time. If the user session times out, the report rendering fails. You can resolve this issue by configuring two properties, **SessionTimeout** and **SessionAccessTimeout**, by using the rs.exe tool. These properties should be set to a value that is more than the time that is required to render your largest report.

On the Reporting Services server, follow these steps to configure the **SessionTimeout** and **SessionAccessTimeout** properties.


> [!WARNING]
> <P>Keeping a user session around longer than necessary can cause your ReportServerTempDB database to grow larger because temporary session snapshots will not be aged out as often.</P>



1.  Create a SessionTimeout.rss file by following these steps:
    
    1.  Open Notepad.
    
    2.  Copy the following code into Notepad.
        
            Public Sub Main()
                Dim props() as [Property]
                props = new [Property] () { new [Property](), new [Property]() }
                
                props(0).Name = "SessionTimeout"
                props(0).Value = timeout
                
                props(1).Name = "SessionAccessTimeout"
                props(1).Value = timeout
                
                rs.SetSystemProperties(props)
            End Sub
    
    3.  Save the file to the local hard drive as **SessionTimout.rss**.

2.  Open a Command Prompt window.

3.  Run the script that you created in step 1 by entering the following command. Keep the following points in mind:
    
      - By default, the URL of the report server is http://\[SSRSServerName\]:80/ReportServer.
    
      - The timeout value is expressed in seconds. In the example below, the **SessionTimeout** and **SessionAccessTimeout** properties are set to 20 hours.
    
    <!-- end list -->
    
        $>rs.exe -i <Path to SessionTimeout.rss file> -s <Report Server URL> -v timeout="72000" –l 0
    
    By default, the rs.exe tool is located at \\Program Files\\Microsoft SQL Server\\110\\Tools\\Binn. For more information about how to use this tool, see the [rs Utility (rs.exe)](http://technet.microsoft.com/en-us/library/ms162839.aspx) topic in the SQL Server documentation and the [Session Timeout during execution](http://blogs.msdn.com/b/jgalla/archive/2006/10/11/session-timeout-during-execution.aspx) blog post.

## Specify WCF time-outs and thresholds

Reporting Services uses the Microsoft Dynamics AX query service to retrieve data. The Microsoft Dynamics AX query service is a WCF service that is exposed by the AOS. For reports that have large data sets, the default WCF configuration may cause WCF to reach some time-outs and thresholds at run time. To help prevent this issue, you can modify the WCF configuration in the following ways.

## Configure the server-side settings

Follow these steps to configure server-side WCF settings. Complete these steps on the AOS server.

1.  Open the Ax32Serv.exe.config file. This file is typically located at \\Program Files\\Microsoft Dynamics AX\\\<version\>\\Server\\MicrosoftDynamicsAX\\Bin.

2.  Find the **QueryServiceBinding** element.
    
        </system.diagnostics>
          <system.serviceModel>
            <bindings>
              <netTcpBinding>
                <binding name="QueryServiceBinding" sendTimeout="00:10:00" transferMode="StreamedResponse" maxBufferSize="65536" maxReceivedMessageSize="104857600" listenBacklog="200" maxConnections="200">
                  <readerQuotas maxStringContentLength="104857600" />
                </binding>

3.  The default value for the **sendTimeout** property on this element is 10 minutes. Increase the value for the **sendTimeout** property. For example, set the value to 30 minutes.

4.  Save your changes.

## Configure the client-side settings

Reporting Services communicates with the AOS to retrieve data. In this communication process, Reporting Services acts as the client, and the AOS acts as the server. Therefore, to configure client-side WCF settings, you must follow these steps on the server where Reporting Services is installed.

1.  Create a new, local client configuration as explained in [Manage a client configuration](manage-a-client-configuration.md).

2.  While the configuration utility is still open, click the **Connection** tab.

3.  Click the **Configure Services** button.

4.  A message is displayed that indicates that the configuration will no longer be updated automatically after a change is made to the server. Click **OK**.

5.  A message may be displayed that indicates that you have to install the Windows SDK for Windows Server and the Microsoft .NET Framework version 4.0. In this case, download and install the Windows SDK for Windows Server and the .NET Framework version 4.0.
    
    After you install the Windows SDK, connect to the client configuration that you created in step 1. Then repeat steps 2 and 3 to open the Microsoft Service Configuration Editor.

6.  In the **Configuration** area, click **Bindings** \> **QueryServiceEndpoint (netTcpBinding)**.

7.  On the **Bindings** tab, modify the following properties:
    
      - **SendTimeout** – By default, this property is set to 10 minutes. Increase the value. For example, set the value to 30 minutes.
    
      - **MaxReceivedMessageSize** – By default, this property is set to 2147483647. Increase the value. For example, if you want to double the value, set it to 4294967294. The maximum value that is allowed is Int64.MaxValue.

8.  Click **File** \> **Save**.

## Use batch processing

To improve performance when you print statements or reports that include large amounts of data, use batch processing. When you use batch processing, you can run specific tasks as batch jobs, and then schedule those batch jobs to be run on a different computer (a batch server). When you move the processing of these tasks to a batch server, the report performance on the client computer can improve. You can also apply range restrictions to limit the size of each batch. You can improve performance by submitting multiple, smaller batches to be processed at the same time on different servers, instead of submitting one large batch.

Many tasks in Microsoft Dynamics AX can be run as part of batch jobs. For more information, see [Batch processing overview](batch-processing-overview.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

