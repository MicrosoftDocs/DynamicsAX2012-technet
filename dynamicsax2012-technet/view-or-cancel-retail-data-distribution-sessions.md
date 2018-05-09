---
title: View or cancel retail data distribution sessions
TOCTitle: View or cancel retail data distribution sessions
ms:assetid: 7a8e08f3-2a2b-4a2c-a51d-e578504ca88e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497795(v=AX.60)
ms:contentKeyID: 62200206
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailCDXDownloadSessionDataStore
- MsDynAx060.Forms.RetailCDXUploadSession
- MsDynAx060.Forms.RetailCDXDownloadSessionDataStore
- Forms.RetailCDXUploadSession
---

# View or cancel retail data distribution sessions 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The **Download sessions** form and the **Upload sessions** form show information about data distribution jobs that are in progress or have been completed. A run of a job is referred to as a session. Use the information in these forms for troubleshooting. You can also run a session again or cancel a session from these forms.

To display complete status information in these forms, you must run the batch job that processes status messages for Commerce Data Exchange. For more information, see [Process status messages for data exchange](process-status-messages-for-data-exchange.md).

This topic includes the following information:

  - View information about download sessions

  - View information about upload sessions

## View information about download sessions

Use the **Download sessions** form to view information about jobs that transfer data from Microsoft Dynamics AX to channels.

1.  Click **Retail** \> **Inquiries** \> **Commerce Data Exchange** \> **Download sessions**.

2.  Select a date range for which to view data. By default, records that have a status of **No data** are not shown in the list. Select **Show all records** to view an unfiltered list.

3.  You can view the following information about download sessions.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Job name</strong></p></td>
    <td><p>The identifier for the scheduler job that was run in the session.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Channel data group</strong></p></td>
    <td><p>The data group that the session was run against. A channel data group can contain multiple channel databases.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Channel database</strong></p></td>
    <td><p>The channel database that was affected by the session.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Status</strong></p></td>
    <td><p>The status of the session. The following statuses are used:</p>
    <ul>
    <li><p><strong>Started</strong> – The data package was created in the working folder.</p></li>
    <li><p><strong>Available</strong> – The data package is available for download.</p></li>
    <li><p><strong>Requested</strong> – The data package has been requested by Async Client.</p></li>
    <li><p><strong>Downloaded</strong> – The data package has been downloaded by Async Client.</p></li>
    <li><p><strong>Applied</strong> – The data package has been applied to the channel database.</p></li>
    <li><p><strong>Canceled</strong> – The session was canceled by the user.</p></li>
    <li><p><strong>Create failed</strong> – The data package could not be created. Review the detailed error message for more information.</p>
    <p>After you have resolved the error, run the distribution schedule again. If the distribution schedule runs as part of a batch job, it is run again the next time that the batch job runs.</p></li>
    <li><p><strong>Download failed</strong> – The data package could not be downloaded. Review the detailed error message for more information.</p>
    <p>After you have resolved the error, Async Client tries the download again according to the retry interval.</p></li>
    <li><p><strong>Apply failed</strong> – The data package could not be applied to the channel database. Review the detailed error message for more information.</p>
    <p>If there is a configuration issue, fix the issue, and wait for the next retry by Async Client. If there is a data issue that you can’t resolve by modifying the database schema, cancel the session.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Message</strong></p></td>
    <td><p>If there was an error, the detailed error message text.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Date requested</strong></p></td>
    <td><p>The date and time when Async Client requested the data package.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Date downloaded</strong></p></td>
    <td><p>The date and time when the data package was successfully downloaded by Async Client.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Date applied</strong></p></td>
    <td><p>The date and time when the data package was successfully applied to the channel database.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Created date and time</strong></p></td>
    <td><p>The date and time when the data package was created.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Session number</strong></p></td>
    <td><p>The identifier for the session.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Download path</strong></p></td>
    <td><p>The working folder where data packages are created.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Rows affected</strong></p></td>
    <td><p>The number of rows in the database that are read from Microsoft Dynamics AX and sent to the channel.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Modified date and time</strong></p></td>
    <td><p>The date and time when the data package was last modified.</p></td>
    </tr>
    </tbody>
    </table>


4.  To run a session again, select the session, and then click **Rerun**.
    
    To cancel a session, select the session, and then click **Cancel**.

## View information about upload sessions

Use the **Upload sessions** form to view information about jobs that transfer data from channels to Microsoft Dynamics AX.

1.  Click **Retail** \> **Inquiries** \> **Commerce Data Exchange** \> **Upload sessions**.

2.  You can view the following information about upload sessions.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Job name</strong></p></td>
    <td><p>The identifier for the scheduler job that was run in the session.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Channel database</strong></p></td>
    <td><p>The channel database where the data originated.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Session number</strong></p></td>
    <td><p>The identifier for the session.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Upload session status</strong></p></td>
    <td><p>The status of the session. The following statuses are used:</p>
    <ul>
    <li><p><strong>Started</strong> – The data package was created in the working folder.</p></li>
    <li><p><strong>Available</strong> – The data package is available for upload.</p></li>
    <li><p><strong>Uploaded</strong> – The data package has been uploaded.</p></li>
    <li><p><strong>Applied</strong> – The data package has been applied to the Microsoft Dynamics AX database.</p></li>
    <li><p><strong>Canceled</strong> – The session was canceled by the user.</p></li>
    <li><p><strong>Upload failed</strong> – The data package could not be uploaded. Review the detailed error message for more information.</p>
    <p>After you have resolved the error, Async Client tries the upload again according to the retry interval.</p></li>
    <li><p><strong>Apply failed</strong> – The data package could not be applied to the Microsoft Dynamics AX database. Review the detailed error message for more information.</p>
    <p>If there is a configuration issue, fix the issue, and wait for the next retry by Async Client. If there is a data issue that you can’t resolve by modifying the database schema, cancel the session.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Rows affected</strong></p></td>
    <td><p>The number of rows in the database that are read from the channel database and sent to Microsoft Dynamics AX.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Temporary files path</strong></p></td>
    <td><p>The working folder where data packages are created.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>File size</strong></p></td>
    <td><p>The size of the data package file.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Date and time created</strong></p></td>
    <td><p>The date and time when the data package was created.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Date and time modified</strong></p></td>
    <td><p>The date and time when the data package was last modified.</p></td>
    </tr>
    </tbody>
    </table>


3.  To run a session again, select the session, and then click **Rerun**.
    
    To cancel a session, select the session, and then click **Cancel**.

## See also

[View history for a distribution schedule](view-history-for-a-distribution-schedule.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

