---
title: 'Example: FindKeys Action'
TOCTitle: 'Example: FindKeys Action'
ms:assetid: 387b1936-eb0c-4951-9da6-6840a41d1b0a
ms:mtpsurl: https://technet.microsoft.com/library/Aa636580(v=AX.60)
ms:contentKeyID: 35242847
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- xml
---

# Example: FindKeys Action 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes sample inbound and outbound messages for the findkeys action in Application Integration Framework (AIF) document services. You can use the findkeys action to obtain the values of the key fields for all records that match your query criteria.

The outbound message contains \<EntityKey\> tags for the found records.

## Inbound FindKeys Message Sample

The following inbound FindKeys message specifies one \<CriteriaElement\> tag. The Range operator is used. Range selects all records that have a value between \<Value1\> and \<Value2\> (including those two values).

There are no XML tags that are specific to this inbound message. However, the value for \<DataSourceName\> is specific to this message, and it must be compatible with the service that is listed in the \<Action\> tag. Line breaks have been added for readability.

``` xml
<?xml version="1.0" encoding="utf-8"?>
<Envelope xmlns = "https://schemas.microsoft.com/
  dynamics/2011/01/documents/Message">

 <Header>
  <MessageId>{B4BD0E9F-0312-0630-0002-47B753E77C2D}</MessageId>
  <Action>https://schemas.microsoft.com/dynamics/
    2008/01/services/CustomerService/findkeys</Action>
 </Header>

 <Body>
  <MessageParts xmlns = "https://schemas.microsoft.com/
    dynamics/2008/01/documents/Message">
   <QueryCriteria xmlns = "https://schemas.microsoft.com/
     dynamics/2006/02/documents/QueryCriteria">

    <CriteriaElement>
     <DataSourceName>CustTable</DataSourceName>
     <FieldName>Street</FieldName>
     <Operator>Range</Operator>
     <Value1>1</Value1>
     <Value2>5</Value2>
    </CriteriaElement>

   </QueryCriteria>
  </MessageParts>
 </Body>

</Envelope>
```

## Corresponding Outbound Message

The outbound message contains \<EntityKey\> tags for the found records.

The following outbound message is generated from the previous inbound message.

``` xml
<?xml version="1.0" encoding="utf-8"?>
<Envelope xmlns = "https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
 <Header>
  <MessageId>{5116528D-C4E1-4483-81A5-7C2976E4E935}</MessageId>
  <Action>https://schemas.microsoft.com/dynamics/2008/01/services/CustomerService/findkeys</Action>
  <RequestMessageId>{B4BD0E9F-0312-0630-0002-47B753E77C2D}</RequestMessageId>
 </Header>
 <Body>
  <MessageParts xmlns = "https://schemas.microsoft.com/dynamics/2008/01/documents/Message">
   <EntityKeyList xmlns = "https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKeyList">
    <EntityKey xmlns = "https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKey">
     <KeyData>
      <KeyField>
       <Field>AccountNum</Field>
       <Value>4012</Value>
      </KeyField>
     </KeyData>
    </EntityKey>
    <EntityKey xmlns = "https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKey">
     <KeyData>
      <KeyField>
       <Field>AccountNum</Field>
       <Value>4014</Value>
      </KeyField>
     </KeyData>
    </EntityKey>
    <EntityKey xmlns = "https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKey">
     <KeyData>
      <KeyField>
       <Field>AccountNum</Field>
       <Value>4500</Value>
      </KeyField>
     </KeyData>
    </EntityKey>
    <EntityKey xmlns = "https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKey">
     <KeyData>
      <KeyField>
       <Field>AccountNum</Field>
       <Value>4501</Value>
      </KeyField>
     </KeyData>
    </EntityKey>
    <EntityKey xmlns = "https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKey">
     <KeyData>
      <KeyField>
       <Field>AccountNum</Field>
       <Value>4505</Value>
      </KeyField>
     </KeyData>
    </EntityKey>
    <EntityKey xmlns = "https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKey">
     <KeyData>
      <KeyField>
       <Field>AccountNum</Field>
       <Value>4506</Value>
      </KeyField>
     </KeyData>
    </EntityKey>
   </EntityKeyList>
  </MessageParts>
 </Body>
</Envelope>
```

## See also

[Document Class Service Operations](document-class-service-operations.md)

[AIF Messages](aif-messages.md)

[Message Header](message-header.md)

[Message Body](message-body.md)

