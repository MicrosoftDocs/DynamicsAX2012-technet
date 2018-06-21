---
title: (USA) View and resolve exceptions for Sites Services
TOCTitle: (USA) View and resolve exceptions for Sites Services
ms:assetid: 67287dbf-81aa-4f3a-b75f-23071c2fff11
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242590(v=AX.60)
ms:contentKeyID: 36057940
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (USA) View and resolve exceptions for Sites Services [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can view and resolve exceptions in Microsoft Dynamics AX that occur when you use Sites Services for Microsoft Dynamics ERP. The **Exceptions** form lists the errors that have occurred during Sites Services operations.

1.  Click **Organization administration** \> **Setup** \> **Sites Services** \> **Exceptions**.

2.  Use the information on the form to help resolve any errors. The following table describes some common exceptions.
    
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
    <td><p>An error occurred downloading &lt;entity&gt; for &lt;solution&gt;.</p></td>
    <td><p>To identify the fields with errors, click <strong>Show details</strong>. To resolve errors, click <strong>Resolve</strong>, specify values for the fields, click <strong>Submit</strong>, and then check after the next synchronization.</p></td>
    </tr>
    <tr class="even">
    <td><p>A conflict error occurred for &lt;entity&gt; for &lt;solution&gt;.</p></td>
    <td><p>An record published online is out of synchronization with the corresponding record in Microsoft Dynamics AX.</p>
    <p>To specify the field value to override, click <strong>Show details</strong>, and then on the error reference form, identify the error and make a note of it. In Microsoft Dynamics AX, correct the erroneous record, and then return to the error message and click <strong>Resolve</strong> to indicate that the record can be synchronized at the next scheduled synchronization.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Schema is out of sync.</p></td>
    <td><p>A schema change, such as the addition of a new field, for a Sites Services solution was made in Microsoft Dynamics AX. You must update the solutions's structure with Sites Services.</p>
    <ol>
    <li><p>Click <strong>Organization administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Sites Services</strong> &gt; <strong>Available solutions</strong>.</p></li>
    <li><p>In the list of solutions on the left, select the solution, and then click <strong>Update</strong>.</p></li>
    </ol>
    <div class="alert">

    > [!NOTE]
    > <P>When you update the structure of a solution, all of the pages in the solution are deleted. You must then create new pages for the solution.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p>A network error occurred and the page could not be displayed.</p></td>
    <td><p>This exception occurs most often when the Internet connection is missing. Ensure that the computer has a working Internet connection and that any other network connections are working properly.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Sites Services cannot be activated since change tracking is not enabled.</p></td>
    <td><p>Change tracking must be enabled on the computer. Contact your system administrator to enable change tracking.</p></td>
    </tr>
    </tbody>
    </table>


## See also

[AIF exceptions (form)](https://technet.microsoft.com/en-us/library/aa587119\(v=ax.60\))

[(USA) Use logging for troubleshooting Sites Services](usa-use-logging-for-troubleshooting-sites-services.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

