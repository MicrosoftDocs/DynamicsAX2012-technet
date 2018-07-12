---
title: Partial Update With AIF
TOCTitle: Partial Update With AIF
ms:assetid: 836f2927-9221-43ee-923f-ce381eaf02bc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh582243(v=AX.60)
ms:contentKeyID: 39533579
ms.date: 04/02/2014
mtps_version: v=AX.60
---

# Partial Update With AIF 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R2.</P>



This topic describes partial updates for data in Microsoft Dynamics AX using Application Integration Framework (AIF). The partial update options are illustrated by using messages for an asynchronous exchange. For more information about messages, see [Messages and transforms in AIF](messages-and-transforms-in-aif.md) and [AIF Messages](aif-messages.md). For more information about asynchronous exchanges, see [Walkthrough: Exchanging documents by using the file system adapter](walkthrough-exchanging-documents-by-using-the-file-system-adapter.md) and [Walkthrough: Exchanging documents by using the MSMQ adapter](walkthrough-exchanging-documents-by-using-the-msmq-adapter.md).

AIF supports a partial update scenario where only the fields that are contained in the submitted message are updated in the corresponding database tables. If there are fields in these tables that are not specified in the message, the fields retain their original values. However, fields that are not specified in the submitted message, but are based on fields that have been updated, are set to default values according to their default rules. For example, consider a field FullName that is based on a combination of FirstName and LastName. If FirstName or LastName are changed in a partial update where FullName is not specified, FullName is also changed.

