---
title: About Document Service Classes
TOCTitle: About Document Service Classes
ms:assetid: 0bf0f772-4e99-4f37-96a3-ecb0eda6ae7a
ms:mtpsurl: https://technet.microsoft.com/library/Cc582145(v=AX.60)
ms:contentKeyID: 35240418
author: Khairunj
ms.author: daxcpft
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# About Document Service Classes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX exposes data for exchange with external systems through business logic exposed as services. The data and business logic together is called a document. This topic describes the document service classes that can be used by the Application Integration Framework (AIF) and the related data contract classes.

The document service classes are part of the XML Document Framework. This framework consists of the classes that implement the business logic for individual documents in Microsoft Dynamics AX. You can also use this framework to create your own custom documents that can be sent using AIF. As a group, these classes encapsulate the business logic for individual documents.

The XML Document Framework contains these types of classes:

  - Document service classes (with data contracts)

  - Axd \<Document\> classes (also known as Axd classes)

  - Ax \<Table\> classes

A document service class is the top-level class that provides an external interface that represents the business logic. Document service classes include the service classes and their related data contract classes.

## Document Service Classes

The service class is the top-level class that is exposed as a service through the Application Object Tree (AOT). You can view service classes in the **Classes** node in the AOT. The service classes are exposed as services, which you can view in **Services** node in the AOT. Each service class is derived from the AifDocumentService class. The service methods delegate their operations to the AifDocumentService class. For example, the SalesSalesOrderService.read method calls the AifDocumentService.readList method as shown in the following code.

```X++
public SalesSalesOrder read(AifEntityKeyList _entityKeyList)
    {
        SalesSalesOrder salesSalesOrder = new SalesSalesOrder();
        this.readList(_entityKeyList, salesSalesOrder);
        return salesSalesOrder;
    }
```

The service class implements the methods that are needed to perform operations on the data. These methods are exposed as service operations by the service. For more information, see [Document Class Service Operations](document-class-service-operations.md).

## Data Object Classes

Data objects provide a data contract for the XML data that is exchanged through AIF. The data object classes reflect the data hierarchy of the query that is the basis of an AIF document. These classes are used only to work with data; they contain no business logic. The data object classes are found in the **Classes** node in the AOT.

The following table shows how the relationship between the data sources, XML elements, and data object classes is modeled in for a subset of the data sources included in the Customer service.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Object</p></th>
<th><p>XML element</p></th>
<th><p>Data object class</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AxdCustomer query</p></td>
<td><p>&lt;Customer&gt;</p></td>
<td><p>CustCustomer</p></td>
</tr>
<tr class="even">
<td><p>CustTable data source</p></td>
<td><p>&lt;CustTable&gt;</p></td>
<td><p>CustCustomer_CustTable</p></td>
</tr>
<tr class="odd">
<td><p>DirParty data source</p></td>
<td><p>&lt;DirParty&gt;</p></td>
<td><p>CustCustomer_DirParty</p></td>
</tr>
</tbody>
</table>


### Document Data Object Class

The document data object class is the top-level data object and represents the whole XML document. The following list contains features of the document data object classes:

  - Implement the AifDocument class.

  - Encapsulate data being exchanged with AIF.

  - Passed as parameters to the update and create methods.

  - Used as the return value of the service class find and read methods.

For example, CustCustomer is the document data object and depends on the CustCustomer\_CustTable data object. The CustCustomer\_CustTable data object in turn depends on the CustCustomer\_DirParty data object.

Although the document data object class implements the AifDocument class, it is still considered a data object. This is because the AifDocument class implements the AfStronglyTypedDataContainer class, just as the data object classes do.

### Data Object Classes

The data object classes provide an object model for the service data. Data object classes implement the AifStronglyTypedDataContainer class which in turn implements the AifXmlSerializable interface.

There is a data object class for each data source in the query. For example, the customer data objects are the CustCustomer\_CustTable class and the CustCustomer\_DirParty class. The CustCustomer\_CustTable class depends on the CustCustomer\_DirParty class which models the relationship of this data in the database.

### Data Object Methods

Both the document data object and the data objects have three types of methods:

  - Exists methods - Verify that data exists for a particular field.

  - Accessor methods - Returns the value for a particular field.

  - Create methods - Creates and returns a list of data objects. For example, the CustCustomer document data object has a method called CreateCustTable. This method creates and returns an instance of the CustCustomer\_CustTable data object. Each of the CustCustomer\_CustTable data objects contains the data for a single customer record.

There are two types of accessor methods: simple and complex. A simple accessor method returns the value of a field. For example, the CustCustomer\_CustTable.parmAccountNum method returns the customer account number.

A complex accessor method returns a list of data objects. For example, the CustCustomer document data object has a method called parmCustTable that returns a list of CustTable objects. This method is useful when there are multiple records in the XML. For example, if you had an XML document that contains two customers, the data for each customer would be inside \<CustTable\> tags. There would be two CustTable data objects.

## See also

[Document Services Classes](document-services-classes.md)

[AIF Class Naming Conventions](aif-class-naming-conventions.md)

