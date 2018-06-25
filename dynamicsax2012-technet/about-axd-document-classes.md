---
title: About Axd<Document> Classes
TOCTitle: About Axd<Document> Classes
ms:assetid: bd346bfa-a56f-4aec-9146-993deed238e4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa862063(v=AX.60)
ms:contentKeyID: 35250018
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# About Axd\<Document\> Classes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the Axd \<Document\> classes that are included in Application Integration Framework (AIF). The Axd \<Document\> classes contain implementation details that support the document service classes.


> [!NOTE]
> <P>You do not have to know how the Axd&nbsp;&lt;Document&gt; classes interact with the other AIF objects. However, if you are creating custom services, this information may be helpful when writing code for your own classes.</P>



Each Axd \<Document\> class contains the business logic for a document. In addition, the document classes encapsulate any business logic that applies across tables and guarantee that the business rules that govern the life cycle of the document are followed. These classes represent data as business entities so that the calling application can exchange data with Microsoft Dynamics AX without any knowledge of the underlying tables in the database.

Within AIF, the terms Axd \<Document\> class, Axd class, and document are often used interchangeably.

## Axd\<Document\> Class Characteristics

The Axd \<Document\> classes have the following characteristics and functions:

  - Implement the AifServiceable interface.

  - Shield users from the complexity of the underlying table structures and associated business logic.

  - Elevate the error handling from the individual database tables or fields to the document level.

  - Provide methods for serializing to XML and for deserializing from XML. During serialization and deserialization, these classes can also perform value mapping and data filtering.

  - Generate an XML Schema Definition (XSD) schema that describes the equivalent XML document.

  - Access Ax \<Table\> classes. Axd \<Document\> classes call Ax \<Table\> classes and use them when serializing to XML and deserializing from XML. This guarantees that business logic within Microsoft Dynamics AX is always followed. Axd \<Document\> classes can invoke business logic internally, but the document classes that are supplied in the application rarely do.

### Functions of Axd\<Document\> Classes

The Axd \<Document\> class is responsible for maintaining the internal data for the document and for creating XML from that data. The responsibilities of the Axd \<Document\> class include the following:

  - Document structure – the document structure enables the Axd document classes to perform operations on a whole document, such as:
    
      - Reading a whole document in one service call by reading all elements that are defined by the associated Axd document query and then serializing them into a single XML file.
    
      - Creating a new document in the database in one operation by saving each element of the document to the database. The create operation is invoked, for example, when AIF processes a receive action.

  - XML serialization and deserialization – the document structure makes it possible for an Axd document class to perform the following:
    
      - Generate an XSD schema that is a one-to-one representation of itself.
    
      - Serialize the class instance into Microsoft Dynamics AX-specific XML.
    
      - Deserialize a class instance from Microsoft Dynamics AX-specific XML.

  - Document life cycle – guarantee that operations on the document do not violate the business rules that govern the document life cycle. For example, guarantee that a change order is not accepted if the original order has already shipped.

  - Document properties – maintain document-level information through properties. Properties provide information that pertains to the specific instance of a document. For example, the document status can describe whether the document is an original or a duplicate.

  - Cross-table dependencies – comply with business logic that applies to a document that contains data from multiple tables.

  - Error handling – consolidate errors that occur in the Ax \<Table\> classes and then provide the calling code with a consolidated list of all the errors in a document.

## Additional Characteristics of Axd\<Document\>Classes

