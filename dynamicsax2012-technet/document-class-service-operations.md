---
title: Document Class Service Operations
TOCTitle: Document Class Service Operations
ms:assetid: c36e9521-3a4e-48c2-a260-33c9b99a1527
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa864923(v=AX.60)
ms:contentKeyID: 35250119
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Document Class Service Operations [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the default service operations in the document service classes in Microsoft Dynamics AX. Application Integration Framework (AIF) exchanges data with external systems by sending and receiving XML documents. Each document being exchanged is represented by a document service class.

The document service classes included with Microsoft Dynamics AX have the service operations shown in the following table.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method</p></th>
<th><p>Parameters</p></th>
<th><p>Returns</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>create</p></td>
<td><p>Document object</p></td>
<td><p>AifEntityKeyList</p></td>
<td><p>Takes a document object, creates records in the database, and returns a list of the IDs for the new records.</p></td>
</tr>
<tr class="even">
<td><p>delete</p></td>
<td><p>AifEntityKeyList</p></td>
<td><p>Nothing</p></td>
<td><p>Takes one or more IDs and deletes the specified records from the database.</p></td>
</tr>
<tr class="odd">
<td><p>find</p></td>
<td><p>AifQueryCriteria</p></td>
<td><p>Document object</p></td>
<td><p>Takes criteria, queries the database for matching records, and returns them in a document object.</p></td>
</tr>
<tr class="even">
<td><p>findKeys</p></td>
<td><p>AifQueryCriteria</p></td>
<td><p>AifEntityKeyList</p></td>
<td><p>Takes criteria, queries the database for matching records, and returns a list of corresponding IDs for those records.</p></td>
</tr>
<tr class="odd">
<td><p>read</p></td>
<td><p>AifEntityKeyList</p></td>
<td><p>Document object</p></td>
<td><p>Takes one or more IDs, reads the records from the database, and returns the records.</p></td>
</tr>
<tr class="even">
<td><p>update</p></td>
<td><p>AifEntityKeyList and document object</p></td>
<td><p>Nothing</p></td>
<td><p>Takes one or more IDs and the data that corresponds to those IDs, and then updates the database. For more information, see <a href="updating-data-with-aif.md">Updating Data With AIF</a>.</p></td>
</tr>
<tr class="odd">
<td><p>getKeys</p></td>
<td><p>AifDocumentPaging</p></td>
<td><p>AifEntityKeyList</p></td>
<td><p>Retrieves the keys for documents based on a document filter. For more information, see <a href="configure-processing-options.md">Configure processing options</a>.</p></td>
</tr>
<tr class="even">
<td><p>getChangedKeys</p></td>
<td><p>AifDocumentPaging, changedDateTime</p></td>
<td><p>AifEntityKeyList</p></td>
<td><p>Retrieves the keys for documents based on a document filter and a date that is passed in. For more information, see <a href="configuring-aif-for-change-tracking.md">Configuring AIF for change tracking</a>.</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>Each service class implements only the methods that are necessary for the business requirements of the class. However, the AIF Document Service Wizard can generate code for all of the service operations. For more information, see <A href="creating-new-document-services.md">Creating New Document Services</A>.</P>



The document service class contains a method for each service operation. Each document service has an entry under the **Services** node in the Application Object Tree (AOT), and each method appears as an entry under the **Operations** node. Each service operation can be exposed through a basic or enhanced integration port. For more information, see [Integration ports](integration-ports.md).

Each method of a document service class has a method type attribute that specifies the type of action that the method performs. For example, the create method has the AifDocumentCreateAttribute attribute. For more information, see [Method Type Attribute](method-type-attribute.md).

## Document Service Operation Parameters

Document service operations may take one or more of the following objects as a parameter:

  - Document object - The top-level data object that represents a whole XML document. This object implements the AifDocument interface and contains the data that is required by the method. For example, when you call the SalesSalesOrder.create service operation, you must pass the sales order data in a document object.

  - AifEntityKeyList - An object that represents one or more key/value pairs that specify a single record. The key contains the name of the field that is the ID, and the value contains the ID value for the record. For example, when you send in a message to read a customer, the key field contains AccountNum and the value contains a numerical value, such as 5407. AIF uses this information to return the specified record from the CustTable table.

  - AifQueryCriteria - An object that represents a query in Microsoft Dynamics AX. Queries are used by the find, findKeys, getKeys, and getChangedKeys service operations to select the range of data that is returned by the method.

## Example

To see how service operations work, consider the CustCustomerService class. The following example shows the signature for the create method for the customer service,which is exposed as the create service operation:

   ```X++
   [AifDocumentCreateAttribute, SysEntryPointAttribute(true)]
   public AifEntityKeyList create(CustCustomer _custCustomer)
   ```

This method takes a CustCustomer parameter which is an object that contains the customer data. The return value is an AifEntityKeyList object that contains the IDs for the customers who were created. For more information, see [About Document Service Classes](about-document-service-classes.md).

## Custom Service Operations

You can add custom service operations to the document service classes that are included with Microsoft Dynamics AX. The service operation must follow these rules:

  - The method that is exposed as a service operation must be public.

  - If the service operation takes an object as a parameter or returns an object, that object class must implement the AifXmlSerializable interface.

  - Parameters or return values that are not objects must be one of the following primitive types: str, date, utcdatetime, guid, int, int64, enum, real, or void.

For more information about how to add a service operation to service, including a document service, see [How to: Add a Service Operation to a Service](how-to-add-a-service-operation-to-a-service.md). We recommend that you add the method type attribute to the service method if the method fits one of the following supported types: create, read, delete, update, find, findKeys, getKeys, or getChangedKeys. For more information, see [Method Type Attribute](method-type-attribute.md).

## Returning Large Data Sets

Calling the find service operation could return a large data set because it can return a large number of records at the same time. When it is possible to retrieve large result sets, it may be more efficient to use the findKeys and read methods together. First, pass the query to the findKeys method, which returns only the IDs of the matching records. Then, loop through the IDs, using each ID in a call to the read method, which returns the data for each record as a separate response.

## See also

[Query Criteria Overview](query-criteria-overview.md)

[AIF Messages](aif-messages.md)

