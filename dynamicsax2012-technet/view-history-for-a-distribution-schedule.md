---
title: View history for a distribution schedule
TOCTitle: View history for a distribution schedule
ms:assetid: 50a852c6-e8c4-474f-ad1c-f9ab4ac0e797
ms:mtpsurl: https://technet.microsoft.com/library/Dn497754(v=AX.60)
ms:contentKeyID: 62200202
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailCDXDownloadSession
- MsDynAx060.Forms.RetailCDXDownloadSession
---

# View history for a distribution schedule 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The **Download history** form shows information about the jobs that were previously run for a selected distribution schedule. A run of a job is referred to as a session. Use the information in this form for troubleshooting. You can also run a session again from this form.

To display complete status information in this form, you must run the batch job that processes status messages for Commerce Data Exchange. For more information, see [Process status messages for data exchange](process-status-messages-for-data-exchange.md).

1.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

2.  Select a distribution schedule, and then click **History**.

3.  In the **Download history** form, you can view the following information about each session that was tried for the selected distribution schedule.
    
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
    <td><p>The name of the job that ran.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Channel data group</strong></p></td>
    <td><p>The channel data group that the job was run against.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Session number</strong></p></td>
    <td><p>The identifier for the session.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Status</strong></p></td>
    <td><p>The status of the session. The following statuses are used:</p>
    <ul>
    <li><p><strong>Started</strong> –Async Server has started to create the data package in the working folder.</p></li>
    <li><p><strong>Available</strong> – The data package is available for download.</p></li>
    <li><p><strong>Requested</strong> – The data package has been requested by Async Client.</p></li>
    <li><p><strong>Downloaded</strong> – The data package has been downloaded by Async Client.</p></li>
    <li><p><strong>Applied</strong> – The data package has been applied to the channel database.</p></li>
    <li><p><strong>Canceled</strong> – The session was canceled.</p></li>
    <li><p><strong>Create failed</strong> – The data package could not be created. Review the detailed error message for more information.</p>
    <p>After you have resolved the error, run the distribution schedule again. If the distribution schedule runs as part of a batch job, it is run again the next time that the batch job runs.</p></li>
    <li><p><strong>Download failed</strong> – The data package could not be downloaded. Review the detailed error message for more information.</p>
    <p>After you have resolved the error, Async Client tries the download again according to the retry interval.</p></li>
    <li><p><strong>Apply failed</strong> – The data package could not be applied to the channel database. Review the detailed error message for more information.</p>
    <p>If there is a configuration issue, fix the issue, and wait for the next retry by Async Client. If there is a data issue that you can’t resolve by modifying the database schema, cancel the session. For more information, see <a href="view-or-cancel-retail-data-distribution-sessions.md">View or cancel retail data distribution sessions</a>.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Download path</strong></p></td>
    <td><p>The working folder where data packages are created for download.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Rows affected</strong></p></td>
    <td><p>The number of rows in the database that are read from Microsoft Dynamics AX and sent to the channel.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Row version</strong></p></td>
    <td><p>The version number that is assigned by Microsoft SQL Server change tracking.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Date and time created</strong></p></td>
    <td><p>The date and time when the data package was created.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Date and time modified</strong></p></td>
    <td><p>The date and time when the data package was last modified.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Message</strong></p></td>
    <td><p>If there was an error, the detailed error message text.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Channel database</strong></p></td>
    <td><p>The channel database that the data package was applied to.</p></td>
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
    </tbody>
    </table>


4.  To repeat a failed session, select it, and then click **Rerun**.

## See also

[View or cancel retail data distribution sessions](view-or-cancel-retail-data-distribution-sessions.md)

  


