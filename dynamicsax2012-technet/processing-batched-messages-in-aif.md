---
title: Processing batched messages in AIF
TOCTitle: Processing batched messages in AIF
ms:assetid: c7bc8b20-9d66-464e-9a89-4df2309d001d
ms:mtpsurl: https://technet.microsoft.com/library/Hh397323(v=AX.60)
ms:contentKeyID: 36929814
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Processing batched messages in AIF 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX document services and Application Integration Framework (AIF) enable large amounts of data to be processed at the same time. A batched message is a single document that contains multiple, individual messages that are grouped together so that they can be processed as a unit. Batched messages can be processed only by using the file system adapter.

## About batched messages

Batched messages use the batch schema. This XML schema provides the \<Batch\> element, which can contain one or more \<Envelope\> elements. Each \<Envelope\> element contains a single AIF message. Each single AIF message in the batch must be smaller than 10 MB.

The namespace of the batch schema is https://schemas.microsoft.com/Microsoft Dynamics/2009/06/documents/Batch. You can retrieve the Extensible Stylesheet Definition (XSD) file for the batch schema from the following location where you installed Microsoft Dynamics AX:

Program files\\Microsoft Dynamics AX\\60\\Server\\MicrosoftDynamicsAX\\bin\\Application\\Share\\Include\\MessageSet.xsd

The \<Batch\> element optionally contains the two attributes that are described in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Name</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>BatchId</strong></p></td>
<td><p>A string value that is unique for a particular batched message. The messages in the batch are processed in parallel when the port is configured for parallel processing.</p>
<p>The maximum length of the string is 256 characters.</p></td>
</tr>
<tr class="even">
<td><p><strong>ConversationId</strong></p></td>
<td><p>A string value that several inbound messages can have in common. The conversation ID is a signal to AIF to process only one message in the conversation group at a time.</p>
<p>For more information about how conversation IDs work with batched messages, see the following section, named &quot;How batched messages are processed.&quot; For more information about how conversation IDs are used in parallel processing scenarios, see <a href="sequential-and-parallel-processing-in-services-and-aif.md">Sequential and parallel processing in services and AIF</a>.</p></td>
</tr>
</tbody>
</table>


The following example shows a single batched message that contains two requests to create sales orders.

    <?xml version="1.0" encoding="UTF-8"?>
    <Batch xmlns="https://schemas.microsoft.com/dynamics/2009/06/documents/Batch"
        BatchId="1234" ConversationId="5678">
    <Envelope xmlns="https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
      <Header>
        <MessageId>{722B196B-4ACB-4048-8ED3-36915A7DD269}</MessageId>
        <Action>https://schemas.microsoft.com/dynamics/2008/01/services/SalesOrderService/create</Action>
      </Header>
      <Body>
        <MessageParts>
          <SalesOrder xmlns="https://schemas.microsoft.com/dynamics/2008/01/documents/SalesOrder">
            <SalesTable class="entity">
              <CustAccount>100002</CustAccount>
              <PurchOrderFormNum>P0</PurchOrderFormNum>
              <ReceiptDateRequested>2011-05-31</ReceiptDateRequested>
              <SalesLine class="entity">
                <ItemId>10003</ItemId>
                <SalesQty>10</SalesQty>
                <SalesUnit>Pcs</SalesUnit>
              </SalesLine>
            </SalesTable>
          </SalesOrder>
        </MessageParts>
      </Body>
    </Envelope>
    <Envelope xmlns="https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
      <Header>
        <MessageId>{44920385-3194-498F-8AC7-438F3632DF51}</MessageId>
        <Action>https://schemas.microsoft.com/dynamics/2008/01/services/SalesOrderService/create</Action>
      </Header>
      <Body>
        <MessageParts>
          <SalesOrder xmlns="https://schemas.microsoft.com/dynamics/2008/01/documents/SalesOrder">
            <SalesTable class="entity">
              <CustAccount>100002</CustAccount>
              <PurchOrderFormNum>P0</PurchOrderFormNum>
              <ReceiptDateRequested>2011-05-31</ReceiptDateRequested>
              <SalesLine class="entity">
                <ItemId>10003</ItemId>
                <SalesQty>5</SalesQty>
                <SalesUnit>Pcs</SalesUnit>
              </SalesLine>
            </SalesTable>
          </SalesOrder>
        </MessageParts>
      </Body>
    </Envelope>
    </Batch>

