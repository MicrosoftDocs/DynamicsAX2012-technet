---
title: 'Walkthrough: Exchanging documents by using the MSMQ adapter'
TOCTitle: 'Walkthrough: Exchanging documents by using the MSMQ adapter'
ms:assetid: 264e7695-3dfe-4d3f-a64d-bd84360da6a8
ms:mtpsurl: https://technet.microsoft.com/library/Hh496417(v=AX.60)
ms:contentKeyID: 37071994
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Walkthrough: Exchanging documents by using the MSMQ adapter 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The MSMQ adapter enables asynchronous communication by using the Message Queuing transport. This walkthrough demonstrates how to use an inbound port together with the MSMQ adapter to create a sales order in Microsoft Dynamics AX. In this walkthrough, you create an inbound integration port, and then use C\# code to create a command-line program that sends an XML document to a message queue.


> [!NOTE]
> <P>This walkthrough does not demonstrate how to work with security settings, such as those that restrict an exchange to a particular company or partition. For more information about security settings, see <A href="configure-security-for-integration-ports.md">Configure security for integration ports</A>.</P>



## Prerequisites

  - You must deploy Message Queuing. See [Deploy Message Queuing for AIF](deploy-message-queuing-for-aif.md).

  - Microsoft Dynamics AX must be preconfigured to accept sales orders. For example, the system must contain at least one customer and one released product, and the minimum related requirements for accounting and inventory tracking must be met.

  - The sales order service must be registered. For information about how to register services, see [Customize service contracts](customize-service-contracts.md).

  - Microsoft Visual Studio 2010 must be installed, and you must know how to create a simple Visual C\# project.

## Create a queue

Create a new public queue that is named CreateSO.

1.  Open Server Manager.

2.  In the console tree, expand **Features** \> **Message Queuing**.

3.  Right-click the **Public Queues** folder, point to **New**, and then click **Public Queue**. The **New Object – Public Queue** dialog box opens.

4.  Name the new queue **CreateSO**.

5.  Select the **Transactional** check box.

6.  Click **Ok** to close the dialog box.

7.  Wait for the queue to appear in Server Manager. The queue may not appear immediately.

8.  Right-click the queue, and then click **Properties**.

9.  Select the **Authenticated** check box.

10. On the **Security** tab, verify that the user account for Application Object Server (AOS) has read-write access to the queue.

11. Click **Ok** to close the dialog box.

For more information about how to configure permissions for the queue, see the "Configure a queue for sending or receiving documents" section in [Deploy Message Queuing for AIF](deploy-message-queuing-for-aif.md).

## Create and configure the integration port

The inbound integration port receives the sales order messages.

1.  Open the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  Click **New**.

3.  Name the new integration port **MSMQSalesOrderCreate**.

4.  In the **Address** group, in the **Adapter** list, select **MSMQ**.

5.  On the **Service contract customizations** FastTab, click **Service operations**.

6.  In the **Select service operations** form, in the **Remaining service operations** list, select **SalesSalesOrderService.create**. Click the left arrow button to move the service operation to the **Selected service operations** list. Then close the form.

7.  In the **URI** field, click the arrow. The **Configure MSMQ** form opens.

8.  In the **Queue name** list, select the CreateSO queue. Then close the form.
    
    If the queue does not appear in the list, click **Find queues** to update the list.

9.  On the **Service contract customizations** FastTab, select **Customize documents**, and then click **Data policies**.

10. In the **Document data policies** form, sort the table by the **Element name** column, and then select **Enabled** for the following elements:
    
      - **CustAccount** (/SalesOrder/SalesTable/CustAccount)
    
      - **ItemId** (/SalesOrder/SalesTable/SalesLine/ItemId)

11. Activate the integration port.

12. Close the **Inbound ports** form.

## Configure and start the AIF batch services

For asynchronous document exchanges, such as the exchange that is demonstrated in this walkthrough, you must configure a batch job for Application Integration Framework (AIF). This batch job periodically runs business logic through integration ports that are configured to use asynchronous adapters. If you have previously configured the AIF batch services, you can skip this section.

1.  Open the **Batch job** form. Click **System administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

2.  Create a new batch job.

3.  Add four tasks, each of which uses one of the following classes: **AifGatewayReceiveService**, **AifGatewaySendService**, **AifInboundProcessingService**, and **AifOutboundProcessingService**.

4.  Set a recurrence interval for the batch job. For testing, we recommend that you set the interval to 1 minute.

5.  To start the batch job, change its status to **Waiting**.

## Create the document for the sales order request

