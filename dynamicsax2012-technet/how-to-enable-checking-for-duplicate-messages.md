---
title: 'How to: Enable Checking for Duplicate Messages'
TOCTitle: 'How to: Enable Checking for Duplicate Messages'
ms:assetid: b6fd698e-44c9-4508-afed-1df866ba5401
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc617915(v=AX.60)
ms:contentKeyID: 35249836
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- xml
---

# How to: Enable Checking for Duplicate Messages [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to enable checking for duplicate messages in Application Integration Framework (AIF). Each XML message that comes into AIF has a header that contains identification information such as the message ID and the service operation being called. For more information, see [Message Header](message-header.md).

The MessageId element in the header contains a GUID that uniquely identifies each inbound message. If you do not provide a MessageId value, AIF generates one when the message is received.

If you want to enable AIF to check for duplicate messages, you must complete two steps:

  - Ensure that the message MessageId element has a value.

  - Set the EnableIdempotence property for the service operation to Yes.

AIF checks for duplicate messages at the service operation level. You must set the EnableIdempotence property for each service operation for which you want to check for duplicates.

By default, the EnableIdempotence property is set to Yes for the create, delete, and update service operations for the document services that are included with Microsoft Dynamics AX. Therefore, if you want to enable checking for duplicates, you must explicitly add a GUID that you created for the MessageId element of the inbound message.

If you have the EnableIdempotence property for a service method set to Yes, you can still send in messages without a MessageId value. However, if there is no MessageId, AIF assigns it a unique GUID and never returns a duplicate message error.

When AIF receives a duplicate message, it sends an error response and the following error appears in the **Exceptions** form:

Duplicate message. Message has already been processed.

The response message that contains the error is sent back to the calling application and resembles the following code.

``` xml
<?xml version="1.0" encoding="utf-8" ?> 
<Envelope xmlns="http://schemas.microsoft.com/dynamics/2008
    /01/documents/Message">
    <Header>
        <MessageId>{8F0DD3FE-D824-4DC9-87D5-D05152851346}</MessageId>
        <Action>http://schemas.microsoft.com/dynamics/2008
            /01/services/CustomerService/read</Action>
        <RequestMessageId>{76704405-5237-4934-83EC-7E1357F28B10}
            </RequestMessageId> 
    </Header>
    <Body>
        <MessageParts xmlns="http://schemas.microsoft.com/dynamics/2008/01/documents/Message">
            <Fault xmlns="http://schemas.microsoft.com/dynamics/2008/
                01/documents/Fault">
                <Code>DuplicateMessage</Code> 
                <Reason>
                    <Text xml:lang="EN-US">Duplicate message. 
                        Message has already been processed.</Text> 
                </Reason>
            </Fault>
        </MessageParts>
    </Body>
</Envelope>
```

## Enable Checking for Duplicates

### To enable checking for duplicate messages

1.  In the AOT, expand the **Services** node, expand the service, expand the **Operations** node, right-click the service operation, and then click **Properties**.

2.  Set the **EnableIdempotence** property to **Yes**.

3.  Set the value of the MessageId in the inbound message to a specific GUID.

## See also

[AIF Messages](aif-messages.md)

[Messages and transforms in AIF](messages-and-transforms-in-aif.md)