### How batched messages are processed

After a batched message is received, Microsoft Dynamics AX splits the document into its component requests, and then processes each request separately. If the integration port is configured to send responses, each component request receives a separate, corresponding response message. Each response message contains a \<RequestMessageId\> element. This element contains the GUID from the corresponding \<MessageId\> element in the header of the original request. The following example shows one response message that corresponds to the second request in the batched message shown in the previous section. In this example, you can see that the \<MessageId\> element contains a new GUID value, but the \<RequestMessageId\> element contains the same value as the message ID in the request.

    <?xml version="1.0" encoding="UTF-8"?>
    <Envelope xmlns="https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
      <Header>
        <MessageId>{B165292C-BF8B-43A4-9788-21D1B0AED185}</MessageId>
        <Action>https://schemas.microsoft.com/dynamics/2008/01/services/SalesOrderService/create</Action>
        <RequestMessageId>{44920385-3194-498F-8AC7-438F3632DF51}</RequestMessageId>
      </Header>
      <Body>
        <MessageParts xmlns="https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
          <EntityKeyList xmlns="https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKeyList">
            <EntityKey xmlns="https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKey">
              <KeyData>
                <KeyField>
                  <Field>SalesId</Field>
                  <Value>SO-100021</Value>
                </KeyField>
              </KeyData>
            </EntityKey>
          </EntityKeyList>
        </MessageParts>
      </Body>
    </Envelope>

The following diagram shows how batched messages are processed by AIF. Notice that the batched message is de-batched after the inbound transform stage, and that the request messages remain separate from that time forward.

![Batched processing in AIF](images/Hh397323.AIFBatchedProcessing(AX.60).jpg "Batched processing in AIF")

### Batch IDs and conversation IDs

A batch ID associates various messages that are contained in the same message set. Messages that have the same batch ID are processed as a group. Additionally, these message are processed in parallel if the **Process requests in parallel** setting for the integration port is selected, and the **Upon error in batched requests:** setting is set to **Continue**. See the next section.

You can use conversation IDs to order the processing of requests. Messages that have the same conversation ID are processed together, in alphabetical order by file name. However, a conversation ID cannot be used to make a connection between messages that are contained in separate batched requests. In other words, a batched message can be part of a conversation, but every message that is contained in a batched message is part of the same conversation.

For more information about sequential and parallel message processing, see [Sequential and parallel processing in services and AIF](sequential-and-parallel-processing-in-services-and-aif.md).

## Error handling and troubleshooting

When batched messages are processed, error handling is determined by the configuration of the integration port. The **Processing options** FastTab contains the setting that determines how errors are managed when they are encountered during batch processing. In the **Upon error in batched requests:** field, select one of the following values:

  - **Continue** – Continue processing messages after an error is encountered. Messages that cause errors may not be processed correctly. These messages remain in the gateway queue. Messages that do not cause errors continue to be processed, and then they generate responses, if responses are appropriate. Check the exceptions log for detailed information about the messages that caused errors.

  - **Halt** – Stop processing the rest of the messages in the batch after an error is encountered. The rest of the messages, together with the message that caused the error, remain in the gateway queue in the appropriate state. Check the exceptions log for detailed information about the error that interrupted the message processing. No more messages from the batch are processed. Messages that have been processed generate responses, if responses are appropriate, and any resulting changes are committed to the database.

  - **Rollback** – Stop processing the batched messages, and undo any previously processed messages from the batch that contains the message that caused the error. All messages remain in the gateway queue in the appropriate state.

Note that conversation IDs are not related to the settings for error handling on the integration port. For information about how to reprocess messages that encounter errors, see [Edit and resubmit messages in the AIF gateway queue](edit-and-resubmit-messages-in-the-aif-gateway-queue.md).

