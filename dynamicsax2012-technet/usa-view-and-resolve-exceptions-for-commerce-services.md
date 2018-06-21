---
title: (USA) View and resolve exceptions for Commerce Services
TOCTitle: (USA) View and resolve exceptions for Commerce Services
ms:assetid: fe471199-3571-491b-996d-3ae6af28db67
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227587(v=AX.60)
ms:contentKeyID: 36060115
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (USA) View and resolve exceptions for Commerce Services [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can view and resolve exceptions in Microsoft Dynamics AX that occur when you use Commerce Services for Microsoft Dynamics ERP. The **Exceptions** form lists the errors that have occurred during Commerce Services operations.


> [!NOTE]
> <P>This feature is not available if Microsoft Dynamics AX 2012 R3 is installed.</P>



1.  Click **Organization administration** \> **Setup** \> **Commerce Services** \> **Exceptions**.

2.  Use the information on the form to help resolve any errors. The following table lists some common exceptions.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Exception</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Another instance of the job is already running.</p></td>
    <td><p>Too many jobs are running at the same time. Suspend all Commerce Services jobs, and then restart the job that you want.</p></td>
    </tr>
    <tr class="even">
    <td><p>Complete data synchronization was cancelled due to conflicting jobs.</p></td>
    <td><p>Too many jobs are running at the same time. Suspend all Commerce Services jobs, and then restart the Commerce Services complete data synchronization job.</p></td>
    </tr>
    <tr class="odd">
    <td><p>A network error occurred and the page could not be displayed.</p></td>
    <td><p>This exception occurs most often when an Internet connection is missing. Ensure that the computer has a working Internet connection and that any other network connections are working properly.</p></td>
    </tr>
    <tr class="even">
    <td><p>Commerce Services cannot be activated since change tracking is not enabled.</p></td>
    <td><p>Change tracking must be enabled on the computer. Contact your system administrator to enable change tracking.</p></td>
    </tr>
    <tr class="odd">
    <td><p>The service is being set up.</p></td>
    <td><p>Setting up Commerce Services can take up to 24 hours. Try again after this time has passed.</p></td>
    </tr>
    <tr class="even">
    <td><p>A complete synchronization is required to upload the changes.</p></td>
    <td><p>In Microsoft Dynamics AX, whenever you select products to sell online, you must then run the Commerce Services complete data synchronization job.</p>
    <p>Note that this job can take time to finish, depending on the number of products that you select.</p></td>
    </tr>
    </tbody>
    </table>


## See also

[AIF exceptions (form)](https://technet.microsoft.com/en-us/library/aa587119\(v=ax.60\))

[(USA) Use logging to troubleshoot Commerce Services](usa-use-logging-to-troubleshoot-commerce-services.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

