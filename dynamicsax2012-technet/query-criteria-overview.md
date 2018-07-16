---
title: Query Criteria Overview
TOCTitle: Query Criteria Overview
ms:assetid: fd2ed539-a9e7-4a6c-af2d-1fa05b5aa12e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa892862(v=AX.60)
ms:contentKeyID: 35254205
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- xml
---

# Query Criteria Overview 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the \<QueryCriteria\> tag in inbound messages for Application Integration Framework (AIF). The \<QueryCriteria\> tag occurs in the \<Body\> tag section of an inbound message. The \<QueryCriteria\> tag never occurs in outbound messages. For more information, see [Message Body](message-body.md).

The purpose of the \<QueryCriteria\> tag is to provide a flexible way to control which records are returned from an inbound message. The \<QueryCriteria\> tag is valid only in messages that have Find or FindKeys specified in their \<Action\> tag. The \<QueryCriteria\> section is more flexible than the \<EntityKeyList\> section.

## Example \<QueryCriteria\> Section

The following XML code illustrates an inbound message. The message has an \<Action\> tag (not shown) which contains the CustomerService service, and the FindKeys service operation. The code shows a \<QueryCriteria\> section that contains two \<CriteriaElement\> tags.

The system uses Boolean OR logic to connect all the \<CriteriaElement\> tags. This means that the record information returned in the outbound message comes from records that satisfy any one of the following \<CriteriaElement\> conditions.

``` xml
<QueryCriteria xmlns = "http://schemas.microsoft.com/
  dynamics/2006/02/documents/QueryCriteria">

 <CriteriaElement>
  <DataSourceName>CustTable</DataSourceName>
  <FieldName>Street</FieldName>
  <Operator>Range</Operator>
  <Value1>1</Value1>
  <Value2>5</Value2>
 </CriteriaElement>

 <CriteriaElement>
  <DataSourceName>CustTable</DataSourceName>
  <FieldName>Name</FieldName>
  <Operator>Equal</Operator>
  <Value1>Northwind Traders</Value1>
  <Value2/>
 </CriteriaElement>

</QueryCriteria>
```

## Tags in the \<CriteriaElement\> Section

The following table lists the tags that occur in the \<CriteriaElement\> section.


> [!NOTE]
> <P>All the tags are required except for &lt;Value2&gt;, which is required only when the Range operator is used.</P>



<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tag name</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>&lt;DataSourceName&gt;</p></td>
<td><p>The name of the table that is targeted for the search. The table must be the one that is targeted by the service that is specified in the &lt;Action&gt; tag.</p></td>
</tr>
<tr class="even">
<td><p>&lt;FieldName&gt;</p></td>
<td><p>The name of a field in the table.</p></td>
</tr>
<tr class="odd">
<td><p>&lt;Operator&gt;</p></td>
<td><p>One of several recognized operators, such as GreaterOrEqual or Range.</p></td>
</tr>
<tr class="even">
<td><p>&lt;Value1&gt;</p></td>
<td><p>The string representation of any value that is appropriate for the type of field specified.</p></td>
</tr>
<tr class="odd">
<td><p>&lt;Value2&gt;</p></td>
<td><p>The second operand, used only when the Range operator is used.</p></td>
</tr>
</tbody>
</table>


The following sections provide more details about some of the tags in the previous table.

### \<DataSourceName\> Value Aligned with Service

You can determine the correct XML tag name for any service that is specified in the \<Action\> tag. The determination process is described by the following steps, which use the service CustomerService as a specific example.

1.  Open the Inbound ports form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  Click **New** to create a new port.

3.  On the **Service contract customizations** FastTab, click **Service operations** to open the **Select service operations** form and select the **CustCustomerService.create** operation.

4.  Click the left arrow button to move selected service operations to the **Selected service operations** list and close the form.

5.  Select **Customize documents** and then click **Data policies** to open the **Document data policies** form.

6.  Click the **View schema** button.

7.  In the **Schema** window that is displayed, the name attribute of the first element is the name that you must use for the first tag under \<Body\>\<MessageParts\> in your inbound message. The name of the first element in our example is Customer, as is shown in the following schema code.
    
    ``` xml
    <xs:element name="Customer" type="tns:AxdCustomer" />
    ```

### \<Operator\> Values

The following table shows all the operators that are recognized as valid \<Operator\> tag values.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>&lt;Operator&gt; value</p></th>
<th><p>Analogous X++ operator</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Equal</p></td>
<td><p>==</p></td>
</tr>
<tr class="even">
<td><p>NotEqual</p></td>
<td><p>!=</p></td>
</tr>
<tr class="odd">
<td><p>Greater</p></td>
<td><p>&gt;</p></td>
</tr>
<tr class="even">
<td><p>GreaterOrEqual</p></td>
<td><p>&gt;=</p></td>
</tr>
<tr class="odd">
<td><p>Less</p></td>
<td><p>&lt;</p></td>
</tr>
<tr class="even">
<td><p>LessOrEqual</p></td>
<td><p>&lt;=</p></td>
</tr>
<tr class="odd">
<td><p>Range</p></td>
<td><p>&gt;= &amp;&amp; &lt;=</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>The Range operator cannot be used to query hidden or locked ranges for a data source or field. For more information about the status property on a query range, see <A href="https://technet.microsoft.com/en-us/library/aa842737(v=ax.60)">Query Properties</A>.</P>



## XSD Validations

The \<QueryCriteria\> section is validated against an XSD schema. You can retrieve XSDs for common schemas from the following directory where you installed Microsoft Dynamics AX:

Program files\\Microsoft Dynamics AX\\60\\Server\\MicrosoftDynamicsAX\\bin\\Application\\Share\\Include

## See also

[Message Body](message-body.md)

[Messages and transforms in AIF](messages-and-transforms-in-aif.md)

