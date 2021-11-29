---
title: 'How to: Create a Role Center'
TOCTitle: 'How to: Create a Role Center'
ms:assetid: 9d7a664e-ad1c-48c5-bc2c-c430599f142f
ms:mtpsurl: https://technet.microsoft.com/library/JJ945384(v=AX.60)
ms:contentKeyID: 51442776
author: Khairunj
ms.date: 02/13/2013
mtps_version: v=AX.60
---

# How to: Create a Role Center 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2_

You can create a role center page for Microsoft Dynamics AX and add the page definition to the AOT so that you can later deploy it to other Enterprise Portal installations.

## Creating a Role Center Page

You can create a role center page for Microsoft Dynamics AX. For more information, see [Role Center Page Reference](https://technet.microsoft.com/library/cc558235\(v=ax.60\)).

### To create a role center page

1.  In Enterprise Portal, create a page that will be used as the role center page. This page should be added in the Enterprise Portal library of the Home site for the Enterprise Portal installation. For more information, see [How to: Create Pages](https://technet.microsoft.com/library/cc585929\(v=ax.60\)).

2.  Create a URL web menu item that points to the new role center page. This web menu item is used when navigating to the role center page. For instance, a web menu item name EPSampleRoleCenter would point to the RoleCenterSample.aspx page. For more information about how to create URL web menu items, see [How to: Add Pages to Navigation](https://technet.microsoft.com/library/cc600786\(v=ax.60\)).

3.  Set the **Label** property for the new URL web menu item to Role Center.

4.  Set the **HomePage** property for the new URL web menu item to Yes. This specifies that the page is a role center. It will appear in the **User profiles** window in Microsoft Dynamics AX with the other role center pages.

## Importing the Role Center Page into the AOT

If a page in Enterprise Portal will be packaged and distributed to other Enterprise Portal installations, a copy of the page definition must be imported from SharePoint into the AOT. From the AOT, the page can be packaged for distribution to other Enterprise Portal installations. For more information, see [How to: Import Pages into the AOT](how-to-import-pages-into-the-aot.md).

