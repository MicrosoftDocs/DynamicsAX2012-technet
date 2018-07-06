---
title: Troubleshoot issues in Async Server or Async Client
TOCTitle: Troubleshoot issues in Async Server or Async Client
ms:assetid: 0405aece-8e58-47c4-a460-47dfc0563092
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn750875(v=AX.60)
ms:contentKeyID: 62369570
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Troubleshoot issues in Async Server or Async Client 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Use the information in this topic to troubleshoot issues with Commerce Data Exchange: Async Server or Commerce Data Exchange: Async Client.

## Test connections

Use the Async Client Configuration Tool to test connections between Async Client and other components.

1.  Start the Async Client Configuration Tool. By default, the executable file is located at C:\\Program Files\\Microsoft Dynamics AX\\60\\CDX\\Async Client\\\<DatabaseName\>\_Package. Double-click the **AsyncClientConfigurationUtility.exe** file.

2.  Test connections to other components, as shown in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Async Client connection</p></th>
    <th><p>How to verify the connection</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Async Server</p></td>
    <td><p>On the <strong>Async Server connection</strong> tab, in the <strong>Authentication information</strong> section, click <strong>Test connection</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p>Channel message database</p></td>
    <td><p>On the <strong>Channel configuration</strong> tab, in the <strong>Channel message database</strong> section, click <strong>Test connection</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Channel database</p></td>
    <td><p>On the <strong>Channel configuration</strong> tab, in the <strong>Channel database</strong> section, click <strong>Test connection</strong>.</p></td>
    </tr>
    </tbody>
    </table>


## Troubleshoot connectivity issues

If connection tests for Async Client are not successful, we recommend that you verify the following information.

  - Verify that the URL to Async Server is correct. Double-check the server name, web site name, port number, and protocol that are used.

  - Verify that the channel database ID is correct in the Async Client configuration. The value that you set for the channel database ID must match the value that is set in the **Channel database** form in Microsoft Dynamics AX.

  - Verify the user name and password for the connection to Async Server. The user name and password must match the values that were set in the **Channel database** form in Microsoft Dynamics AX.

  - Run the **Sync metadata** process in the **Retail scheduler parameters** form. This process synchronizes configuration data for Commerce Data Exchange with the message database at headquarters.

  - Make sure that initial data has been distributed to the channel database. In the **Channel database** form, click **Full data sync** and then select the distribution schedule that is named **Full sync**.

  - On the location computer, verify that remote connections to Microsoft SQL Server are enabled, and that SQL Server users and permissions are set up correctly. For more information about these requirements, see [Configure SQL Server for the Retail databases](configure-sql-server-for-the-retail-databases.md).

  - Use ping, Telnet, or another network utility to verify that the location computer can connect to the Microsoft Dynamics AX computer at the head office. If it cannot, make sure that the firewall at headquarters is open to the required ports or programs. If the firewall is already open, work with the network administrator to correct the network configuration.

## Find information about data distribution issues

If there are issues with data distribution, more information is available in the following locations.

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
<td><p><strong>Download sessions</strong> form and <strong>Upload sessions</strong> form</p></td>
<td><p>View information about data distribution jobs that are in progress or have been completed.</p>
<p>To open the <strong>Download sessions</strong> form: Click <strong>Retail</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Commerce Data Exchange</strong> &gt; <strong>Download sessions</strong>.</p>
<p>To open the <strong>Upload sessions</strong> form: Click <strong>Retail</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Commerce Data Exchange</strong> &gt; <strong>Upload sessions</strong>.</p>
<p>For more information about how to use these forms, see <a href="view-or-cancel-retail-data-distribution-sessions.md">View or cancel retail data distribution sessions</a>.</p>
<div class="alert">

> [!NOTE]  
> To display complete status information in these forms, you must run the batch job that processes status messages for Commerce Data Exchange. For more information, see <a href="process-status-messages-for-data-exchange.md">Process status messages for data exchange</a>.

</div></td>
</tr>
<tr class="even">
<td><p><strong>Download history</strong> form</p></td>
<td><p>View information about the jobs that were previously run for a selected distribution schedule. A run of a job is referred to as a session.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Batch job history</strong> form</p></td>
<td><p>If the scheduler job runs as part of a batch, you can view error messages in the <strong>Batch job history</strong> form. For more information about batch processing, see <a href="process-batch-jobs-and-tasks.md">Process batch jobs and tasks</a>.</p></td>
</tr>
<tr class="even">
<td><p>Windows event log</p></td>
<td><p>Depending on how logging is configured, you may be able to view logs of events in the Windows event log of the host computer.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

