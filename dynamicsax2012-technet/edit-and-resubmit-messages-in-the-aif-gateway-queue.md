---
title: Edit and resubmit messages in the AIF gateway queue
TOCTitle: Edit and resubmit messages in the AIF gateway queue
ms:assetid: 4b1a3ef7-1fc9-4fb8-8c8e-9d4a0913b72b
ms:mtpsurl: https://technet.microsoft.com/library/Aa834355(v=AX.60)
ms:contentKeyID: 35132623
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Edit and resubmit messages in the AIF gateway queue 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Queue manager** form displays information about messages in the Application Integration Framework (AIF) queues. This information includes the status of each message. The following statuses are used:

  - **Ready**

  - **In process** – This status is used for inbound messages only.

  - **Hold**

  - **Error**

  - **In transport process** – This status is used for outbound messages only.

  - **Malformed XML**

If the status of a message is set to **Ready**, you can change the status to **Hold**. If the status is set to **Hold**, you can change it to **Ready**. If the status is set to **Error** or **Hold**, you can delete or modify the message.

## View the message status and details

To view the status of a message and other details, follow these steps.

1.  Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **Queue manager**.

2.  On the **Overview** tab, view the port name, message ID, direction, status, company accounts ID, service operation, and any error message that is associated with the message.

3.  On the **Details** tab, view information about the submitting user, the ID of the Microsoft Dynamics AX user who is associated with the port, and the date and time that the message was created.

4.  Click **Refresh** to update the information.

5.  Click **Document log** to view information about the document that is contained in the message. The information that is displayed varies, depending on the logging options that were set for the port.

## Delete a message

If a message remains unprocessed in the AIF queues, you can delete it in the **Queue manager** form.

1.  Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **Queue manager**.

2.  Press ALT+F9 to delete the message.
    
    You can delete the message only if the value in the **Status** field is **Error**, **Malformed XML**, or **Hold**.

## Modify and resubmit a message

If a message enters the queue but cannot be processed because of an error, you may be able to modify and resubmit the message. To resubmit a message, follow these steps.

1.  If the status of the message is **Error** or **Hold**, click **View message** to view the message. Then enter a file name and path, and save the message to an XML file.

2.  Open the file that you just saved in any XML editor, and then modify the file to correct the field or fields that have errors.

3.  Click **Import message** to import the file.

4.  Change the status of the message from **Error** or **Hold** to **Ready**. The queue can now start to process the message. Note that for message sets, changing the status changes the status for all messages in the message set.