The sales order request is an XML-based document. For this example, you use a sales order request that complies with the sales order schema. The request document uses the AIF message schema as an envelope to contain the sales order request.

1.  Copy the following XML code into an empty Notepad document.
    
        <?xml version="1.0" encoding="utf-8" ?>
        <Envelope xmlns="https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
        <Header>
          <MessageId>{944EBD21-50ED-41BF-B779-2DC90F00F350}</MessageId>
          <Action>https://schemas.microsoft.com/dynamics/2008/01/services/SalesOrderService/create</Action>
        </Header>
          <Body>
            <MessageParts>
              <SalesOrder xmlns="https://schemas.microsoft.com/dynamics/2008/01/documents/SalesOrder">
                <SalesTable class="entity">
                  <CustAccount>100002</CustAccount>
                  <DeliveryDate>2011-10-11</DeliveryDate>
                  <PurchOrderFormNum>PO</PurchOrderFormNum>
                  <ReceiptDateRequested>2011-11-11</ReceiptDateRequested>
                  <SalesLine class="entity">
                    <ItemId>10003</ItemId>
                    <SalesQty>18</SalesQty>
                    <SalesUnit>Pcs</SalesUnit>
                  </SalesLine>
                </SalesTable>
              </SalesOrder>
            </MessageParts>
          </Body>
        </Envelope>

2.  The XML code includes an element that is named \<MessageId\>. This element contains a GUID that uniquely identifies the message. You must provide a new, unique GUID for each message that you send to AIF.

3.  Replace the values in the document with valid values for your Microsoft Dynamics AX environment. For example, replace the values for \<CustAccount\> and \<ItemId\>.

4.  Save the file as SOCreate.xml. For this walkthrough, we recommend that you save this file to the root directory, C:.

## Create a Message Queuing client application

This section describes how to create a simple client application that sends a message to a queue. The code for the client application is written in the C\# programming language. The sample application creates an XML document object by reading the file that you saved in the previous section. The sample application then sends the document object to the message queue.

1.  Open Visual Studio, and create a new console application project in Visual C\#. Name the project **MSMQ Client**.

2.  In **Solution Explorer**, right-click the project name, and then click **Add Reference**.

3.  On the **.NET** tab, select **System.Messaging**, and then click **OK**.

4.  Open Program.cs. In the code editor, add the following using statements.
    
        using System.Messaging;
        using System.Xml;

5.  Replace the empty Main function with the following C\# code.
    
        static void Main(string[] args)
        {
          
            // The queue name.
            // Replace this AOS name and queue name with the values from 
            // the URI field in the Inbound ports form. 
            // For this walkthrough, 
            // only the server name should be different.
            String QName = "FormatName:DIRECT=OS:MYSERVER\\CreateSO";
            // The path to the sales order XML file
            String XMLPath = "c:\\Create.xml";
        
            // Create the XML document object.
            XmlDocument doc = new XmlDocument();
            doc.Load(XMLPath);
        
            // Create a new message.
            Message msg = new Message();
        
            // Add authentication.
            msg.AttachSenderId = true;
            msg.UseAuthentication = true;
            msg.HashAlgorithm = HashAlgorithm.Sha;
        
            // Attach the document to the message.
            msg.Body = doc;    
        
            // Create the queue object.
            MessageQueue myQ = new MessageQueue(QName);
        
            try
            {
                // Send a message to the queue
                // Create a transaction.
                MessageQueueTransaction myTransaction = new MessageQueueTransaction();
        
                // Begin the transaction
                myTransaction.Begin();
        
                // Send the message
                myQ.Send(msg, "Sales Order", myTransaction);
        
                // End the transaction
                myTransaction.Commit();
            }
            catch (Exception e)
            {
                // Display the description of the exception
                Console.WriteLine(e.Message);
            }  
        
            Console.Write("Done. Press ENTER to continue.");
            Console.In.ReadLine();
        }

6.  Build the project.

## Send the request

To send the sales order request, run the client application.

1.  In Windows, open a Command Prompt window.

2.  At the command prompt, run the MSMQ client application.

When the application has finished running, the message has been sent to the queue. The batch job retrieves the message from the queue and processes it through the inbound integration port that you created. Processing can require some time. To verify that the sales order was created, view the **All sales orders** form. To check for errors, view the **Exceptions** log.

## See also

[Configuring batch jobs and tasks for AIF](configuring-batch-jobs-and-tasks-for-aif.md)

[Managing integration ports](managing-integration-ports.md)

[Walkthrough: Transforming a document](walkthrough-transforming-a-document.md)

