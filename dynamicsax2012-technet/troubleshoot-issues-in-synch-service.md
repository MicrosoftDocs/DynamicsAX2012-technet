---
title: Troubleshoot issues in Synch Service
TOCTitle: Troubleshoot issues in Synch Service
ms:assetid: 60b6ee43-5e95-4eca-9736-b4d53b7d38d6
ms:mtpsurl: https://technet.microsoft.com/library/JJ891081(v=AX.60)
ms:contentKeyID: 50646136
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Troubleshoot issues in Synch Service 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

When a communication issue occurs, an error is returned by Commerce Data Exchange: Synch Service. You can view Synch Service messages in the following locations.


> [!NOTE]
> <P>Synch Service is required for Retail only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack. In Microsoft Dynamics AX 2012 R3, this component is used only to support previous versions of Retail POS while you upgrade (N-1).</P>



<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Monitoring tool</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Synch Service messages</p></td>
<td><p>View status and error messages for Synch Service in the <strong>Commerce Data Exchange: Synch Service messages</strong> form. (Click <strong>Retail</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Commerce Data Exchange: Synch Service messages</strong>.)</p>
<p>To trace the history of a message, select the message, and then click <strong>View message tree</strong> to open the <strong>Commerce Data Exchange: Synch Service message tree</strong> form. In this form, you can see the origin and routing of the message.</p>
<div class="alert">
<div class="mtps-table">
<div class="mtps-row">
<img src="images/Dn527205.alert_note(AX.60).gif" title="Note" alt="Note" class="note" /><strong>Note</strong>
</div>
<div class="mtps-row">
You must configure an upload profile before messages are available in Microsoft Dynamics AX. Create upload profiles by using the <strong>Commerce Data Exchange: Synch Service upload options</strong> form. (Click <strong>Retail</strong> &gt; <strong>Setup</strong> &gt; <strong>Retail scheduler</strong> &gt; <strong>Channel integration</strong> &gt; <strong>Commerce Data Exchange: Synch Service upload options</strong>.)
</div>
</div>
</div>
<p>Messages are stored in the Microsoft Dynamics AX database. To free disk space, you can periodically delete stored messages.</p>
<p>For more information about one of these forms, open the form, and then press F1.</p></td>
</tr>
<tr class="even">
<td><p>Microsoft Dynamics AX Infolog</p></td>
<td><p>If you run a job manually in Microsoft Dynamics AX, and Microsoft Dynamics AX cannot communicate with Synch Service, an error code is displayed in the <strong>Infolog</strong> form.</p>
<p>If the scheduler job runs as part of a batch, you can view error messages in the <strong>Batch job history</strong> form. For more information about batch processing, see <a href="process-batch-jobs-and-tasks.md">Process batch jobs and tasks</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Synch Service log file</p></td>
<td><p>You can configure Synch Service to save error information in a log file. You can specify the location of the log file, the level of logging, and the maximum number of lines in the log file.</p>
<p>For information about how to configure logging for Synch Service, see <a href="configure-settings-for-synch-service.md">Configure settings for Synch Service</a>.</p></td>
</tr>
<tr class="even">
<td><p>Windows event log</p></td>
<td><p>Depending on how logging is configured for Synch Service, you may be able to view full logs of Synch Service events in the Windows event log of the host computer.</p>
<p>For information about how to configure logging for Synch Service, see <a href="configure-settings-for-synch-service.md">Configure settings for Synch Service</a>.</p></td>
</tr>
</tbody>
</table>


## Troubleshoot error codes in Synch Service

Use the information in the following table to troubleshoot common errors in Synch Service. Errors in Synch Service are typically caused by one of two general issues: an error in communication between Microsoft Dynamics AX and Synch Service, or an error in the processing of a job.


