---
title: Developing with Services and AIF
TOCTitle: Developing with Services and AIF
ms:assetid: ef81f14f-a96a-43a0-9a58-dc8a2cda09e9
ms:mtpsurl: https://technet.microsoft.com/library/Hh509053(v=AX.60)
ms:contentKeyID: 37046472
author: tonyafehr
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Developing with Services and AIF 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX supports integration with the Application Integration Framework (AIF) components using the Microsoft Dynamics AX services programming model. You can customize the document services that are included with Microsoft Dynamics AX, create new custom services, and consume external web services. To support a range of option for customization and programmability, Microsoft Dynamics AX provides the following types of services:

  - Custom Services are services that you create to expose X++ logic through a service interface. You can use the business logic with inbound or outbound transfers.

  - Document Services represent data and business logic within Microsoft Dynamics AX. You can use or customize the over 70 standard Axd document services that are included with Microsoft Dynamics AX. If none of the standard document services meet your needs, you can create a new document service by using the **AIF Document Service Wizard**. Each document is represented by a class; the name of a document class is preceded by Axd. For example, AxdSalesOrder is the name of the document and also the name of the document class. The terms "document" and "Axd document" and "document class" are used interchangeably.

  - System Services cannot be customized. The Query Service, Metadata Service, and User Session Service are Windows Communication Foundation (WCF) services included with Microsoft Dynamics AX. They provide access to data returned in queries, metadata for AOT objects such as tables and extended data types (EDTs), and data about the calling user such as default language and default company.

Microsoft Dynamics AX enables you to consume external web services from X++ code, and to consume web services hosted by Microsoft Dynamics AX from .NET Framework languages such as Microsoft Visual C\#.

Security for document services called from an external client is based on the role-based security that is used in Microsoft Dynamics AX. For more information, see [About role-based security in services and AIF](about-role-based-security-in-services-and-aif.md) and [Security best practices for services and AIF](security-best-practices-for-services-and-aif.md).

Microsoft Dynamics AX supports application integration and data exchange in both intranet and Internet-facing scenarios. Services based on WCF classes are hosted on the AOS for applications to integrate within the intranet of a company. To consume or expose services over the Internet, you must install and use Internet Information Services (IIS). For more information about Microsoft Dynamics AX web services on IIS see [Install web services on IIS](install-web-services-on-iis.md).

## Distinguishing Between Service Types

The three types of services provided by Microsoft Dynamics AX can be used by Microsoft Dynamics AX components and third-party applications. You can use system services out-of-the-box to retrieve data in a query, metadata for objects in the AOT, and information about the calling user. You can use document services to exchange data for business entities defined by the standard documents in Microsoft Dynamics AX. For any custom requirements for application integration, you can customize existing documents, or create new document services and custom services.

The following table provides information about how to distinguish between the service types, based on deployment and usage parameters.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p></p></th>
<th><p>Document Services</p></th>
<th><p>Custom Services</p></th>
<th><p>System Services</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Service Definition and Data Contracts</p></td>
<td><p>Auto-generated based on underlying query and options entered in the <strong>AIF Document Service Wizard</strong>.</p></td>
<td><p>Defined by the developer.</p></td>
<td><p>Fixed and cannot be changed.</p></td>
</tr>
<tr class="even">
<td><p>Deployment Mode</p></td>
<td><p>Integration Ports</p></td>
<td><p>Integration Ports</p></td>
<td><p>Stand-alone service that is running at fixed address on the AOS</p></td>
</tr>
<tr class="odd">
<td><p>Hosted Location</p></td>
<td><p>AOS or IIS</p></td>
<td><p>AOS or IIS</p></td>
<td><p>AOS only</p></td>
</tr>
<tr class="even">
<td><p>Transport Protocol</p></td>
<td><p>Any supported adapter (for a list of supported adapters, see <a href="adapters.md">Adapters</a>)</p></td>
<td><p>Any supported adapter (for a list of supported adapters, see <a href="adapters.md">Adapters</a>)</p></td>
<td><p>Only NetTcp adapter</p></td>
</tr>
<tr class="odd">
<td><p>Usage</p></td>
<td><p>Use to expose a business entity through a service interface. All AIF framework artifacts can be applied on these services.</p></td>
<td><p>Use to expose any custom (including simple business entities) through a service interface. AIF framework supports transforms but not pipelines, schema constraints, or other data processing options.</p></td>
<td><p>Use to return metadata, data in a query, or user information. Metadata includes information about AOT objects in Microsoft Dynamics AX such as tables, services, extended data types (EDTs), enums, and so on.</p></td>
</tr>
</tbody>
</table>


