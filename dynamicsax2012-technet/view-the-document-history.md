---
title: View the document history
TOCTitle: View the document history
ms:assetid: ad9b57ee-2d9f-4a49-a831-7b7ff6c33db6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa834426(v=AX.60)
ms:contentKeyID: 35132806
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# View the document history 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Documents that are exchanged by using Application Integration Framework (AIF) are related to data in the Microsoft Dynamics AX database, such as a sales order. To exchange documents and data with external systems, AIF creates a message that contains header information and data.

You can view information about documents and messages in the AIF **History** form. If you select **Message** in the **Display by** field, you see only information about the message. If you select **Document** in the **Display by** field, you see both information about the message and information about the underlying document, such as the entity key.

Information about messages and the document history are organized by the service operation for each port. You can set the parameters for logging when you configure the troubleshooting options for ports.

## View the general document history

1.  Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **History**.

2.  In the **Display by** field, you can filter the display by selecting either **Message** or **Document**.
    
      - If you select **Message**, you see the following information about the message: the port, service operation, message ID, company accounts ID, and date and time that the message was created.
    
      - If you select **Document**, you see both the information about the message, and the form name and entity key for the document.

3.  Click the **General** tab to view the ID of the message set.

4.  Click the **Details** tab to view the following information:
    
      - The direction of the message: inbound or outbound.
    
      - The ID of the pipeline, if there is a pipeline.
    
      - The Microsoft Dynamics AX user who is associated with the port, and the submitting user. The submitting user is the user who is associated with the process that submitted the message. The submitting user is either the Microsoft Dynamics AX user who submitted the message for the port or a trusted intermediary.
    
      - For outbound documents that are sent in response to read requests, the message ID for the original request.
    
      - Address details, such as the adapter and URI that were used for the exchange.
    
      - The partition key that identifies the partition for which the message is intended.

5.  Click **Correlation** to view the database record that corresponds to the message.

6.  Click **Document logs** to view the XML code for each version of the document as the document is transformed by each component in the pipeline.

7.  Click **Clear document XML** to clear all or some of the XML code for any version of the document that currently exists in the system.

## View the data in a document for a message

1.  Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **History**.

2.  In the **Display by** field, select **Message**.

3.  Select a message, and then click **Correlation**.

4.  In the **Document correlation** form, view the form name, table name, and entity key for the database record that is contained in the selected message. You can also view a record for each numbered version of the document and the related processing steps.

5.  Click **View** to display the data in the default form for the document.

## Delete a message

When you delete a message by using the **History** form, you delete that message from the AifMessageLog table.

1.  Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **History**.

2.  In the **Display by** field, select **Message**.

3.  Press ALT+F9 to delete the record from the document history.

## Clear the document XML

1.  Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **History**.

2.  In the **Display by** field, select **Document**.

3.  Select a document, and then click **Clear document XML**.

4.  To clear all the versions of the XML document that exist in the system, click **Clear all versions**.

5.  To clear all intermediate versions of the XML document, click **Clear interim versions**. For outbound documents, this action clears all versions except the version that has the highest version number. For inbound documents, this action clears all versions except the first version.

