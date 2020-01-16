---
title: 'Example: Delete Action'
TOCTitle: 'Example: Delete Action'
ms:assetid: 1f3261d9-c237-4f3e-8413-cb6cba60e246
ms:mtpsurl: https://technet.microsoft.com/library/Cc584466(v=AX.60)
ms:contentKeyID: 35241491
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- xml
---

# Example: Delete Action 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes sample inbound and outbound messages for the delete action in Application Integration Framework (AIF) document services. An inbound delete action message can specify one or more records to be deleted. After the inbound message is processed, AIF generates a single outbound message that has an almost empty \<Body\> tag section.

## Inbound Delete Message Sample

The following inbound delete message specifies that one record is deleted from the SalesTable table. To enforce referential integrity, the system might also delete records from the child table SalesLine. Line breaks have been added for readability.

``` xml
<?xml version="1.0" encoding="utf-8"?>
<Envelope xmlns = "https://schemas.microsoft.com/
  dynamics/2008/01/documents/Message">
 <Header>
  <MessageId>{DD112222-0306-1220-0001-DD33444455DD}</MessageId>
  <Action>https://schemas.microsoft.com/dynamics/
    2011/01/services/SalesOrderService/delete</Action>
 </Header>

 <Body>
  <MessageParts xmlns = "https://schemas.microsoft.com/
    dynamics/2008/01/documents/Message">
   <EntityKeyList xmlns = "https://schemas.microsoft.com/
     dynamics/2006/02/documents/EntityKeyList">

    <EntityKey xmlns = "https://schemas.microsoft.com/
      dynamics/2006/02/documents/EntityKey">
     <KeyData>
      <KeyField>
       <Field>SalesId</Field>
       <Value>00020_036</Value>
      </KeyField>
     </KeyData>
    </EntityKey>

   </EntityKeyList>
  </MessageParts>
 </Body>
</Envelope>
```


> [!NOTE]
> <P>The sample XML contains no tags that are specific to this service or delete action.</P>



## Corresponding Outbound Message

The outbound delete message has an almost empty \<Body\> section. The following outbound message is generated from the previous inbound message.

``` xml
<?xml version="1.0" encoding="utf-8"?>
<Envelope xmlns = "https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
 <Header>
  <MessageId>{513ACDF8-8BB9-41E2-8B26-48D8A0458C5B}</MessageId>
  <Action>https://schemas.microsoft.com/dynamics/2008/01/services/SalesOrderService/delete</Action>
  <RequestMessageId>{DD112222-0306-1220-0001-DD33444455DD}</RequestMessageId>
 </Header>
 <Body>
  <MessageParts xmlns = "https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
  </MessageParts>
 </Body>
</Envelope>
```

## See also

[Document Class Service Operations](document-class-service-operations.md)

[AIF Messages](aif-messages.md)

[Message Header](message-header.md)

[Message Body](message-body.md)