## Exposing Business Entities as Services

Microsoft Dynamics AX installs with over 70 document services. The document services framework provides the **AIF Document Service Wizard** that generates a document service from the query that defines the business entity. To expose business logic through services, you use serialization with the Data Contract class and custom attributes.

The following table contains information that can help you to decide whether to use document services or custom data contract–based services.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Characteristic</p></th>
<th><p>Document Services</p></th>
<th><p>Custom Services</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Entity complexity</p></td>
<td><p>The <strong>AIF Document Service Wizard</strong> handles queries of any complexity and size and generates the service seamlessly.</p>
<p>For example, some queries contain data sources and relationships that include dimensions, polymorphism, date-effective information, and so on. The document services framework handles these types of queries seamlessly.</p></td>
<td><p>Suitable when the entity complexity is low. The schema can be written as a data contract class and relevant data member attributes set.</p>
<p>If tables and relationships are used in a data contract, then any feature around dimensions, polymorphism, and so on, must be handled in code by the developer.</p></td>
</tr>
<tr class="even">
<td><p>Performance requirements</p></td>
<td><p>The incoming XML is passed to the document services framework, which parses the XML to validate the AxD schema, and then invokes the relevant operation.</p>
<p>The framework enables customization to handle any complex pattern in the underlying query.</p></td>
<td><p>Custom services use the underlying .NET XML Serializer to serialize and de-serialize the XML into a data contract object. No other logic is present.</p>
<p>For simple entity schemas, this approach is faster than document services. For complex schemas, you may have to write a lot of custom code.</p></td>
</tr>
<tr class="odd">
<td><p>Integration requirements</p></td>
<td><p>All integration stack elements such as pipelines, transforms, and schema constraints can be applied to document services.</p></td>
<td><p>Schema constraints and value substitution are not honored for custom services.</p>
<p>However, transforms that convert between the AifXMLMessage format and other formats and pipelines for preprocessing and postprocessing of XML messages can be used.</p></td>
</tr>
<tr class="even">
<td><p>Flexibility in service contracts</p></td>
<td><p>Because the document service is derived from a query, changes to the query object or the data source schema might require a change the service contract.</p>
<p>The tight coupling between the service contract and the underlying query-table schema could be limiting for certain scenarios.</p></td>
<td><p>The data contracts are written by developers and can be controlled to make sure that the underlying schema changes do not have any effect on them.</p>
<p>The control that a developer has in defining the service contracts can be good for service clients.</p></td>
</tr>
<tr class="odd">
<td><p>Microsoft Office Add-ins support</p></td>
<td><p>Office Add-ins tools, included with Microsoft Dynamics AX, have built-in support for consuming document services for updating data.</p></td>
<td><p>No preinstalled integration with Office add-ins exists.</p></td>
</tr>
</tbody>
</table>


## Common Usage Scenarios

The following table summarizes some of the key scenarios for all the service types in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service Type</p></th>
<th><p>Common Scenarios</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Custom Services</p></td>
<td><p>Use to expose very simple business entities as a service, or to expose custom logic from Microsoft Dynamics AX.</p></td>
</tr>
<tr class="even">
<td><p>Document Services</p></td>
<td><p>Use to expose business entitles with varying degrees of complexity, or to support medium-to-complex integration scenario involving business entities.</p></td>
</tr>
<tr class="odd">
<td><p>System Service: Query Service</p></td>
<td><p>Use to implement read operations for any Microsoft Dynamics AX, ad-hoc, or existing AOT query.</p></td>
</tr>
<tr class="even">
<td><p>System Service: Metadata Service</p></td>
<td><p>Use to retrieve information about the structures in Microsoft Dynamics AX for a client application. For example, if you want to return information about a table such as what indexes exist on that table, you can use the metadata service.</p></td>
</tr>
<tr class="odd">
<td><p>System Service: User Session Service</p></td>
<td><p>Use to retrieve information about the user session.</p></td>
</tr>
</tbody>
</table>


For more information, see the following white papers:

  - [Services in Microsoft Dynamics AX 2012](https://www.microsoft.com/download/en/details.aspx?id=24742)

  - [Consuming Web Services](https://www.microsoft.com/download/en/details.aspx?id=24742)

## See also

[Services, service operations, and service groups](services-service-operations-and-service-groups.md)

[AIF Document Services](aif-document-services.md)

[AIF System Services](aif-system-services.md)

[Using Custom Services](using-custom-services.md)

[Services and AIF security and protection](services-and-aif-security-and-protection.md)

