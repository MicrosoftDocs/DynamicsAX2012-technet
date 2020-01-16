---
title: Message Header
TOCTitle: Message Header
ms:assetid: d290df0a-0902-49c3-a732-b2b85eb92fb3
ms:mtpsurl: https://technet.microsoft.com/library/Aa872025(v=AX.60)
ms:contentKeyID: 35251912
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Message Header 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the \<Header\> tag section of inbound and outbound messages in Application Integration Framework (AIF). For more information about AIF messages, see [AIF Messages](aif-messages.md).


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R2.</P>



## XSD Schema Validation

In the message XML, the \<Header\> tag is nested one level under the \<Envelope\> tag. The \<Header\> section in inbound and outbound messages must validate against the same XSD schema. The XSD is stored in the database in the AifSchemaStore table. The XSD schema for the \<Header\> section is duplicated in the file Message.xsd that is included with Microsoft Dynamics AX under the installation directory. For more information, see [Messages and transforms in AIF](messages-and-transforms-in-aif.md).

## Table of Contained Tags

The following table lists all the tags that can appear in the \<Header\> tag section. All tags are optional unless they are described as required in the table. The tags must appear in the same sequence they are listed in the table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tag name</p></th>
<th><p>Inbound description</p></th>
<th><p>Outbound description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>&lt;MessageId&gt;</p></td>
<td><p>This value uniquely identifies each message. If you do not provide a MessageId value, AIF generates one when the message is received.</p>
<p>The value is a GUID that is not case sensitive. As an option, the value can be bounded by braces (the two characters {}).</p>
<p>The value is replicated in the &lt;RequestMessageId&gt; tag of the corresponding outbound message. You can use this value to locate the particular message on the <strong>Exceptions</strong>, <strong>Queue manager</strong>, and <strong>History</strong> forms. For more information, see <a href="monitoring-services-and-aif.md">Monitoring services and AIF</a>.</p>
<p>By default, the inbound message is rejected if the system has seen this same &lt;MessageId&gt; value before for create, delete, and update service operations for the document services included with Microsoft Dynamics AX. For more information, see <a href="how-to-enable-checking-for-duplicate-messages.md">How to: Enable Checking for Duplicate Messages</a>.</p></td>
<td><p>The system generates a unique GUID value for each outbound message.</p></td>
</tr>
<tr class="even">
<td><p>&lt;LogonAsUser&gt;</p></td>
<td><p>This is the name of the authorized Microsoft Dynamics AX user on whose authority the inbound request is being made.</p>
<p>The value must be a valid Microsoft Dynamics AX user or user group expressed as a string in the format “Domain\User.”</p>
<p>This value is used when trusted intermediaries are configured for an integration port using the <strong>AIF trusted intermediaries</strong> form. For more information, see <a href="configure-security-for-integration-ports.md">Configure security for integration ports</a>.</p></td>
<td><p>The inbound value is repeated in the outbound message.</p></td>
</tr>
<tr class="odd">
<td><p>&lt;Company&gt;</p></td>
<td><p>This is a string value that identifies the company to use when you are retrieving data in a query from Microsoft Dynamics AX.</p>
<p>If no company is specified, the default company is used.</p></td>
<td><p>If an explicit value was given for the &lt;Company&gt; in the inbound message, that value is reused for the &lt;Company&gt; in the corresponding outbound message.</p></td>
</tr>
<tr class="even">
<td><p>&lt;Action&gt;</p></td>
<td><p>This tag is required.</p>
<p>The value is a string that contains information that uniquely identifies the service operation to the system.</p></td>
<td><p>This tag is required. The value is identical to the inbound value.</p></td>
</tr>
<tr class="odd">
<td><p>&lt;ConversationId&gt;</p></td>
<td><p>This is a string value that several inbound messages have in common to force AIF to process only one message in the set at a time. The messages in the conversation are processed sequentially even when the channel is configured for parallel processing.</p>
<p>The maximum length of the string is 256 characters.</p>
<p>If no value is specified, a setting on the port determines whether the messages are processed sequentially or in parallel. For more information, see <a href="configure-processing-options.md">Configure processing options</a>.</p>
<p>For more information about how conversation IDs work with batched messages, see <a href="processing-batched-messages-in-aif.md">Processing batched messages in AIF</a>. For more information about how conversation IDs are used in parallel processing scenarios, see <a href="sequential-and-parallel-processing-in-services-and-aif.md">Sequential and parallel processing in services and AIF</a>.</p></td>
<td><p>The same value as was in the corresponding inbound message.</p></td>
</tr>
<tr class="even">
<td><p>&lt;RequestMessageId&gt;</p></td>
<td><p>Does not apply to inbound messages.</p></td>
<td><p>AIF puts the &lt;MessageId&gt; value from the inbound message into this tag. This enables you to determine which outbound message corresponds to your inbound message.</p></td>
</tr>
<tr class="odd">
<td><p>&lt;PartitionKey&gt;</p></td>
<td><p>This is a string value that specifies the partition for the data that is used in the service operation.</p>
<p>The default value for PartitionKey is the data partition that is set for the calling user. For more information about data partitions, see <a href="data-partitioning-architecture.md">Data partitioning architecture</a>.</p>
<p>This option is available only if Microsoft Dynamics AX 2012 R2 is installed.</p></td>
<td><p>If an explicit value was given for the &lt;PartitionKey&gt; in the inbound message, that value is reused for the &lt;PartitionKey&gt; in the corresponding outbound message.</p>
<p>This option is available only if Microsoft Dynamics AX 2012 R2 is installed.</p></td>
</tr>
</tbody>
</table>


