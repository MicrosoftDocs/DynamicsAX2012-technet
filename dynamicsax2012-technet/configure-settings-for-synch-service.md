---
title: Configure settings for Synch Service
TOCTitle: Configure settings for Synch Service
ms:assetid: 06302927-ef14-4fd3-8d54-3825679137ce
ms:mtpsurl: https://technet.microsoft.com/library/JJ679908(v=AX.60)
ms:contentKeyID: 49557890
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Configure settings for Synch Service 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic describes how to use the Synch Service Settings wizard to manage Commerce Data Exchange: Synch Service. You must have administrative credentials to open the Synch Service Settings wizard.


> [!NOTE]
> <P>Synch Service is required for Retail only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack. In Microsoft Dynamics AX 2012 R3, this component is used only to support previous versions of Retail POS while you upgrade (N-1).</P>



1.  Click **Start** \> **All Programs** \> **Microsoft Dynamics AX** \> **Commerce Data Exchange** \> **Synch Service** \> **Service Settings** to open the wizard.

2.  To register an instance of Synch Service, type the name of the instance in the **Server name** field, and then click **Add**. By default, the local computer name is displayed. This step associates the instance of Synch Service with the local message database.
    
    To manage an existing instance, select the instance in the **All Servers** list. You can also start or stop an instance on this page.
    

    > [!TIP]
    > <P>To prevent confusion, use a unique name for each instance of Synch Service in the organization.</P>

    
    Click **Next**.

3.  On the **Service properties** page, enter the following information, or accept the default settings.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Packet Owner</strong></p></td>
    <td><p>If you select <strong>2nd Stage Synch Service</strong> in the <strong>Server mode</strong> field, specify the server where packages originate.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Server mode</strong></p></td>
    <td><p>In most cases, you should select <strong>Synch Service</strong>. However, if the selected instance of Synch Service is a forwarder, select <strong>2nd Stage Synch Service</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Server port</strong></p></td>
    <td><p>Enter the listening port for Synch Service. This setting is not available for a forwarder instance, because in that case, the service only forwards packages. If you plan to run more than one instance of the service on the same computer, you must change the port values so that they do not conflict with other services.</p>
    <p>Use the <strong>Off</strong> button to turn the server listening port on or off. We do not recommend that you turn the port off.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Telnet port</strong></p></td>
    <td><p>Enter the port that is used by the Synch Service Telnet interface. This feature lets you use Telnet to monitor the status of Synch Service. If you also run a Telnet server on the computer, assign the Synch Service interface to another port to conflicts.</p></td>
    </tr>
    </tbody>
    </table>
    
    Click **Next**.

4.  On the **Synch Service specific properties** page, enter the following information, or accept the default settings.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Working Directory</strong></p></td>
    <td><p>The path of the folder where Synch Service keeps temporary files and package files, if it is configured to keep package files. To change this path, click <strong>Browse</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Days Messages Exist</strong></p></td>
    <td><p>Enter the number of days to keep incoming or outgoing messages that have been processed. If you type a value of <strong>0</strong> in this field, messages are not deleted.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Timer Interval</strong></p></td>
    <td><p>Enter the interval at which Synch Service checks for packages that must be reprocessed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Limit Job Process (cnt)</strong></p></td>
    <td><p>Enter the maximum number of job records that Synch Service processes per connection. You should set this field to a lower value when the average package size is high, and to a higher value when the average package size is low. To disable the feature, enter a value of <strong>0</strong>. We do not recommend that you disable this feature.</p>
    <p>This feature ensures that Synch Service continues to process job records, even if it has a heavy load that might typically cause it to stop responding. Additionally, when this feature is on, if the first job record in the batch has an error, the remaining packages are skipped for the run.</p></td>
    </tr>
    </tbody>
    </table>
    
    Click **Next**.

