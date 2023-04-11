---
title: Set up Microsoft Outlook or Exchange Server integration
TOCTitle: Set up Microsoft Outlook or Exchange Server integration
ms:assetid: 8a79817f-783a-4928-94d1-7299ac9579dd
ms:mtpsurl: https://technet.microsoft.com/library/Aa498242(v=AX.60)
ms:contentKeyID: 36058466
author: tonyafehr
ms.date: 12/10/2014
mtps_version: v=AX.60
f1_keywords:
- integration
- microsoft outlook
audience: Application User
ms.search.region: Global
---

# Set up Microsoft Outlook or Exchange Server integration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before users can integrate Microsoft Outlook or Microsoft Exchange Server with Microsoft Dynamics AX on a client computer, they must be granted access to the COM+ Service. When Microsoft Dynamics AX is installed on the client computer, the user who installed the program is automatically granted access to the COM+ Service, but other users must be added manually.

Before you can integrate the two programs for a user, you must add each user of that client computer who plans to enable the integration of Outlook or Exchange Server with Microsoft Dynamics AX to the COM+ Service.

Support for integration with Microsoft Exchange Server is available only in AX 2012 R3 Cumulative Update 8 and later.

## Add a user to the COM+ Service

1.  Click **Start** \> **Administrative tools**, and then double-click **Component services**.

2.  On the **Component services** page, expand the nodes **Computers** \> **My computer** \> **COM+ Applications**.

3.  Locate and expand either the **DynamicsMAPI** node or the **DynamicsMAPI32** node.

4.  Right-click **Roles**, and then click **New** \> **Role**.

5.  Enter a role name, such as **Non-admin** or **Other users**, for the users whom you are adding to the COM+ Service, and then click **OK**.

6.  Expand the role that you created, right-click the **Users** folder, and then click **New** \> **User**.

7.  Enter the names of the users whom you are adding to the COM+ Service, and then click **Check Names** to validate the names that you entered.

8.  After you enter all of the user names, close the window, and then restart Microsoft Dynamics AX.

## Set up Microsoft Outlook integration

Every user who wants to integrate Microsoft Dynamics AX and Microsoft Outlook must complete this procedure.

1.  Click **Home** \> **Setup** \> **Microsoft Outlook setup wizard**.

2.  Click **Next \>**.

3.  On the **Employee setup** page, verify that the worker name and user ID are correct, and then click **Next \>**.

4.  On the **Microsoft Outlook synchronization** page, click **Use current Microsoft Outlook profile** to select the user ID and the contact, task, and calendar folders from your Outlook profile.
    
    If you want to select different contact, task, and calendar folders, click the corresponding buttons.

5.  To select another folder, click **Pick contact Microsoft Outlook folder**, **Pick task Microsoft Outlook folder**, or **Pick appointment Microsoft Outlook folder**.
    
    To clear the selected folders, click **Clear Microsoft Outlook folders**.

6.  Enter the number of days before the current date and after the current date for which you want to synchronize Outlook appointments and tasks.

7.  Click **Next \>**, and then click **Finish**.

## Set up Outlook or Exchange Server integration in AX 2012 R3 CU8

Support for integration with Microsoft Exchange Server is available only in AX 2012 R3 Cumulative Update 8 and later.

Every user who wants to integrate Microsoft Dynamics AX and Microsoft Outlook must complete this procedure.

1.  Click **Home** \> **Setup** \> **Microsoft Outlook setup wizard**.

2.  Click **Next \>**.

3.  On the **Employee setup** page, verify that the worker name and user ID are correct.

4.  If your legal entity is using Exchange Server instead of Outlook, enter the URL of the Exchange Server implementation, and your logon ID and password. These are typically the credentials that you use to log on to your email.

5.  Click **Next \>**.

6.  On the **Microsoft Outlook or Exchange Server synchronization** page, click **Use current profile** to select the user ID and the contact, task, and calendar folders from your Outlook or Exchange Server profile.
    
    If you want to select different contact, task, and calendar folders, click the corresponding buttons.

7.  To select another folder, click **Pick contact folder**, **Pick task folder**, or **Pick appointment folder**.
    
    To clear the selected folders, click **Clear folders**.

8.  Enter the number of days before the current date and after the current date for which you want to synchronize Outlook or Exchange Server appointments and tasks.

9.  Click **Next \>**, and then click **Finish**.

## See also

[My contacts (form)](https://technet.microsoft.com/library/aa554281\(v=ax.60\))

[Select the Microsoft Outlook or Exchange Server items to synchronize (form)](https://technet.microsoft.com/library/aa598437\(v=ax.60\))

  


