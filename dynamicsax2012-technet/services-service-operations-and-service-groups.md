---
title: Services, service operations, and service groups
TOCTitle: Services, service operations, and service groups
ms:assetid: b8698332-a18d-4600-8451-d1008c1c6974
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731906(v=AX.60)
ms:contentKeyID: 35132828
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Services, service operations, and service groups 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the concepts of services, service operations, and service groups.

## Services

Application Object Server (AOS) is the Windows Communication Foundation (WCF) service host for Microsoft Dynamics AX 2012 services that are exposed to users and applications on an intranet.

To consume services over the Internet, you must host services on Internet Information Services (IIS). Services that are hosted on IIS use the WCF message routing service. IIS routes all service requests to AOS. All service requests are processed on AOS, regardless of whether they originate on the Internet or an intranet. AOS then returns a response to the service consumer via IIS. Exchanges that are configured to use Web services are processed synchronously and therefore are not queued. Microsoft Dynamics AX deploys the service that is based on Web Services Description Language (WSDL) to a subfolder of the virtual directory that is associated with the Web site that you provide.

Microsoft Dynamics AX 2012 supports the following three kinds of services:

  - Document services are query-based services that can be used to exchange data with external systems by sending and receiving XML documents. These documents represent business entities, such as customers, vendors, or sales orders. Document services were introduced in Microsoft Dynamics AX 4.0. For more information about document services, see [AIF Document Services](aif-document-services.md).

  - Custom services can be used by developers to expose any X++ logic, such as X++ classes and their members, through a service interface.

  - System services are provided by Microsoft Dynamics AX. System services include the Query service, the Metadata service, and the User Session service. System services are not customizable, and they are not mapped to any query or X++ code. For more information about system services, see [AIF System Services](aif-system-services.md).

## Service operations

A service operation is a named set of functionality that is offered by a service. For example, the service operation that creates a new sales order is named **SalesSalesOrderService.create**. A service can expose multiple service operations. The service operations that a service exposes can include custom service operations. The following table describes some of the common service operations for document services.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service operation</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>create</strong></p></td>
<td><p>This operation creates a record for a new item in the database. For example, for the sales order service, this operation creates a new sales order. Usually, this operation responds with an entity key that contains the ID of the new item. The new record that is created uses the field values from the record in the message.</p>
<p>An integration port can be configured to replace existing documents when this service operation is called. See <a href="configure-processing-options.md">Configure processing options</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>delete</strong></p></td>
<td><p>This operation deletes a record in the database. Only records in child tables can be deleted.</p></td>
</tr>
<tr class="odd">
<td><p><strong>find</strong></p></td>
<td><p>This operation searches for the specified database record.</p></td>
</tr>
<tr class="even">
<td><p><strong>findKeys</strong></p></td>
<td><p>This operation retrieves a list of entity keys that correspond to the specified search criteria. For example, a request can contain a query for customers whose last name starts with the letter T. The response to this query contains a list of key fields and values that you can use to query again for additional data. For example, you can use the key fields to update each customer record in the list that you retrieved.</p></td>
</tr>
<tr class="odd">
<td><p><strong>read</strong></p></td>
<td><p>This operation retrieves the specified records from the database. The records that must be read are specified by using entity keys. The response contains the data for the records that are returned.</p></td>
</tr>
<tr class="even">
<td><p><strong>update</strong></p></td>
<td><p>This operation updates a record in the database. Only the fields that are contained in the message are updated. Values for all other database fields remain unchanged.</p></td>
</tr>
</tbody>
</table>


When you configure an integration port, you must know which service operations have to be exposed from the port.

## Service groups

A service group is a collection of services that are frequently consumed and managed together. All the services in a service group are published in a single WSDL file. Publishing to a single WSDL file simplifies how developers consume services in their code.

A developer can create a service group in the Application Object Tree (AOT). Developers can use the **AutoDeploy** property to specify whether the service groups that they create are automatically deployed and activated when they are created. You must manually deploy and activate any service groups that are not automatically activated.

Service groups are associated only with basic inbound integration ports.

## See also

[Customize service contracts](customize-service-contracts.md)

[Services and AIF architecture](services-and-aif-architecture.md)

