---
title: 'Checklist: Deploy Enterprise Portal changes to a different server'
TOCTitle: 'Checklist: Deploy Enterprise Portal changes to a different server'
ms:assetid: f107320f-e45b-4514-9e1e-c08f569b719b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352329(v=AX.60)
ms:contentKeyID: 36687959
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Checklist: Deploy Enterprise Portal changes to a different server [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following checklist can help you deploy changes from one Enterprise Portal server to a different server. Changes can include updates to Enterprise Portal objects in the Application Object Tree (AOT), updates to SharePoint Web Parts, or the transfer of a whole Enterprise Portal site to a different server. The checklist includes links to procedure topics that contain the step-by-step instructions to complete a task.

## Checklist for deploying Enterprise Portal changes to a different server

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>For more information, see…</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>If you changed Enterprise Portal pages, you must import a copy of the page definition from SharePoint into the Application Object Tree (AOT). From the AOT, the page can be packaged for distribution to other Enterprise Portal installations.</p></td>
<td><p><a href="how-to-import-pages-into-the-aot.md">How to: Import Pages into the AOT</a></p></td>
</tr>
<tr class="even">
<td><p>Export the changes from the AOT, so that they can be distributed to other Enterprise Portal installations.</p></td>
<td><p><a href="how-to-export-application-objects-by-using-the-aot.md">How to: Export Application Objects by Using the AOT</a></p></td>
</tr>
<tr class="odd">
<td><p>Import the changes to the AOT on the new server.</p></td>
<td><p><a href="how-to-import-application-objects-by-using-the-aot.md">How to: Import Application Objects by Using the AOT</a></p></td>
</tr>
<tr class="even">
<td><p>Right-click the AOT project and then click <strong>Deploy to EP</strong>. Or, use the AxUpdatePortal.exe utility to update the web-related items from the AOT.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/dd261467(v=ax.60)">AxUpdatePortal Utility</a></p></td>
</tr>
</tbody>
</table>



> [!IMPORTANT]
> <P>If you made significant changes to a site and you want to deploy the whole site to a new server, see <A href="move-an-enterprise-portal-deployment-to-a-different-server.md">Move an Enterprise Portal deployment to a different server</A>.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