> [!NOTE]
> <P>The same error code can represent multiple issues. When you troubleshoot, you should consider both the documentation about the error code and the detailed error message that is displayed together with the error code.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Code</p></th>
<th><p>Definition</p></th>
<th><p>Suggested resolution</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>4096</p></td>
<td><p><strong>Error inserting in system tables</strong></p>
<p>An error occurred while Synch Service was confirming the data package.</p></td>
<td><p>Review the Synch Service error log for more information.</p></td>
</tr>
<tr class="even">
<td><p>4097</p></td>
<td><p><strong>Remote connection dropped</strong></p>
<p>The TCP/IP connection was ended while Synch Service was forwarding a package, or the receiving instance of Synch Service was shut down during the transfer.</p></td>
<td><p>Restore the network connection. If the network connection is slow or overloaded, consider increasing the TCP/IP time-out for both Synch Service instances. You can adjust the TCP/IP time-out in Synch Service Settings.</p></td>
</tr>
<tr class="odd">
<td><p>4098</p></td>
<td><p><strong>Canceled because of send and receive size</strong></p>
<p>The registered size of the package does not match the actual size of the package. This issue is most likely caused by a transmission failure.</p></td>
<td><p>Resend the package by running the Retail Scheduler job again.</p></td>
</tr>
<tr class="even">
<td><p>4099</p></td>
<td><p><strong>Cannot find new packet number</strong></p>
<p>Synch Service could not assign a new package number to an incoming package. Typically, this issue occurs when the message database for the receiving instance of Synch Service is configured incorrectly in Synch Service Settings.</p></td>
<td><p>Confirm that the message database is configured correctly, and that the Synch Service user has the required permissions.</p></td>
</tr>
<tr class="odd">
<td><p>4100</p></td>
<td><p><strong>Cannot instance a socket</strong></p>
<p>The operating system could not create a Windows TCP/IP socket. TCP/IP might not be installed or enabled on the computer.</p></td>
<td><p>Confirm that the TCP/IP protocol is installed and enabled on the computer.</p></td>
</tr>
<tr class="even">
<td><p>4102</p></td>
<td><p><strong>HopCount has exceeded its maximum value</strong></p>
<p>A package cannot be transferred, because the hop counter for the package has reached the maximum that is set in Synch Service Settings.</p>
<p>This error can occur when a service name is incorrectly assigned to an IP address. The error can also be caused by an inconsistency between the server name for a location and the actual server name for the instance of Synch Service.</p></td>
<td><ul>
<li><p>Verify the DNS registration of the server name or the entry for the server name in the Hosts files on all computers that are involved.</p></li>
<li><p>Confirm that the server name for the location in the <strong>Commerce Data Exchange: Synch Service profiles</strong> form matches the service name in Synch Service Settings.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>8192</p></td>
<td><p><strong>Error in processing request</strong></p>
<p>An unhandled exception occurred when Synch Service was reading from or writing to a database. This error is typically not related to the database connection.</p></td>
<td><ul>
<li><p>Check the event log for more information. Because this error occurred at the database level, the database has likely reported the cause of the error in the event log.</p></li>
<li><p>Check for an invalid or incorrect setup for field transfers in a subjob.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>12288</p></td>
<td><p><strong>An error occurred connecting to Synch Service</strong></p>
<p>Microsoft Dynamics AX cannot connect to Synch Service. This error can occur in the following situations:</p>
<ul>
<li><p>Synch Service is not running.</p></li>
<li><p>Microsoft Dynamics AX is trying to connect to a service that does not exist, or that is not associated with the correct IP address.</p></li>
<li><p>Microsoft Dynamics AX is trying to connect to Synch Service on an invalid TCP/IP port.</p></li>
</ul></td>
<td><ul>
<li><p>Start the Synch Service service.</p></li>
<li><p>Confirm that the service name for Synch Service is associated with an IP address. To confirm the IP address, at a command prompt, type <strong>ping &lt;Synch Service computer name&gt;</strong>. If the service name does not respond to a ping command, you must reconfigure your DNS server or Hosts file so that the service name is associated with the correct IP address.</p></li>
<li><p>Verify that the port numbers match in Synch Service Settings and in the Synch Service profile.</p></li>
<li><p>If IPsec is enabled, verify that it is configured correctly. Alternatively, verify that the firewall is configured correctly. For example, connect to the Synch Service port by using Telnet.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>12295</p></td>
<td><p><strong>Waiting for a previous package</strong></p>
<p>A previous package that is part of the same JobID has not been processed successfully. Check the job status to determine whether the job is waiting, or whether there is an issue with the job.</p></td>
<td><ul>
<li><p>Take corrective action so that the package is processed successfully.</p></li>
<li><p>Cancel the job by using one of the following methods:</p>
<ul>
<li><p>If an upload profile has been configured and selected for Synch Service messages, select the message in the <strong>Commerce Data Exchange: Synch Service messages</strong> form, and then click <strong>Cancel</strong>.</p></li>
<li><p>Set CancelledByUser=1 in the message database.</p></li>
</ul></li>
</ul></td>
</tr>
<tr class="even">
<td><p>12305</p></td>
<td><p><strong>Error while sending package information</strong></p></td>
<td><ul>
<li><p>Retry the operation.</p></li>
<li><p>Check all connections.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>12306</p></td>
<td><p><strong>Error while transferring package</strong></p>
<p>A connection has failed, or the network is unstable.</p></td>
<td><ul>
<li><p>Retry the operation.</p></li>
<li><p>Check all connections.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>16384</p></td>
<td><p><strong>Error writing file</strong></p></td>
<td><ul>
<li><p>Free some space on the disk.</p></li>
<li><p>Confirm that the process has the required permissions to write to the disk.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>16385</p></td>
<td><p><strong>Error creating file</strong></p>
<p>Synch Service cannot write to the hard disk. Possible causes include the following issues:</p>
<ul>
<li><p>The disk is full.</p></li>
<li><p>Synch Service does not have permissions to write to the working directory.</p></li>
<li><p>The path of the working directory, as specified in Synch Service Settings, is incorrect.</p></li>
</ul></td>
<td><ul>
<li><p>Free some space on the disk.</p></li>
<li><p>Confirm that the process has the required permissions to write to the disk.</p></li>
<li><p>Confirm that the path of the working directory is correct.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>16386</p></td>
<td><p><strong>Error reading file</strong></p>
<p>Synch Service was trying to read a file that does not exist.</p></td>
<td><p>Re-create the file by running the job again.</p></td>
</tr>
<tr class="odd">
<td><p>24577</p></td>
<td><p><strong>Synch Service system error</strong></p>
<p>Synch Service encountered a system error. This error code represents several issues that might occur with the service.</p></td>
<td><p>See the error log for more information.</p></td>
</tr>
<tr class="even">
<td><p>24578</p></td>
<td><p><strong>Synch Service communication error</strong></p>
<p>Synch Service encountered a communication error. This error code represents several communication issues that might occur.</p></td>
<td><ul>
<li><p>Retry the operation.</p></li>
<li><p>Check all connections.</p></li>
<li><p>See the error log for error codes that were reported by Windows. Typically, this error is a socket error.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>24579</p></td>
<td><p><strong>Synch Service job metadata processing error</strong></p>
<p>An error occurred when Synch Service was preprocessing a request package.</p></td>
<td><p>See the error log for more information.</p></td>
</tr>
<tr class="even">
<td><p>24580</p></td>
<td><p><strong>Synch Service message database error</strong></p>
<p>Synch Service cannot connect to the message database. Possible causes include the following issues:</p>
<ul>
<li><p>An incorrect server name is specified in the connection settings for the database.</p></li>
<li><p>An incorrect database name is specified in the connection settings for the database.</p></li>
<li><p>Appropriate permissions are not granted to the database.</p></li>
</ul></td>
<td><p>See the error log for more information.</p>
<p>If Synch Service cannot access the message database, verify the connection string to the database in the following registry setting:</p>
<p>HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\ Dynamics \6.0\Retail Store Connect\Servers \SERVICE_INSTANCE_NAME, key: SysConnStr</p></td>
</tr>
<tr class="odd">
<td><p>28673</p></td>
<td><p><strong>Error when request handler manager is preparing/packing/unpacking request and processing temp data files</strong></p>
<p>Possible causes include the following issues:</p>
<ul>
<li><p>The package is corrupted.</p></li>
<li><p>The channel schema for the distribution location is configured incorrectly. In this case, the error message likely says “Cannot find request handler factory.”</p></li>
<li><p>Synch Service does not have permission to create the working folder or to write files to the working folder.</p></li>
</ul></td>
<td><ul>
<li><p>See the error log for more information.</p></li>
<li><p>Check all connections.</p></li>
<li><p>In the <strong>Distribution locations</strong> form, verify the retail channel schema for the distribution location.</p></li>
<li><p>Make sure that folder permissions have been set correctly.</p></li>
<li><p>Retry the operation.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>32769</p></td>
<td><p><strong>Error when request handler fails to process request</strong></p>
<p>Typically, this kind of error means that data from the channel database or the Microsoft Dynamics AX database cannot be read or written. This issue can occur when the scheduler job is not configured correctly.</p></td>
<td><p>Because there are many possible causes for this error code, we recommend that you see the error log for the detailed error message from the database.</p></td>
</tr>
</tbody>
</table>


