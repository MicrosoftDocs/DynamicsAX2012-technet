---
title: Tips to improve Enterprise Portal and Role Center performance
TOCTitle: Tips to improve Enterprise Portal and Role Center performance
ms:assetid: 9706f027-2356-4f1e-817d-030421234f3d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677308(v=AX.60)
ms:contentKeyID: 49384079
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Tips to improve Enterprise Portal and Role Center performance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

There are several factors that can cause poor performance for Enterprise Portal and Role Center pages. Some of these factors include memory leaks in custom code, insufficient memory on the server, and network latency. Enterprise Portal performance is also directly affected by the performance of Internet Information Services (IIS) and SharePoint. Before you attempt to configure features or settings that might improve Enterprise Portal performance, we recommend that you read about how to improve IIS and SharePoint performance on Microsoft TechNet. We also recommend that you use performance-monitoring tools to eliminate hardware or other components as the source of the problem. For more information, see [Tools for monitoring performance](tools-for-monitoring-performance.md) and [Set up Performance Monitor counters](set-up-performance-monitor-counters.md). If you are confident that your code and hardware are not causing the problems, then you might improve Enterprise Portal and Role Center performance by using the features and configuration settings described in this topic. This topic includes the following sections.

  - Configure session and server state settings in the web.config file

  - Use Windows Server AppFabric distributed caching for load-balanced environments

  - Remove Web parts from Role Center pages

## Configure session and server state settings in the web.config file

Session and server state settings in the Enterprise Portal web.config file directly affect how the server manages user sessions, caches objects, and allocates memory. By adjusting these settings, you might improve Enterprise Portal performance. Review the following descriptions carefully to understand which settings might have the most helpful impact on your Enterprise Portal environment, and then monitor configuration changes in a test environment.

You can customize the following session settings in the Enterprise Portal web.config file.

  - **Timeout:** Specifies the time, in seconds, before an inactive user session is ended. The default value is 30. If you increase the time-out, the session remains active longer and does not have to be rebuilt when the user sends another request. If you specify a longer time-out value, the system uses memory to store session state. As you adjust this setting monitor the performance cost of creating new sessions against storing session state in memory.

  - **MaxSessions:** Specifies the maximum number of cached concurrent sessions. The default value is 200. This setting cannot be set to less than 10. If you expect to have more than 200 concurrent users increase this number. Be aware that if you increase this value the system uses more memory. Conversely, if you do not have lots of concurrent users you can decrease this number to reduce memory consumption.

You can customize the following server-state settings in the Enterprise Portal web.config file.

  - **Enabled:** Set this to true to enable state storage on the server.

  - **MaxNumberOfInMemoryCachedItems:** Specifies the maximum number of in-memory cached items. The default value is 80. If you expect to have lots of concurrent users increase this number. Be aware that if you increase this value the system uses more memory. This option is not valid if the system is using Windows Server AppFabric.

  - **MaxNumberOfInMemoryCachedLargeItems:** Specifies the maximum number of in-memory cached large items. The default value is 15. If you expect to have lots of concurrent users increase this number. Be aware that if you increase this value the system uses more memory. This option is not valid if the system is using Windows Server AppFabric.

## Add the custom settings to the web.config file

Use the following procedure to add a block of custom settings to the Enterprise Portal web.config file in a test environment.

1.  On the server that hosts Enterprise Portal in your test environment, create a backup of the web.config file. By default the file is located in the following directory: “C:\\inetpub\\wwwroot\\wss\\VirtualDirectories\\80” where 80 represents the port number of the Enterprise Portal site.

2.  Open the web.config file in Microsoft Visual Studio or a simple text editor like Notepad.

3.  Press Ctrl + F to find the following tag: \</configSections\>.

4.  Copy and paste the following Microsoft Dynamics AX custom configuration section immediately after the \</configSections\> tag.
    
        <Microsoft.Dynamics>
           </Microsoft.Dynamics>

5.  Add one of the session and server state values. For example:
    
        <Microsoft.Dynamics>
           <Session Timeout="45" />
        </Microsoft.Dynamics>

6.  Save your changes in the web.config file, restart the Web service, and test the configuration change to see whether performance has improved. Repeat this process of adding a setting to the web.config file and testing the change. By incrementing changes in this manner you can see exactly which configuration change is helpful and which is detrimental to performance. Here is an example of a custom block of settings for Enterprise Portal that uses all of the settings described here.
    
        <Microsoft.Dynamics>
           <Session Timeout="45" MaxSessions="300" />
           <ServerState Enabled="true" MaxNumberOfInMemoryCachedItems="100" MaxNumberOfInMemoryCachedLargeItems="25" /> 
           </Microsoft.Dynamics>

## Use Windows Server AppFabric distributed caching for load-balanced environments

Windows Server AppFabric is a set of integrated technologies that make it easier to build, scale and manage Web and composite applications that run on IIS. For the purpose of Enterprise Portal, AppFabric provides a distributed caching system that can improve performance if Enterprise Portal is running in a server farm. Before you configure Enterprise Portal for AppFabric, you must install and configure Windows Server AppFabric in the SharePoint server farm. For more information, see Microsoft TechNet.

You can specify the following AppFabric parameters in the web.config file.

  - **AppFabricCaching:** Specifies Windows Server AppFabric distributed caching instead of ASP.NET caching.

  - **CacheName:** Specifies the name of the Windows Server AppFabric cache to use.

  - **Region:** Specifies the name of the Windows Server AppFabric region to use.

## Add the AppFabric setting to the web.config file

Use the following procedure to add the AppFabric setting to the web.config file. This procedure adds the AppFabric setting to the block of custom settings that were entered earlier in this topic. We recommend that you add these settings to the web.config file in a test environment.

1.  On the server that hosts Enterprise Portal in your test environment, create a backup of the web.config file. By default the file is located in the following directory: “C:\\inetpub\\wwwroot\\wss\\VirtualDirectories\\80” where 80 represents the port number of the Enterprise Portal site.

2.  Open the web.config file in Microsoft Visual Studio or a simple text editor like Notepad.

3.  Press Ctrl + F to find the following tag: \<Microsoft.Dynamics\>.

4.  Copy and paste the following settings in the \<Microsoft.Dynamics\> block of custom settings: \<AppFabricCaching CacheName=”*cache\_name*” Region=”*region\_name*” /\>. For example:
    
        <Microsoft.Dynamics>
           <Session Timeout="45" MaxSessions=”300” Configuration=”c:\test.axc” />
           <ServerState Enabled=”true” MaxNumberOfInMemoryCachedItems=”100” MaxNumberOfInMemoryCachedLargeItems=”25” /> 
          <AppFabricCaching CacheName=”EPTest” Region=”NorthAmerica” />
        </ Microsoft.Dynamics>

5.  Save your changes in the web.config file, restart the Web service, and test the configuration change to see whether performance has improved.

## Remove Web parts from Role Center pages

If Role Center pages take a long time to load, you might be able to improve performance by removing unused or unwanted Web parts from Role Center pages. For information about how to remove a Web part from a SharePoint page, see the SharePoint product documentation on Microsoft TechNet.

## See also

[Optimize performance](optimize-performance.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