## Elements of the \<Action\> Tag

The \<Action\> tag consists of three elements: the namespace, the external name of the service, and the service operation, or method on the service class. The following example is for the Customer Service (that is, the CustCustomerService class), shown with line breaks to improve readability:

\<Action\>http://schemas.microsoft.com/dynamics/2008/01/

services/CustomerService/

read\</Action\>

The following table shows the elements of the \<Action\> tag for the example.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Element</p></th>
<th><p>Portion of the &lt;Action&gt; value</p></th>
<th><p>Location in AOT</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Namespace</p></td>
<td><p>http://schemas.microsoft.com/</p>
<p>dynamics/2008/01/services/</p></td>
<td><p>Under the <strong>Services</strong> node, on the <strong>CustCustomerService</strong> node, the <strong>Namespace</strong> property.</p></td>
</tr>
<tr class="even">
<td><p>Service Name</p></td>
<td><p>CustomerService</p></td>
<td><p>Under the <strong>Services</strong> node, on the <strong>CustCustomerService</strong> node, the <strong>ExternalName</strong> property.</p></td>
</tr>
<tr class="odd">
<td><p>Service Operation</p></td>
<td><p>read</p></td>
<td><p>Under the <strong>Services</strong> node, under the <strong>CustCustomerService</strong> node, under the <strong>Operations</strong> node, on the <strong>Read</strong> node, the <strong>Name</strong> property.</p>
<p>Another property is the name of the <strong>Method</strong> on the service class. Usually the <strong>Name</strong> and <strong>Method</strong> properties have the same value.</p></td>
</tr>
</tbody>
</table>


The items specified in the \<Action\> tag determine the XSD schemas that the \<Body\> tag contents must comply with.

### \<Action\> Tag: Service Class

The services that are exposed by Microsoft Dynamics AX are listed on the **Select service operations** form. To view the available service operations, click **Service operations** on the **Service contract customizations** FastTab for any inactive inbound or outbound integration port. For more information, see [Customize service contracts](customize-service-contracts.md). Every service that is listed on that form is also listed in the AOT in the **Services** node.

### \<Action\> Tag: Service Operation for Document Services

The following table lists the service operations that are available for document services.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service operation name</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>create</p></td>
<td><p>Inserts new records into the database.</p></td>
</tr>
<tr class="even">
<td><p>delete</p></td>
<td><p>Deletes records from the database.</p></td>
</tr>
<tr class="odd">
<td><p>find</p></td>
<td><p>Reads complete data from records that match the specified fields and values.</p></td>
</tr>
<tr class="even">
<td><p>findKeys</p></td>
<td><p>Reads the key values from records that match the specified fields and values.</p></td>
</tr>
<tr class="odd">
<td><p>read</p></td>
<td><p>Reads complete data from records that match the specified key values. Read is a subset of the Find functionality, with slightly less verbose syntax.</p></td>
</tr>
<tr class="even">
<td><p>update</p></td>
<td><p>Modifies data in existing records, which are selected by the specified key values.</p></td>
</tr>
<tr class="odd">
<td><p>getKeys</p></td>
<td><p>Returns only the key values for the entities returned in a query.</p></td>
</tr>
<tr class="even">
<td><p>getChangedKeys</p></td>
<td><p>Returns only the key values for the entities that have changed after the specified timestamp.</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td></td>
</tr>
</tbody>
</table>


Each type of \<Action\> message can affect zero, one, or many records.

For more information about service operations for document services, see [Document Class Service Operations](document-class-service-operations.md).

## See also

[Using the Call Context](using-the-call-context.md)

[View the exceptions log](view-the-exceptions-log.md)

[View the document history](view-the-document-history.md)

[Edit and resubmit messages in the AIF gateway queue](edit-and-resubmit-messages-in-the-aif-gateway-queue.md)

