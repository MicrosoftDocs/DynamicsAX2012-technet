---
title: Specify options for Microsoft Project integration
TOCTitle: Specify options for Microsoft Project integration
ms:assetid: 7bb3f5b9-7b6c-484c-9b1d-99626062b08f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn479195(v=AX.60)
ms:contentKeyID: 59633710
ms.date: 04/23/2014
mtps_version: v=AX.60
---

# Specify options for Microsoft Project integration [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Project managers in your legal entity can link projects in Microsoft Dynamics AX 2012 R2 to Microsoft Project, where they can manage the work breakdown structure and worker assignments for projects in more detail. Before you can create the link, you must specify options for how Microsoft Project files are managed. These options include whether Microsoft Project MPP files are created and maintained in a local or network folder, or in a Microsoft Project Server implementation.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**.

2.  In the left pane, click **General**.

3.  In the **Save Microsoft Project files to** field, choose one of the following storage types:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Type</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Archive directory</strong></p></td>
    <td><p>A local or network folder that is available to all project managers who will integrate projects with Microsoft Project.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>SharePoint</strong></p></td>
    <td><p>A collaboration workspace that is set up in Microsoft SharePoint Server 2010 or Microsoft SharePoint Server 2013.</p>
    <p>Tasks can be synchronized with Microsoft Dynamics AX only if you are using SharePoint Online.</p></td>
    </tr>
    </tbody>
    </table>


4.  Depending on the selection you made in step 3, do one of the following:
    
      - If you selected **Archive directory**: In the **Folder for Microsoft Project files** field, enter the local or network folder where Microsoft Project MPP files will be stored.
    
      - If you selected **SharePoint**: Click the **Set up collaboration workspace** link, and then set up the collaboration workspace in SharePoint Server where Microsoft Project MPP files will be stored.
        
        For information about setting up collaboration workspaces, see [Select preferences for collaboration workspaces](select-preferences-for-collaboration-workspaces.md).

## See also

[Collaboration workspace settings (form)](https://technet.microsoft.com/en-us/library/hh242783\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