5.  On the **Synch Service Properties** page, enter the following information, or accept the default settings.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Hold Connections</strong></p></td>
    <td><p>Enter the number of connections to the source database that Synch Service should reserve.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Idle Conn. Time</strong></p></td>
    <td><p>Enter the number of idle minutes before the reserved connections time out and are released.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Thread Timeout</strong></p></td>
    <td><p>Enter the number of seconds before threads that are used in connections to remote locations time out.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Max. Forw. Threads</strong></p></td>
    <td><p>Enter the maximum number of threads that can be used concurrently to send packages.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Max Hop counter</strong></p></td>
    <td><p>Enter the maximum number of transfers, per package, between instances of Synch Service. This setting prevents infinite loops that can be caused by a Synch Service instance that is incorrectly configured.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Socket Timeout</strong></p></td>
    <td><p>Enter the number of seconds that Synch Service waits for the network to finish a particular send or receive operation. To prevent Synch Service from shutting down just because it is waiting for the network, set this field to a value that is lower than the value in the <strong>Thread Timeout</strong> field.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Retry Interval</strong></p></td>
    <td><p>Enter the interval at which Synch Service makes another attempt to perform an operation on a package that failed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Maximum retries</strong></p></td>
    <td><p>Enter the number of attempts before Synch Service stops trying to perform an operation on a package.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Forw. Attempts</strong></p></td>
    <td><p>Enter the maximum number of attempts that Synch Service makes to forward a packet. This setting works only on a forwarder instance.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Use Processor</strong></p></td>
    <td><p>Enter the processor that the service should run on. If you want the operating system to allocate processors, select <strong>All Processors</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Disable IPsec</strong></p></td>
    <td><p>Select this option to bypass the IPsec requirements of Synch Service. For more information, see <a href="configure-or-bypass-ipsec-for-synch-service.md">Configure or bypass IPsec for Synch Service</a>.</p>
    <div class="alert">
    <div class="mtps-table">
    <div class="mtps-row">
    <img src="images/Dn527205.alert_note(AX.60).gif" title="Note" alt="Note" class="note" /><strong>Note</strong>
    </div>
    <div class="mtps-row">
    If the <strong>Disable IPsec</strong> option is selected for a distribution location in Retail Scheduler, the <strong>Disable IPsec</strong> option in Synch Service Settings should be selected for all instances of Synch Service that communicate with that location.
    </div>
    </div>
    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Prefer IPV6</strong></p></td>
    <td><p>Select this check box to use the IPv6 communication protocol, if it is enabled.</p></td>
    </tr>
    </tbody>
    </table>
    
    Click **Next**.

6.  On the **Server debugging properties** page, enter the following information, or accept the default settings.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Keep Package Files</strong></p></td>
    <td><p>Select this option if you want to save the packages of exchanged information so that you can view them by using Synch Service Pack Viewer. When this option is selected, Synch Service does not delete the temporary package files from the working directory.</p>
    <p>Do not enable this feature for a long time, because it can cause you to run out of disk space and prevent Synch Service from operating correctly. For more information about Pack Viewer, see <a href="synch-service-pack-viewer.md">Synch Service Pack Viewer</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Exception Dump</strong></p></td>
    <td><p>Select this option to create a memory dump file if Synch Service suddenly stops working.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Log/Dump Dir</strong></p></td>
    <td><p>Enter the folder where log files are saved. Confirm that the folder that you specify actually exists.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Log Mode</strong></p></td>
    <td><p>Select this option to log Synch Service operations in the manner that is specified by the <strong>Log Level</strong> settings.</p>
    <p>When <strong>Write to Windows event log</strong> is selected, Synch Service writes the logging data to the Windows event log.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Max Lines/Logfile</strong></p></td>
    <td><p>Enter the maximum number of lines in each log file. Synch Service creates three log files. When the maximum number of lines has been reached in one log file, Synch Service rotates to the next log file. At startup, Synch Service makes a copy of the old log files by appending <strong>.old</strong> to their names. Therefore, if the service has been set to automatically restart when a failure occurs, the failure appears in the old log files.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Log Level</strong></p></td>
    <td><p>Select the amount of error logging that occurs. Usually, <strong>Error</strong> logging and <strong>Main</strong> logging are sufficient, but more detail might be helpful in some cases. The following levels are available:</p>
    <ul>
    <li><p><strong>Error</strong> – All errors that are reported from Synch Service are logged.</p></li>
    <li><p><strong>Main</strong> – The main operations in Synch Service are logged.</p></li>
    <li><p><strong>Actions</strong> – Detailed information about operations in Synch Service is logged.</p></li>
    <li><p><strong>Detail</strong> – Very detailed information about operations in Synch Service is logged.</p></li>
    <li><p><strong>Functions</strong> – Highly detailed and technical information about operations in Synch Service is logged. This option is intended for use by developers only.</p></li>
    </ul>
    <div class="alert">
    <div class="mtps-table">
    <div class="mtps-row">
    <img src="images/Gg732282.alert_caution(AX.60).gif" title="Important" alt="Important" class="note" /><strong>Important</strong>
    </div>
    <div class="mtps-row">
    The logging that is specified by the <strong>Log Level</strong> settings can occur only if the <strong>Log Mode</strong> option is selected.
    </div>
    </div>
    </div></td>
    </tr>
    </tbody>
    </table>
    
    Click **Finish**. To configure another instance of Synch Service, select the instance in the **All Servers** list, and then repeat the steps in this procedure.

7.  When the configuration is completed, close the wizard.

8.  On a Microsoft Dynamics AX client computer, modify the Application Object Server (AOS) profile so that it uses this instance of Synch Service. For more information, see [Set up an AOS profile](set-up-an-aos-profile.md).

  