The following table lists the three possible scenarios for a partial update:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Message Field Entry</p></th>
<th><p>Resulting Table Field Entry</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The field is not in the message.</p></td>
<td><p>The table field remains unmodified.</p></td>
</tr>
<tr class="even">
<td><p>The field is in the message and a NULL value is specified (for example, &lt;Field&gt;xsi:nil&lt;/Field&gt;).</p></td>
<td><p>The table field remains unmodified.</p></td>
</tr>
<tr class="odd">
<td><p>The field is in the message and contains one of these values: a value (for example, &lt;Field&gt;123&lt;/Field&gt;, an empty tag (for example, &lt;Field&gt;&lt;/Field&gt;), or an X++ NULL value.</p></td>
<td><p>The table field is changed to contain the specified value.</p></td>
</tr>
</tbody>
</table>


## Specifying a Partial Update

In a partial update, the inbound message includes only the data to be updated plus any fields required by the document. All the other field values that are not contained in the inbound update request message remain unchanged in the database tables, unless there is some default logic.

The signature for the update service operation is:

void update(EntityKey\[\], \<DocumentObject\>)

The \<DocumentObject\> parameter contains one or more elements (for example, SalesTable or CustTable). The number of tables that are contained in the document object must equal the length of the entity key array. The index of each entity key that is passed through the EntityKey\[\] parameter must correspond to the position of its corresponding table in the document object.

## Specifying Action Attributes

A partial update specifies the update action in the header of the message. The action for each record to be updated is specified by one of the action attributes.

The following table lists the specific actions that can be performed by using the sales order document service to update SalesTable and SalesLine.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Attribute</p></th>
<th><p>Description of Update Action</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>&lt;SalesTable class=&quot;entity&quot; action=&quot;update&quot;&gt;</p></td>
<td><p>The sales order header should be updated.</p></td>
</tr>
<tr class="even">
<td><p>&lt;SalesLine class=&quot;entity&quot; action=&quot;update&quot;&gt;</p></td>
<td><p>A sales order line should be updated.</p></td>
</tr>
<tr class="odd">
<td><p>&lt;SalesLine class=&quot;entity&quot; action=&quot;create&quot;&gt;</p></td>
<td><p>A new sales order line should be created.</p></td>
</tr>
<tr class="even">
<td><p>&lt;SalesLine class=&quot;entity&quot; action=&quot;delete&quot;&gt;</p></td>
<td><p>A sales order line should be deleted.</p></td>
</tr>
</tbody>
</table>


## Example XML

The following example creates a message to update a sales order with three sales lines: one to be updated, one to be created, and one to be deleted.

    <?xml version="1.0" encoding="utf-8" ?> 
    <Envelope xmlns="http://schemas.microsoft.com/dynamics/2011/
        01/documents/Message">
        <Header>
            <Action>http://www.microsoft.com/dynamics/services/2008/
                01/SalesOrderService/update</Action>
        </Header>
        <Body>
            <MessageParts xmlns = "http://schemas.microsoft.com/dynamics/2008/01/documents/Message">
     
            <EntityKeyList xmlns="http://schemas.microsoft.com/dynamics/
                2006/02/documents/EntityKeyList">
                <EntityKey xmlns="http://schemas.microsoft.com/dynamics/
                    2006/02/documents/EntityKey">
                    <KeyData>
                        <KeyField>
                            <Field>CustAccount</Field>
                            <Value>10002</Value>
                        </KeyField>
                    </KeyData>
                </EntityKey>
      </EntityKeyList>
     
          <SalesOrder xmlns="http://schemas.microsoft.com/dynamics/
              2008/01/documents/SalesOrder">
              <SalesTable class="entity" action="update">
                 <CustAccount>10002</CustAccount>
                 <_DocumentHash>d2394857bffgg23924718kxk2908zj3s</_DocumentHash>
              <SalesLine class="entity" action="update">
                 <ItemId>4710003</ ItemId >
    
    … data omitted …
    
                 <SalesQty>77</ SalesQty >
                 <SalesUnit>Pcs</ SalesUnit > 
             </SalesLine>
             <SalesLine class="entity" action="create">
                 <ItemId>4710005</ ItemId >
    
     … data omitted …
    
             </SalesLine>
             <SalesLine class="entity" action="delete">
                 <ItemId>4710001</ ItemId >
    
    … data omitted …
    
             </SalesLine>
             </SalesTable>
             </SalesOrder>
             </MessageParts>
        </Body>
    </Envelope>


> [!NOTE]
> <P>The document hash value in the &lt;_DocumentHash&gt; tag is used for concurrency. You must specify either the document hash or the RecID and RecVersion fields for each record. You can retrieve these values from a prior read operation. For more information, see <A href="concurrency-when-updating-data.md">Concurrency When Updating Data</A>.</P>



## Clearing Surrogate Foreign Keys in a Table


> [!NOTE]
> <P>This feature is only available if Microsoft Dynamics AX 2012 R2 or a later version is installed.</P>



Document service queries often contain tables that are linked with a surrogate foreign key. Default behavior for a partial update using a document service is to leave fields unchanged if they are not specified in the update. In other words, if you do not specify any new values for the fields in the LogisticsPostalAddress table when updating fields for a Sales Order, those values remain the same after the partial update. However, you can clear surrogate foreign key fields by using the ClearNilFieldsOnUpdate property and xsi:nil attribute.

To clear the surrogate foreign key fields when you perform a partial update, you set values for a property and an attribute. You set the property ClearNilFieldsOnUpdate to True. You use the xsi:nil attribute to indicate that the fields in the **LogisticsPostalAddress** table have no content. For more information about the xsi:nil attribute, see [Xsi:nil Attribute Binding Support](http://go.microsoft.com/fwlink/?linkid=394533%26clcid=0x409).

The following example shows XML that clears the surrogate foreign key values for a Sales Order that has a CustAccount of 10002.

    <?xml version="1.0" encoding="utf-8" ?> 
    <Envelope xmlns="<a href='http://schemas.microsoft.com/dynamics/2011/'>http://schemas.microsoft.com/dynamics/2011/</a>
    01/documents/Message">
    <Header>
    <Action><a href='http://www.microsoft.com/dynamics/services/2008/'>http://www.microsoft.com/dynamics/services/2008/</a>
    01/SalesOrderService/update</Action>
    </Header>
    <Body>
    <MessageParts xmlns = "<a href='http://schemas.microsoft.com/dynamics/2008/01/documents/Message'>http://schemas.microsoft.com/dynamics/2008/01/documents/Message</a>">
     
    <EntityKeyList xmlns="<a href='http://schemas.microsoft.com/dynamics/'>http://schemas.microsoft.com/dynamics/</a>
    2006/02/documents/EntityKeyList">
    <EntityKey xmlns="<a href='http://schemas.microsoft.com/dynamics/'>http://schemas.microsoft.com/dynamics/</a>
    2006/02/documents/EntityKey">
    <KeyData>
    <KeyField>
    <Field>CustAccount</Field>
    <Value>10002</Value>
    </KeyField>
    </KeyData>
    </EntityKey>
    </EntityKeyList>
     
    <SalesOrder xmlns="<a href='http://schemas.microsoft.com/dynamics/'>http://schemas.microsoft.com/dynamics/</a>
    2008/01/documents/SalesOrder">
    <ClearNilFieldsOnUpdate>true</ClearNilFieldsOnUpdate>
    <SalesTable class="entity" action="update">
    <CustAccount>10002</CustAccount>
    <_DocumentHash>d2394857bffgg23924718kxk2908zj3s</_DocumentHash>
    <CustomerRef>NewCustomerAccount</CustomerRef>
    <LogisticsPostalAddress xsi:nil=”true”/>
    </SalesLine>
    </SalesTable>
    </SalesOrder>
    </MessageParts>
    </Body>
    </Envelope>

## See also

[Document Class Service Operations](document-class-service-operations.md)

[Document XML Generation](document-xml-generation.md)

  


