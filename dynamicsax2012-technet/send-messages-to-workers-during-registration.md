---
title: Send messages to workers during registration
TOCTitle: Send messages to workers during registration
ms:assetid: bab8b6db-f7f9-437c-9227-31fbfacb5045
ms:mtpsurl: https://technet.microsoft.com/library/Aa498857(v=AX.60)
ms:contentKeyID: 36059128
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Send messages to workers during registration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you are a supervisor or manager, you can send messages that are displayed in the **Job registration** form to workers who are using the form to log on. When you send messages, consider the following:

  - You can send a message to specific workers or to specific terminals.

  - The message will be visible when workers log on to the **Job registration** form. The message is not displayed when workers log off.

  - When you send a message to a specific worker, you can require the worker to confirm that he or she has read the message.

  - An icon is displayed with the message to indicate whether the message is for information only, important, or urgent.

## Create a message to all workers

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Handle messages**.

2.  Press CTRL+N to create a line.

3.  In the **Subject** field, enter the heading of the message.

4.  In the **From time** and **To time** fields, enter the time period when the message will be visible to the recipients.

5.  Select the **Public message** check box to send the message to all workers who log on to the **Job registration** form.

6.  In the **Message type** field, select the level of importance for the message.

7.  In the **Information** field, enter the message text.

8.  Click **Close**.

## Send a message to selected workers or terminals

When you send a message to selected workers, the message will be displayed only when the workers log on to the **Job registration** form. If you send a message to selected terminals, the message is displayed only when a worker logs on to one of the selected terminals.

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Handle messages**.

2.  Press CTRL+N to create a line.

3.  In the **Subject** field, enter the heading of the message.

4.  In the **From time** and **To time** fields, enter the time period when the message will be visible to the recipients.

5.  Select the **Receipt** check box to receive a notification that the worker has read the message.
    
    When the worker confirms the message as having been read, the **Read** check box on the **Workers** tab of the **Recipients** tab will be selected.

6.  In the **Message type** field, select the level of importance for the message.

7.  In the **Information** field, enter the message text.

8.  Press CTRL+S to save the message.

9.  On the **Recipients** tab, select the workers or terminals to send the message to. You can select recipients individually or by creating queries.
    
    To select the recipients individually:
    
    1.  Click the **Workers** tab to add workers, or the **Terminals** tab to add terminals.
    
    2.  Click the **Select workers** or **Select terminals** buttons to add a worker or terminal to the list.
    
    3.  Select the worker in the **Worker** field. The name of the worker is displayed in the **Name** field.
        
        –or–
        
        Select the terminal in the **Terminal** field. The description of the terminal is displayed in the **Description** field.
    
    4.  Repeat these steps to add more recipients.
    
    5.  Close the form when you have added all the recipients.
    
    To select the recipients by creating a query:
    
    1.  On the **Recipients** tab, click **Select workers** to create a query for workers or **Select terminals** to create a query for terminals.
    
    2.  Select the criteria for the query. For more information about the **Inquiry** form, see [Inquiry (form)](https://technet.microsoft.com/library/aa575929\(v=ax.60\)).
    
    3.  Repeat these steps to add more recipients to the list.
    
    4.  Close the form when you have added all the recipients.

## See also

[Inquiry (form)](https://technet.microsoft.com/library/aa575929\(v=ax.60\))

  