The following are additional characteristics of Axd \<Document\> classes:

  - Typically, Axd document classes in Microsoft Dynamics AX have descriptive names that are prefixed with Axd, such as, AxdPurchaseRequisition or AxdSalesOrder. The list of document classes can be viewed **Classes** node in the AOT.

  - If an Axd \<Document\> class supports both inbound and outbound documents, it reads data from and writes data to the same tables. These tables can be represented by Ax \<Table\> classes.

  - The public properties of the Axd \<Document\> classes map to the fields of the underlying database tables of the corresponding Ax \<Table\> classes.

  - Axd \<Document\> classes provide access to the fields of the underlying Ax \<Table\> classes. By using the original field names, you can make sure that the serialized XML representation through the Axd \<Document\> and the Ax \<Table\> classes is consistent with the data model. Use the original field names when you debug to make sure that the serialized XML representation through the Axd \<Document\> and the Ax \<Table\> classes can be traced. The same fields are not renamed in the various elements.

  - Axd \<Document\> classes work with data in the application indirectly through Ax \<Table\> classes.

## Axd\<Document\> Class Properties

An Axd \<Document\> class has properties that are part of the document schema. Additional properties are exposed from the Ax \<Table\>classes. The following table describes the document-level properties.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Property</p></th>
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>docPurpose</p></td>
<td><p>XMLDocPurpose</p></td>
<td><p>Identifies whether the document is an original or a duplicate. Possible values are XMLDocPurpose::Original, XMLDocPurpose::Duplicate, or XMLDocPurpose::Proforma. These values are found in the XMLDocPurpose enum. Proforma designates a document that is not yet posted, such as an un-posted invoice being sent with an international shipment for tax declarations.</p></td>
</tr>
<tr class="even">
<td><p>senderId</p></td>
<td><p>senderId</p></td>
<td><p>Identifies the company from which the document originates. It is populated with the DataAreaId of the sender in all outbound documents.</p></td>
</tr>
<tr class="odd">
<td><p>validTimeStateType</p></td>
<td><p>Date or UtcDateTime</p></td>
<td><p>For retrieving data from valid time state tables, identifies the type of validation: AsOf or Range.</p></td>
</tr>
<tr class="even">
<td><p>validAsOfDateTime</p></td>
<td><p>Date or UtcDateTime</p></td>
<td><p>For records in valid time state tables, identifies the valid date and time as a single point in time.</p></td>
</tr>
<tr class="odd">
<td><p>validFromDateTime</p></td>
<td><p>Date or UtcDateTime</p></td>
<td><p>For records in valid time state tables, identifies the start of the valid time range.</p></td>
</tr>
<tr class="even">
<td><p>validToDateTime</p></td>
<td><p>Date or UtcDateTime</p></td>
<td><p>For records in valid time state tables, identifies the end of the valid time range.</p></td>
</tr>
</tbody>
</table>


## Axd\<Document\> Class Interfaces

The Axd \<Document\> classes inherit from the AxdBase class, which in turn implements the AifServiceable interface. A document class that you create must implement the AIFServicable interface to be recognized as an Axd \<Document\> class. The relationship between derived classes and the AifServiceable interface is shown in the following illustration.

![Derived Classes and the AifServicable Interface](images/Aa862063.AifServiceable(AX.60).gif "Derived Classes and the AifServicable Interface")

**Axd\<Document\> class hierarchy object model**

The AifServiceable interface contains methods that must be implemented by any document class that will be exposed by using AIF. The following table shows these methods.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AifDocumentName getName()</p></td>
<td><p>Returns the name of the document. This must match the root element name in the document's XML schema. Not localized.</p></td>
</tr>
<tr class="even">
<td><p>LabelString getLabel()</p></td>
<td><p>Returns the friendly name of the document. Localized.</p></td>
</tr>
<tr class="odd">
<td><p>AifDocumentSchemaXML getSchema()</p></td>
<td><p>Returns the XML schema that represents the Axd &lt;document&gt;.</p></td>
</tr>
<tr class="even">
<td><p>AifActionInfoList getActionList()</p></td>
<td><p>Returns a list of actions that are implemented by the document. An action is implemented if it has a method that matches the signature type of a particular action.</p></td>
</tr>
</tbody>
</table>


## See also

[Document Services Classes](document-services-classes.md)

[About Ax\<Table\> Classes](about-ax-table-classes.md)