## Troubleshoot common issues with data packages

Use the information in the following table to troubleshoot issues with data packages. To view the information that is contained in a data package, you must use Commerce Data Exchange: Synch Service Pack Viewer. For more information, see [Synch Service Pack Viewer](synch-service-pack-viewer.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Issue</p></th>
<th><p>Solution</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>A package that failed blocks the processing of other packages.</p></td>
<td><p>When a package is not processed successfully, its blocked status can prevent other packages from being sent, even after you have resolved the cause of the error. To resume ordinary communications, in the message database, set CancelledByUser=1 for the messages that are related to the blocked package.</p>
<p>If Synch Service was configured to upload status messages to Microsoft Dynamics AX, you can view and cancel error messages in the <strong>Commerce Data Exchange: Synch Service messages</strong> form. (Click <strong>Retail</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Commerce Data Exchange: Synch Service messages</strong>.)</p>
<p>If Synch Service was not configured to upload status messages, you must use Microsoft SQL Server Management Studio to cancel the blocking messages. On the originating computer, in SQL Server Management Studio, expand the <strong>Databases</strong> folder, click the message database, and then click <strong>New Query</strong>. In the query pane, type <strong>update dbo.IncomingMessages set CancelledByUser=1 where PackageNo='nnnn'</strong>, where nnnn is the ID number of the failed package. Then click <strong>Execute</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Synch Service at the head office cannot read results for a query packet.</p></td>
<td><p>If a job is unsuccessful, and no records were changed in the store database, follow these steps to determine the reason for the failure.</p>
<ol>
<li><p>Confirm that the request from Retail Scheduler reached the head office instance of Synch Service.</p></li>
<li><p>Confirm that the message database for the head office instance of Synch Service contains a corresponding record in the incoming messages table.</p></li>
<li><p>Confirm that the request packet was created by Synch Service. A request packet is also referred to as an “I” file, and the file name is in the form &lt;Synch Service service name&gt;-&lt;sequential number&gt;-I.tmp. If the <strong>Keep Package Files</strong> check box was selected in Synch Service Settings, this file is in the working directory.</p></li>
<li><p>Make sure that .NET Business Connector is installed. .NET Business Connector is required on the communications server at the head office.</p></li>
<li><p>Verify that the entry in the incoming message table for this packet has no errors. If Synch Service cannot process a request, it does not generate a result packet, and an error occurs. A result packet is also referred to as an “R” file, and the file name is in the form &lt;Synch Service service name&gt;-&lt;sequential number&gt;-R.tmp]. This issue could be caused by a scheduler job that is not configured correctly. In this case, see the detailed message in the error log for more information.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Synch Service crashes when it processes many transactions.</p></td>
<td><p>The default thread time-out for Synch Service is 10800 seconds, but this value may not be sufficient when many transactions are processed. If you are processing more than 200,000 transactions, and Synch Service crashes without synchronizing the data, try increasing the thread time-out.</p></td>
</tr>
</tbody>
</table>

  


