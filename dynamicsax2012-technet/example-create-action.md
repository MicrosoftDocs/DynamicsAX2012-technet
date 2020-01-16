---
title: 'Example: Create Action'
TOCTitle: 'Example: Create Action'
ms:assetid: 6233024b-43d3-41f4-81b7-db1f8de45f22
ms:mtpsurl: https://technet.microsoft.com/library/Aa633136(v=AX.60)
ms:contentKeyID: 35244565
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- xml
---

# Example: Create Action 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes sample inbound and outbound messages for the create action in Application Integration Framework (AIF) document services. An inbound create message can specify one or more records to be added. After the inbound message is processed, AIF generates a single outbound message that contains the unique entity key value for each record that was added.

## Inbound Create Message Sample

The following inbound create message specifies that one record is added to the SalesTable table, and one record is added to the child SalesLine table.

The XML tags that are specific to this message are the service tag \<SalesOrder\>, and the two data source tags \<SalesTable\> and \<SalesLine\>.

The following example message has a header that contains a unique message ID and an Action tag that specifies the create operation for the SalesOrderService service. Line breaks have been added for readability.

``` xml
<?xml version="1.0" encoding="utf-8"?>
<Envelope xmlns = "http://schemas.microsoft.com/
 dynamics/2011/01/documents/Message">
 <Header>
  <MessageId>{D1F93462-0229-1430
    -0001-93FAE32B2E4D}</MessageId>
  <Action>http://schemas.microsoft.com/
    dynamics/2008/01/services/
    SalesOrderService/create</Action>
 </Header>

 <Body>
  <MessageParts xmlns = "http://schemas.microsoft.com/
    dynamics/2011/01/documents/Message">
   <SalesOrder xmlns = "http://schemas.microsoft.com/
     dynamics/2008/01/documents/SalesOrder">
    <DocPurpose>Original</DocPurpose>

    <SalesTable class = "entity">
     <CurrencyCode>EUR</CurrencyCode>
     <CustAccount>4000</CustAccount>
     <DeliveryDate>2008-02-29</DeliveryDate>
     <ExportReason>Sale parts.</ExportReason>
     <Payment>D30</Payment>
     <PurchOrderFormNum>PO2</PurchOrderFormNum>

     <SalesLine class = "entity">
      <ItemId>ESB-009</ItemId>
      <SalesQty>1.00</SalesQty>
      <SalesUnit>Pcs</SalesUnit>
     </SalesLine>
    </SalesTable>
   </SalesOrder>

  </MessageParts>
 </Body>
</Envelope>
```

## Corresponding Outbound Message

The outbound create message contains an \<EntityKey\> for every record that was created in the main target table. There are no \<EntityKey\> tags for records that are added to child tables.

The following outbound message is generated from the previous inbound message.

``` xml
<?xml version="1.0" encoding="utf-8"?>
<Envelope xmlns = "http://schemas.microsoft.com/dynamics/2011/01/documents/Message">
 <Header>
  <MessageId>{9779F678-4BE2-442C-ABD3-AF53A7B8D2D5}</MessageId>
  <Action>http://schemas.microsoft.com/dynamics/2008/01/services/SalesOrderService/create</Action>
  <RequestMessageId>{D1F93462-0229-1430-0001-93FAE32B2E4D}</RequestMessageId>
 </Header>
 <Body>
  <MessageParts xmlns = "http://schemas.microsoft.com/dynamics/2011/01/documents/Message">
   <EntityKeyList xmlns = "http://schemas.microsoft.com/
    dynamics/2006/02/documents/EntityKeyList">
    <EntityKey xmlns = "http://schemas.microsoft.com/
     dynamics/2006/02/documents/EntityKey">
     <KeyData>
      <KeyField>
       <Field>SalesId</Field>
       <Value>00018_036</Value>
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

