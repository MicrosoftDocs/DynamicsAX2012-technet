---
title: Create or modify a security privilege, duty, or process cycle
TOCTitle: Create or modify a security privilege, duty, or process cycle
ms:assetid: f2ca438f-1e4e-44bb-9e1e-087c70065ce9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh556870(v=AX.60)
ms:contentKeyID: 39509604
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Create or modify a security privilege, duty, or process cycle [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If the security privileges, duties, and process cycles that are provided with Microsoft Dynamics AX do not meet the requirements of your business, you can create new privileges, duties, and process cycles.


> [!TIP]
> <P>Security is organized hierarchically. Permissions on specific application elements are combined into privileges, privileges are combined into duties, and duties are grouped into process cycles. You can assign either duties or privileges to roles. For more information about the security hierarchy, see <A href="security-architecture-of-the-microsoft-dynamics-ax-application.md">Security architecture of the Microsoft Dynamics AX application</A>.</P>



Only the Microsoft Dynamics AX administrator can create or modify a security privilege, duty, or process cycle.

For information about how privileges, duties, and process cycles are used in the security model for Microsoft Dynamics AX, see [Role-based security in Microsoft Dynamics AX](role-based-security-in-microsoft-dynamics-ax.md).

## Create or modify a security privilege or duty

1.  Click **System administration** \> **Setup** \> **Security** \> **Security privileges**.

2.  To create a new privilege, select the duty that the privilege must belong to, and then click **New**.
    
    To create a new duty, select the process cycle that the duty must belong to, and then click **New**.
    
    To modify an existing privilege or duty, select the privilege or duty.

3.  If you are creating a new privilege or duty, enter the name that appears for the privilege or duty in the Application Object Tree (AOT).
    

    > [!NOTE]
    > <P>AOT names can contain only alphanumeric characters and underscore characters (_). AOT names cannot begin with a number, and they cannot contain special characters or spaces.</P>



4.  Enter or modify the display name of the privilege or duty.

5.  Enter or modify the description of the privilege or duty.

6.  Add or modify the content of the privilege or duty.
    
      - To add an existing privilege to a duty, right-click the privilege in the left pane, and then click **Copy**. Right-click the duty, and then click **Paste**.
    
      - To remove a privilege from a duty, right-click the privilege in the left pane, and then click **Delete**. To remove a permission from a duty or privilege, select the permission in the central pane, and then click **Remove**.
    
      - To add permissions to a duty or privilege, click **Add...** to open the **Add permissions to privilege** form. Find the security permissions to add. You can sort the permissions by the location of the entry points on the main menu or by process cycle. If you sort by process cycle, you can also enter the permission name or keywords in the **Find** field.

7.  When you have finished modifying the privilege or duty, click **Close** in the **Security privileges** form.

## Create or modify a process cycle

1.  Click **System administration** \> **Setup** \> **Security** \> **Security privileges**.

2.  To create a new process cycle, select the **Process cycles** node in the left pane, and then click **New**.
    
    To modify an existing process cycle, select the process cycle.

3.  If you are creating a new process cycle, enter the name that appears for the process cycle in the AOT.
    

    > [!NOTE]
    > <P>AOT names can contain only alphanumeric characters and underscore characters (_). AOT names cannot begin with a number, and they cannot contain special characters or spaces.</P>



4.  Enter or modify the display name of the process cycle.

5.  Enter or modify the description of the process cycle.

6.  Add or modify the content of the process cycle.
    
      - To add an existing duty or privilege to a process cycle, right-click the duty or privilege in the left pane, and then click **Copy**. Right-click the process cycle, and then click **Paste**.
    
      - To remove a duty or privilege from a process cycle, right-click the duty or privilege in the left pane, and then click **Delete**.

7.  When you have finished modifying the process cycle, click **Close** in the **Security privileges** form.

## See also

[Security privileges (form)](https://technet.microsoft.com/en-us/library/hh209366\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

