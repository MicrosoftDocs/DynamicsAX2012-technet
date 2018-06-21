---
title: Message Body
TOCTitle: Message Body
ms:assetid: c3fa5b4b-94cf-49f1-abed-5b1eb0ad5e34
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa865166(v=AX.60)
ms:contentKeyID: 35251096
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- xml
---

# Message Body [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the \<Body\> tag section of inbound and outbound messages in Application Integration Framework (AIF). The \<Body\> tag must follow the closing \</Header\> tag. For more information about messages and their format in Microsoft Dynamics AX, see [Messages and transforms in AIF](messages-and-transforms-in-aif.md).

For examples of inbound and outbound messages, see [Example of Inbound XML Message](example-of-inbound-xml-message.md) and [Example of Outbound XML Message](example-of-outbound-xml-message.md).

## The \<MessageParts\> Tag

The first tag nested under \<Body\> must be the \<MessageParts\> tag. There is no requirement to specify the xmlns attribute on the \<MessageParts\> tag because the correct value is already specified on the outer \<Envelope\> tag.

## Tags Required for \<Action\> Values

The values in the \<Action\> tag determine the XSD schema validations that are applied to the contents of the \<Body\> tag. The \<Action\> tag is nested under the \<Header\> tag.

For more information about actions, see [Document Class Service Operations](document-class-service-operations.md).

### Tags in the \<Body\> of Inbound Messages

The outermost tag in each table cell occurs immediately after the \<MessageParts\> tag, and is nested directly under the \<MessageParts\> tag. The following example shows the nesting relationship between the \<MessageParts\> tag and the tags in the body of an inbound Find message .

``` xml
<Body>
    <MessageParts>
        <QueryCriteria>
            <CriteriaElement>
            ...
            </CriteriaElement>
        </QueryCriteria>
    </MessageParts>
</Body>
```

For inbound messages, the following table shows the XML tags that must be in the \<Body\> tag section for each action.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service operation in &lt;Action&gt;</p></th>
<th><p>Tags in the inbound &lt;Body&gt;</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create</p></td>
<td><ul>
<li><p>&lt;serviceExternalName&gt;</p>
<ul>
<li><p>&lt;entityName&gt;</p></li>
</ul></li>
</ul>
<p>Examples could be as follows:</p>
<ul>
<li><p>&lt;Customer&gt;</p>
<ul>
<li><p>&lt;CustTable&gt;</p></li>
</ul></li>
</ul>
<p>The following example shows the XML for a Create action for the LedgerJournal document.</p>
<pre><code>&lt;Body&gt;
        &lt;MessageParts xmlns = &quot;http://schemas.microsoft.com/dynamics/2008/01/
        documents/Message&quot;&gt;
        &lt;LedgerJournal xmlns = &quot;http://schemas.microsoft.com/dynamics/2008/01/
        documents/LedgerJournal&quot;&gt;
        &lt;LedgerJournalTable class=&quot;entity&quot;&gt;
            &lt;CurrencyCode&gt;USD&lt;/CurrencyCode&gt;
            &lt;JournalName&gt;Day1&lt;/JournalName&gt;
            &lt;JournalTotalCredit&gt;50&lt;/JournalTotalCredit&gt;
            &lt;JournalTotalDebit&gt;50&lt;/JournalTotalDebit&gt;
            &lt;JournalType&gt;Daily&lt;/JournalType&gt;
            &lt;Name&gt;Daily Journal 1&lt;/Name&gt;
            &lt;VoucherSeries&gt;Ledger_3&lt;/VoucherSeries&gt;
        &lt;LedgerJournalTrans class=&quot;entity&quot;&gt;        
            &lt;AccountNum&gt;11010&lt;/AccountNum&gt;
            &lt;AccountType&gt;Ledger&lt;/AccountType&gt;
            &lt;AmountCurDebit&gt;50&lt;/AmountCurDebit&gt;
            &lt;CurrencyCode&gt;USD&lt;/CurrencyCode&gt;
            &lt;DocumentDate&gt;2007-05-28&lt;/DocumentDate&gt;
            &lt;Invoice&gt;00003&lt;/Invoice&gt;
            &lt;OffsetAccount&gt;12020&lt;/OffsetAccount&gt;
            &lt;OffsetAccountType&gt;Ledger&lt;/OffsetAccountType&gt;
            &lt;TransDate&gt;2007-05-28&lt;/TransDate&gt;
            &lt;Txt&gt;AxLedgerJournal inbound test trans 1&lt;/Txt&gt;
        &lt;/LedgerJournalTrans&gt;      
        &lt;/LedgerJournalTable&gt;  
        &lt;/LedgerJournal&gt;
        &lt;/MessageParts&gt;
    &lt;/Body&gt;</code></pre></td>
