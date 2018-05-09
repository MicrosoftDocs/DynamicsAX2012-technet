---
title: 'How to: Import Pages into the AOT'
TOCTitle: 'How to: Import Pages into the AOT'
ms:assetid: a7861d47-e9ef-4742-8661-036156113c86
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc616468(v=AX.60)
ms:contentKeyID: 35245593
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# How to: Import Pages into the AOT 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If a page in Enterprise Portal will be packaged and distributed to other Enterprise Portal installations, a copy of the page definition must be imported from SharePoint into the AOT. From the AOT, the page can be packaged for distribution to other Enterprise Portal installations.

## Importing a Page into the AOT

After a page has a URL Web Menu Item defined that points to it, the page can be imported into the AOT. For details about how to create a URL Web Menu Item for a page, see [How to: Add Pages to Navigation](https://technet.microsoft.com/en-us/library/cc600786\(v=ax.60\)).

### To import a page into the AOT

1.  In the AOT, expand the **Web** node, and then expand the **Web Menu Items** node.

2.  Expand the **URLs** node and locate the URL for the page that you want to import into the AOT.

3.  Right-click the node and then click **Import Page**. A copy of the page definition will be imported into the AOT. The page definition will appear as a node in the **Web** \> **Web Files** \> **Page Definitions** section of the AOT.

Whenever you use SharePoint to make updates to a page, such as adding or removing web parts, you must re-import the page into the AOT.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

