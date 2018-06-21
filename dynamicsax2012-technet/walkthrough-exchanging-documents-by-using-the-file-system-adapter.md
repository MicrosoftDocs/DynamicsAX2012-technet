---
title: 'Walkthrough: Exchanging documents by using the file system adapter'
TOCTitle: 'Walkthrough: Exchanging documents by using the file system adapter'
ms:assetid: c121bfd3-7833-4f55-9944-45506c10559a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352313(v=AX.60)
ms:contentKeyID: 36687942
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Exchanging documents by using the file system adapter [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic demonstrates how to perform an asynchronous document exchange. In this scenario, a new sales order request is sent to AIF by using the file system adapter.


> [!NOTE]
> <P>This walkthrough does not demonstrate how to work with security settings, such as those that restrict an exchange to a particular company or partition. For more information about security settings, see <A href="configure-security-for-integration-ports.md">Configure security for integration ports</A>.</P>



## Prerequisites

  - Microsoft Dynamics AX must be preconfigured to accept sales orders. For example, the system must contain at least one customer and one released product, and the minimum related accounting and inventory tracking requirements must be in place.

  - The sales order service must be registered. For information about how to register services, see [Customize service contracts](customize-service-contracts.md).

## Create the file system directories

To enable the document exchange, you must create the following two folders:

  - A folder to contain the source document for the request. Name this folder AIFIn. This is the folder from which AIF will get the original sales order that is written in a custom schema.

  - A folder to receive the AIF response. Name this folder AIFOut.

## Create and configure the integration port

To receive a new sales order and provide a response message, you will use an inbound integration port. Follow these steps to create the port.

### Create a new inbound port

1.  Open the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  Click **New**.

3.  Name the new integration port SalesOrderCreate.

### Select and configure the file adapter and its address

1.  In the **Adapter** list in the **Address** group, select **File system adapter**.

2.  In the **URI** list, click the arrow to browse to the folder that you created, named AIFIn.

3.  Select the **Response address** check box and repeat steps 1 and 2. This time, in the **URI** list, provide the path to the folder that you created, named AIFOut.

### Select the service operation

1.  On the **Service contract customizations** FastTab, click **Service operations**.

2.  In the **Select service operations** form, select **SalesSalesOrderService.create** in the **Remaining service operations** list. Click the left arrow to move the service operation to the **Selected service operations** list.

3.  Close the form.

### Configure the data policies

1.  On the **Service contract customizations** FastTab, select **Customize documents** and then click **Data policies**.

2.  In the **Document data policies** form, sort the table on the **Element name** column and then select **Enabled** for the following elements:
    
      - **CustAccount** (/SalesOrder/SalesTable/CustAccount)
    
      - **ItemId** (/SalesOrder/SalesTable/SalesLine/ItemId)

3.  Close the form.

### Activate the port

1.  In the **Inbound ports** form, click **Activate**.

2.  Close the form.

## Configure and start the AIF batch services

For asynchronous document exchanges, such as the one demonstrated in this scenario, you must configure an AIF batch job. This batch job periodically executes business logic through integration ports that are configured to use asynchronous adapters. If you have previously configured the AIF batch services, you can skip this section.

### Create the batch job

1.  Open the **Batch job** form. Click **System administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

2.  Create a new batch job.

3.  Add four tasks that use the following classes to the batch job: **AifGatewayReceiveService**, **AifGatewaySendService**, **AifInboundProcessingService**, and **AifOutboundProcessingService**.

4.  Set a recurrence interval for the batch job. For testing purposes, it is convenient to set the interval to one minute.

5.  To start the batch job, change its status to **Waiting**.

## Send the sales order request

The sales order request is an XML-based document. For this example, you will use a sales order request that already complies with the sales order schema. The request document uses the AIF message schema as an envelope to contain the sales order request.

### Create the sales order request document

1.  Copy the following XML code into an empty Notepad document.
    
        <?xml version="1.0" encoding="utf-8" ?>
        <Envelope xmlns="http://schemas.microsoft.com/dynamics/2011/01/documents/Message">
        <Header>
          <MessageId>{5603D03A-4380-404D-9F27-738BE0FEA13E}</MessageId>
          <Action>http://schemas.microsoft.com/dynamics/2008/01/services/SalesOrderService/create</Action>
        </Header>
          <Body>
            <MessageParts>
              <SalesOrder xmlns="http://schemas.microsoft.com/dynamics/2008/01/documents/SalesOrder">
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

2.  The XML code includes an element titled \<MessageId\>, which contains a GUID. This GUID uniquely identifies the message. You must provide a new, unique GUID for each message that you send to AIF.

3.  Replace the values in the document with valid values for your Microsoft Dynamics AX environment. For example, you will probably need to replace the values for \<CustAccount\> and \<ItemId\>.

4.  Save the file. Name the file SORequest.xml.

### Send the request and view the response

1.  Save a copy of the file that you named SORequest.xml to the folder that you named AIFIn.
    

    > [!NOTE]
    > <P>When you submit multiple documents to a port that uses the file system adapter, the documents are processed in order based on their file names. To control the order in which documents are processed, use file names that include a sequencing scheme, such as "SO_0001" and "SO_0002".</P>



2.  Wait for the batch job to retrieve the file from the folder.

3.  Watch the folder that you named AIFOut. After a few minutes, a response file will be saved to this folder by AIF.

4.  Open the response file to view the XML code. A valid XML response contains the number of the sales order that was created in the field named **SalesId**. For example:
    
        <?xml version="1.0" encoding="UTF-8"?>
        <Envelope xmlns="http://schemas.microsoft.com/dynamics/2011/01/documents/Message">
        <Header>
          <MessageId>{E120D4F9-C466-4CBF-BA60-E365202D7BE6}</MessageId>
          <Action>http://schemas.microsoft.com/dynamics/2008/01/services/SalesOrderService/create</Action>
          <RequestMessageId>{5603D03A-4380-404D-9F27-738BE0FEA13E}</RequestMessageId>
        </Header>
        <Body>
          <MessageParts xmlns="http://schemas.microsoft.com/dynamics/2011/01/documents/Message">
            <EntityKeyList xmlns="http://schemas.microsoft.com/dynamics/2006/02/documents/EntityKeyList">
              <EntityKey xmlns="http://schemas.microsoft.com/dynamics/2006/02/documents/EntityKey">
                <KeyData>
                  <KeyField>
                    <Field>SalesId</Field>
                    <Value>SO-100004</Value>
                  </KeyField>
                </KeyData>
              </EntityKey>
            </EntityKeyList>
          </MessageParts>
        </Body>
        </Envelope>
    
    The response message contains an element titled \<RequestMessageId\>. This element contains the same GUID value that you provided for the \<MessageId\> element in the original request document. You can use this value to match responses to requests, a process called correlation.

## See also

[Walkthrough: Transforming a document](walkthrough-transforming-a-document.md)