</tr>
<tr class="even">
<td><p>Delete</p></td>
<td><ul>
<li><p>&lt;EntityKeyList&gt;</p>
<ul>
<li><p>&lt;EntityKey&gt;</p></li>
</ul></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Find</p></td>
<td><ul>
<li><p>&lt;QueryCriteria&gt;</p>
<ul>
<li><p>&lt;CriteriaElement&gt;</p></li>
</ul></li>
</ul></td>
</tr>
<tr class="even">
<td><p>FindKeys, GetKeys, GetChangedKeys</p></td>
<td><ul>
<li><p>&lt;QueryCriteria&gt;</p>
<ul>
<li><p>&lt;CriteriaElement&gt;</p></li>
</ul></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Read</p></td>
<td><p>Same as Delete.</p></td>
</tr>
<tr class="even">
<td><p>Update</p></td>
<td><p>The following tags must come first:</p>
<ul>
<li><p>&lt;EntityKeyList&gt;</p>
<ul>
<li><p>&lt;EntityKey&gt;</p></li>
</ul></li>
</ul>
<p>The following tags must come next:</p>
<ul>
<li><p>&lt;serviceExternalName&gt;</p>
<ul>
<li><p>&lt;entityName&gt;</p></li>
</ul></li>
</ul>
<p>The tags &lt;EntityKeyList&gt; and &lt;serviceExternalName&gt; are at the same level of nesting under &lt;MessageParts&gt;. Both tags are nested one level deeper than &lt;MessageParts&gt;, which is their parent tag.</p>
<p>The &lt;EntityKey&gt; tag sequence must align with the &lt;entityName&gt; tag sequence.</p></td>
</tr>
</tbody>
</table>


### Tags in the \<Body\> of Outbound Messages

For outbound messages, the following table shows the XML tags that occur in the \<Body\> tag section for each action.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service operation in &lt;Action&gt;</p></th>
<th><p>Tags in the outbound &lt;Body&gt;</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create</p></td>
<td><ul>
<li><p>&lt;EntityKeyList&gt;</p>
<ul>
<li><p>&lt;EntityKey&gt;</p></li>
</ul></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Delete</p></td>
<td><p>The &lt;MessageParts&gt; tag section is empty.</p></td>
</tr>
<tr class="odd">
<td><p>Find</p></td>
<td><ul>
<li><p>&lt;serviceExternalName&gt;</p>
<ul>
<li><p>&lt;entityName&gt;</p></li>
</ul></li>
</ul></td>
</tr>
<tr class="even">
<td><p>FindKeys, GetKeys, GetChangedKeys</p></td>
<td><ul>
<li><p>&lt;EntityKeyList&gt;</p>
<ul>
<li><p>&lt;EntityKey&gt;</p></li>
</ul></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Read</p></td>
<td><p>Same as Find.</p></td>
</tr>
<tr class="even">
<td><p>Update</p></td>
<td><p>Same as Delete.</p></td>
</tr>
</tbody>
</table>


## Details About Each Tag in the \<Body\> Section

The following sections discuss the tags in more detail.

### \<EntityKeyList\> Tag

The \<EntityKeyList\> tag section contains one or more \<EntityKey\> tags. The following is the correct syntax for the \<EntityKeyList\> tag (with a line break added to improve this display).

\<EntityKeyList xmlns = "http://schemas/microsoft.com/

dynamics/2008/01/documents/Message"\>

### \<EntityKey\> Tag

Each record in a table is uniquely identified by its value in the key field. In some tables the key is a set of two or more fields. The \<EntityKey\> tag section specifies the name and value for each key field. Each \<EntityKey\> section identifies at most one record.

The service class specified in the \<Action\> tag determines the table (or data source) that contains the records targeted by the \<EntityKey\>.

#### \<EntityKey\> Example

The following XML code is an example of the \<EntityKey\> tag section. It identifies the record that has a value of 4507 in its AccountNum field. Not shown is XML code elsewhere in the message that relates this \<EntityKey\> to the CustTable table.

``` xml
<EntityKey xmlns = "http://schemas.microsoft.com/
  dynamics/2006/02/documents/EntityKey">
 <KeyData>
  <KeyField>
   <Field>AccountNum</Field>
   <Value>4507</Value>
  </KeyField>
 </KeyData>
</EntityKey>
```

### \<serviceExternalName\> Tag

This tag is named for the document service that is specified in the \<Action\> tag.

### \<entityName\> Tag

This tag is the name of the table (or data source) that the inbound message operates against. Nested under this tag are tags for each field in the table (or a subset of those field tags).

Also, nested under this tag could be another \<entityName\> tag for a child table. This can occur for create and update \<Action\> operations. For example, under the \<SalesOrderTable\> tag there can be a \<SalesLine\> tag.

### \<QueryCriteria\> Tag

The \<QueryCriteria\> tag section contains one or more \<CriteriaElement\> tags. The \<QueryCriteria\> tag offers more flexibility than does the \<EntityKeyList\> tag. Unlike the \<EntityKeyList\> tag, the \<QueryCriteria\> tag never occurs in an outbound message.

For more information, see [Query Criteria Overview](query-criteria-overview.md).

### \<CriteriaElement\> Tag

For matching records, the \<CriteriaElement\> tag section can specify field-value pairs that are not limited to key fields. The \<CriteriaElement\> tag also offers several operators beyond the equals operator.

## XSD Validations

The XSD schemas that are used to validate all parts of each message are stored in the following directory where you installed Microsoft Dynamics AX:

  - Program files\\Microsoft Dynamics AX\\60\\Server\\MicrosoftDynamicsAX\\bin\\Application\\Share\\Include

For more information about XSD schema, see the following topics:

  - [Messages and transforms in AIF](messages-and-transforms-in-aif.md)

  - [Document Schema Rules](document-schema-rules.md)

  - [How to: Generate a Document Schema](how-to-generate-a-document-schema.md)

## See also

[AIF Messages](aif-messages.md)

[Query Criteria Overview](query-criteria-overview.md)

[Example: Fault in an Outbound Message](example-fault-in-an-outbound-message.md)

[Message Header](message-header.md)

