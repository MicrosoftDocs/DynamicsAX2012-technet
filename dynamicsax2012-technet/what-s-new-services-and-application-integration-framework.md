---
title: "What's new: Services and Application Integration Framework"
TOCTitle: Services and Application Integration Framework
ms:assetid: de2a9f9a-b1b4-4042-819d-10295b972079
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527243(v=AX.60)
ms:contentKeyID: 59623371
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Services and Application Integration Framework 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the enhancements to services and Microsoft Dynamics AX Application Integration Framework (AIF) in Microsoft Dynamics AX 2012. Services now provide a first-class programming model for integration and enable the Microsoft Dynamics AX application to expose its functionality through services that are based on Windows Communication Foundation (WCF).

## New functionality

AX 2012 introduces integration ports for streamlined configuration of services. AX 2012 also provides significant improvements in the programming model, deployment, and administration.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>In this topic</strong></p>
<p>New features in Cumulative Update 6 for Microsoft Dynamics AX 2012</p>
<ul>
<li><p>Support for deploying Microsoft Dynamics AX services to the Windows Azure Service Bus adapter</p></li>
<li><p>Support for creating mobile applications</p></li>
</ul>
<p>New features in Microsoft Dynamics AX 2012 R2</p>
<ul>
<li><p>Support for data partitions</p></li>
<li><p>WCF configuration</p></li>
<li><p>Additions to standard document services</p></li>
<li><p>Support for optional replacement fields for a surrogate foreign key</p></li>
</ul>
<p>New features in Microsoft Dynamics AX 2012</p>
<ul>
<li><p>Framework changes</p></li>
<li><p>Installation of services and AIF</p></li>
<li><p>Upgrade considerations</p></li>
<li><p>Deploying services on a web farm</p></li>
<li><p>Security changes</p></li>
<li><p>Administration changes</p></li>
<li><p>Improvements in services and AIF development</p></li>
<li><p>Improvements in troubleshooting</p></li>
</ul></td>
</tr>
</tbody>
</table>


## New features in cumulative update 6 for Microsoft Dynamics AX 2012

The following features have been added in cumulative update 6.

## Support for deploying Microsoft Dynamics AX services to the Windows Azure Service Bus

In cumulative update 6, you can publish services to the Service Bus. The Service Bus adapter enables integration between AX 2012 and cloud computing platforms. You can develop mobile, cloud-based, and enterprise applications that communicate securely with AX 2012 over the Internet or through external networks by using the Service Bus adapter. The Service Bus acts as a message relay by enabling messages from the Internet to reach Microsoft Dynamics AX service endpoints on a private enterprise network and enabling responses from the private network to reach the intended client over the Internet.

For information about how to configure AX 2012 to publish services by using the Service Bus adapter, see the blog post [Microsoft Dynamics AX Services and Windows Azure Service Bus](http://go.microsoft.com/fwlink/?linkid=306178%26clcid=0x409).

## Support for creating mobile applications

Mobile applications let you perform a wide variety of business processes, such as submitting expense reports and timesheets, from anywhere. For a walkthrough of a sample app for employee expense capture, see [Developing secure mobile apps for Microsoft Dynamics AX 2012](developing-secure-mobile-apps-for-microsoft-dynamics-ax-2012.md).

## New features in Microsoft Dynamics AX 2012 R2

The following features have been added in AX 2012 R2.

## Support for data partitions

An AX 2012 R2 installation might consist of multiple data partitions. The administration of AIF remains centralized. System administrators can view and modify service documents for all partitions.

AIF provides the following features that are related to data partitions:

  - Administration forms, such as **Queue manager**, **History**, and **Exceptions**, let system administrators view the status of the service operation infrastructure for all partitions. Each entry includes a **Partition key** field that identifies the related partition.

  - The **Inbound ports** form lets system administrators restrict an enhanced port to a specified partition.

  - The new data partitioning feature affects the way that data is accessed by service operations in Microsoft Dynamics AX. Each service request must contain information that identifies a specific partition. If you do not specify a partition in the call context or message header XML, AIF uses the default partition for the calling user.

  - The call context, the schema for the message header, and the administration form for inbound ports have been changed so that you can now restrict service requests to a specific partition. For more information, see [Using the Call Context](using-the-call-context.md) and [Message Header](message-header.md).

For more information about data partitioning, see the following topics:

  - [Data partitioning architecture](data-partitioning-architecture.md)

  - [AIF inbound ports (form)](https://technet.microsoft.com/en-us/library/hh208821\(v=ax.60\))

  - [Configure security for integration ports](configure-security-for-integration-ports.md)

  - [Security best practices for services and AIF](security-best-practices-for-services-and-aif.md)

## WCF configuration

The **Inbound ports** form includes a new button that lets you configure WCF settings for specific integration adapters. For more information, see [Configure addresses for enhanced integration ports](configure-addresses-for-enhanced-integration-ports.md) and [AIF inbound ports (form)](https://technet.microsoft.com/en-us/library/hh208821\(v=ax.60\)).

## Additions to standard document services

You can now use services to import various types of transactions, import bank statements, maintain budget plans, import earnings statements from external systems, and forecast warehouse workload capacity and space utilization. You can also read, create, and update worker information in the **Human resources** module by using external systems.

The following services are new in AX 2012 R2:

  - Advanced ledger entry

  - Bank statement

  - Budget plan

  - Customer collection letters for Norway

  - Payroll earnings import

  - Worker import

  - Warehouse space utilization forecast

  - Warehouse workload capacity forecast

For more information, see [Standard Document Services](standard-document-services.md).

## Support for optional replacement fields for a surrogate foreign key

In AX 2012 R2, AIF supports optional replacement fields for a surrogate foreign key that has multiple replacement fields. In other words, a replacement field is optional if the referring surrogate foreign key field is specified as non-mandatory on the table.

In earlier versions of Microsoft Dynamics AX, AIF treated all surrogate foreign key replacement fields as mandatory. Therefore, for outbound transfers, earlier versions of Microsoft Dynamics AX serialized each field when Axd documents were sent. However, in external clients that were written to use outbound document services in earlier versions of Microsoft Dynamics AX, fields that were previously mandatory are now optional and can be missing from the XML message.

## New features in AX 2012

The following features have been added or changed in AX 2012.

## Framework changes in AX 2012

This section describes new features and enhancements that were made to the framework in AX 2012.

## WCF adapters

This release of Microsoft Dynamics AX provides expanded support for WCF beyond the basic HTTP and HTTPS bindings. The proprietary Microsoft Message Queuing (MSMQ) and Microsoft BizTalk Server adapters that were used in the earlier releases of Microsoft Dynamics AX are no longer available. Instead, AX 2012 provides equivalent native WCF functionality. However, custom adapters that customers and partners developed by using the AIF adapter framework are still supported in this release.

## Services are hosted on Application Object Server

Microsoft Dynamics AX Application Object Server (AOS) is the WCF service host for AX 2012 services that are exposed to users and applications on an intranet. To consume services over the Internet, you must host services on Internet Information Services (IIS).

For more information about services, see [Services, service operations, and service groups](services-service-operations-and-service-groups.md).

## IIS services are hosted without .NET Business Connector

In the previous release of Microsoft Dynamics AX, services that were hosted on IIS required .NET Business Connector to communicate with AOS. In AX 2012, IIS-hosted services use the WCF routing service instead of .NET Business Connector.

For more information about services, see [Services, service operations, and service groups](services-service-operations-and-service-groups.md).

## Integration ports

In AX 2012, integration ports provide simplified administration of services and AIF. The concept of integration ports replaces AIF endpoints and related concepts that were used in earlier releases of Microsoft Dynamics AX. Each integration port can expose one or more services, and each integration port has a unique Uniform Resource Identifier (URI) that identifies the address of the port.

For more information about the concept of integration ports, see [Integration ports](integration-ports.md).

## Batched messaging

In AX 2012, you can submit large amounts of data by using the batch XML schema. This schema lets you group single messages into message sets that can be submitted together by using a single XML document. For more information about batched messaging, see [Processing batched messages in AIF](processing-batched-messages-in-aif.md).

## Change tracking

In AX 2012, you can configure the database to track changes that occur at the table level. You can then use the **getChangedKeys** service operation to retrieve entity keys for only those documents that have changed, based on specific criteria, such as the date and time. For more information about how to configure change tracking, see [Configuring AIF for change tracking](configuring-aif-for-change-tracking.md).

## Performance improvements in services and AIF

The following list describes enhancements to services and AIF that improve performance:

  - To achieve scale and redundancy, you can configure AOS servers to use Network Load Balancing (NLB) for Microsoft Dynamics AX services. The AOS clustering solution affects only the RPC-based connections and does not let you load balance Microsoft Dynamics AX services. For more information, see [Configuring network load balancing for services](configuring-network-load-balancing-for-services.md).

  - Client applications can access services via the WCF runtime, without using .NET Business Connector. .NET Business Connector was required for services and AIF in earlier releases of Microsoft Dynamics AX.

  - A deployment on an intranet does not require IIS, because services are now hosted on AOS by default.

  - You can host services on IIS for requests that originate from the Internet. However, the routing service on IIS dispatches these requests to the AOS host. All service requests, regardless of origin, are processed on AOS.

  - The services framework uses connection pooling to reduce the overhead of creating and destroying a session on service calls.

  - All the service references are placed in a single Web Services Description Language (WSDL) file. The single WSDL file lets developers reuse types when Microsoft Dynamics AX services are consumed.

## Installation of services and AIF

To expose services on the Internet by using the HTTP protocol, you must install the Web services on IIS feature. For more information, see [Install web services on IIS](install-web-services-on-iis.md).

The **Initialization checklist** helps you set up AIF. In this single initialization step, you register services, adapters, and basic ports.

## Upgrade considerations

In AX 2012, enhancements to the services framework significantly change functionality, configurations, database schemas, and document schemas (XSDs). When you plan an upgrade from earlier releases of Microsoft Dynamics AX, consider the following points:

  - You must recompile and test all applications that used the earlier release of Microsoft Dynamics AX to make sure that the applications work with services in AX 2012.

  - AX 2012 replaces the proprietary MSMQ and BizTalk Server adapters with equivalent functionality that is available in WCF. You must reconfigure and then recompile any automated integration processes that used these adapters, such as the BizTalk Server orchestration.

  - The upgrade framework creates partially configured integration ports that are based on existing endpoints. Newly created integration ports contain data policies and service operations, but you must provide address information and activate the ports. After you successfully complete the upgrade, you must configure the integration ports before you use AX 2012 services and AIF functionality.

For information about how to upgrade from earlier releases of Microsoft Dynamics AX, see the [Upgrade Guide](https://connect.microsoft.com/dynamicsax6tap/downloads).

## Deploying services on a web farm

Use the IIS Web Deployment Tool to manage multiple sites and web farm scenarios. Download the tool from the [Web Deploy](http://www.iis.net/extensions/webdeploymenttool) page.

## Security changes

AX 2012 offers a robust and flexible security framework. Users are granted access to Microsoft Dynamics AX based on their assigned role. For more information, see [Services and AIF security and protection](services-and-aif-security-and-protection.md).

Services and AIF rely on WCF for additional security. You can change the WCF configuration to configure the security settings that are required by Microsoft Dynamics AX services. WCF is responsible for authenticating the user. Service-level authorization is defined by the configuration of the integration ports.

## Administration changes

The following table describes the changes to the functionality and configuration of services and AIF in AX 2012 that affect system administrators.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Microsoft Dynamics AX 2009 functionality</p></th>
<th><p>AX 2012 functionality</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Configuration is company specific.</p></td>
<td><p>Configuration is not company specific.</p></td>
<td><p>In earlier releases, each AIF endpoint was associated with a specific company. AX 2012 does not require that you associate integration ports with a specific company. You can use the integration port functionality to restrict service calls to a specific company. For an inbound message, the services framework obtains the company ID from the message header. If the message header does not contain a company ID, AIF uses the default company for the submitting user.</p></td>
</tr>
<tr class="even">
<td><p>AIF endpoint</p></td>
<td><p>Integration port</p></td>
<td><p>The concept of integration ports replaces AIF endpoints and AIF configuration forms.</p></td>
</tr>
<tr class="odd">
<td><p>Data policies are mandatory.</p></td>
<td><p>Data policies are optional.</p></td>
<td><p>In earlier releases of Microsoft Dynamics AX, you had to manually assign data policies for each endpoint action policy. In AX 2012, configuration of data policies is optional. The default data policy is defined by the service schema that is defined by the service developer. You can use integration ports to enforce data policies.</p></td>
</tr>
</tbody>
</table>


## Improvements in services and AIF development

This feature has changed considerably since AX 2009. Many new capabilities have been added to support application development and integration with Microsoft Dynamics AX through services.

New features have been added that enable X++ business logic to be exposed as services, and that enable X++ to consume services. In addition to programming model changes, AIF has been updated so that developers can create transformations of non-XML data. AIF system services now let you retrieve information about users or metadata, and also run queries.

The following list contains a summary of the new feature areas for developers:

  - Services Enhancements

  - Service Groups

  - Support for Data Model Changes

  - SysOperation Framework

  - Support for Non-XML Files

  - SOAP Headers

  - Consume External Services in X++

  - System Services

  - Support for New Document Service Operations GetKeys and GetChangedKeys

## Services enhancements

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>X++ business logic can easily be exposed as a service.</p></td>
<td><p>X++ classes could be exposed as a service only if they implemented a service interface.</p></td>
<td><p>X++ classes and members can be exposed as services and service operations by using attributes.</p></td>
<td><p>You can easily expose X++ business logic to external systems as a service. Therefore, existing X++ code investments can be reused.</p></td>
<td><p><a href="using-custom-services.md">Using Custom Services</a></p></td>
</tr>
<tr class="even">
<td><p>Services support data contracts of any type.</p></td>
<td><p>Only classes that implemented the AifSerializable interface could be used as service data contracts.</p></td>
<td><p>Any .NET or X++ native type, such as str or int, can be used as a data contract. Any class that uses the AIF data contract attributes can be used as a data contract.</p></td>
<td><p>You can more easily develop services, because you can use all native types and complex types as data contracts.</p></td>
<td><p><a href="using-data-contracts-in-x.md">Using Data Contracts in X++</a></p></td>
</tr>
<tr class="odd">
<td><p>Support for X++ types in data contracts</p></td>
<td><p>The feature was not available.</p></td>
<td><p>Data contracts can now use X++ container types and strongly typed X++ collections, such as Set or Array.</p></td>
<td><p>Because complex X++ types are supported, more complex data scenarios can be supported in services.</p></td>
<td><p><a href="using-data-contracts-in-x.md">Using Data Contracts in X++</a></p></td>
</tr>
</tbody>
</table>


## Service groups

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The capability to group services by using service groups was added to the Microsoft Dynamics AX Application Object Tree (AOT).</p></td>
<td><p>Services were managed at the individual service level.</p></td>
<td><p>A service group is a collection of services that are frequently consumed and managed together. All services in a service group are published in a single WSDL file.</p></td>
<td><p>You just have to add a reference to a single WSDL file to gain access to the service proxies for all the services in that service group. Service groups enable type sharing for simple types that are common across various services in a service group. For example, if two services in a service group take a parameter that is an enum or an extended data type (EDT), the parameter is shared and can be seamlessly passed between the two services. However, complex types, such as <strong>Address</strong>, are not shared.</p></td>
<td><p><a href="services-service-operations-and-service-groups.md">Services, service operations, and service groups</a></p></td>
</tr>
</tbody>
</table>


## Support for data model changes

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Extensive data model changes are supported by AIF.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>The document services framework supports the data model changes that are implemented in AX 2012. The document services framework handles the following scenarios to produce a usable data contract schema:</p>
<ul>
<li><p>The framework replaces a surrogate foreign key (SFK) with the natural key for a specific table relationship. Therefore, the service contract has user-friendly, readable fields instead of obscure SFKs.</p></li>
<li><p>The framework handles all queries that contain the global address book (GAB) views as a data source.</p></li>
<li><p>The framework supports query data source tables that implement table inheritance.</p></li>
<li><p>The framework supports query data sources that contain tables that have date-effective fields.</p></li>
<li><p>The framework handles query data sources that contain tables that have dimension columns. The framework supports serialization and deserialization of the dimension columns across the service boundary.</p></li>
<li><p>The wizards that are used to create and update document services support these data model changes.</p></li>
</ul></td>
<td><p>AIF fully supports data model features. Therefore, data contracts are easier to use.</p></td>
<td><p><a href="what-s-new-aos-and-database-for-developers-in-microsoft-dynamics-ax-2012.md">What's New: AOS and Database for Developers in Microsoft Dynamics AX 2012</a></p></td>
</tr>
</tbody>
</table>


## SysOperation Framework

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>SysOperation Framework replaces the RunBase framework.</p></td>
<td><p>Only the RunBase framework was available. The user interface, business logic code, and data contract code were all contained in a single class.</p></td>
<td><p>SysOperation framework classes separate the user interface, business logic, and data contract logic.</p></td>
<td><p>You can use SysOperation framework classes to write applications that have reduced client to server communication. The user interface for input parameters can be auto-generated.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg862488(v=ax.60)">SysOperation Framework Overview</a></p></td>
</tr>
</tbody>
</table>


## Support for non-XML files

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AIF supports the import and export of data in non-XML formats.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>Data that is not XML, such as a comma-delimited file, can now be imported into and exported from Microsoft Dynamics AX. Developers can create custom transformations that transform non-XML data into a format that can be consumed by AIF. Custom transformations can be implemented by using an XSLT or a .NET DLL that implements the ITransform interface.</p></td>
<td><p>AIF can work with non-XML data, and you can handle all data transformations in Microsoft Dynamics AX.</p></td>
<td><p><a href="messages-and-transforms-in-aif.md">Messages and transforms in AIF</a></p></td>
</tr>
</tbody>
</table>


## SOAP headers

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>You can pass data into a service by using the SOAP header.</p></td>
<td><p>Developers had to manually add custom code for SOAP headers.</p></td>
<td><p>SOAP headers have been extended. There is now a strongly typed parameter that is part of the service contract.</p>
<p>You can add SOAP headers when you call a service to pass additional data into the service. The following SOAP headers are supported:</p>
<ul>
<li><p>Company – The calling user’s default company.</p></li>
<li><p>Language – The calling user’s default language.</p></li>
<li><p>Logon As User – The Microsoft Dynamics AX user who performs the service operation. By default, the submitting user (calling user) is used, in the format “domain\user.”</p></li>
</ul></td>
<td><p>Extended SOAP headers let developers provide more contextual information to a service when the client calls that service.</p></td>
<td><p><a href="using-the-call-context.md">Using the Call Context</a></p></td>
</tr>
</tbody>
</table>


## Consuming external services in X++

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Consume external web services from X++ without adding a service reference in the AOT.</p></td>
<td><p>You could consume an external web service from X++, but you first had to add a service reference in the AOT. External services could be consumed only in limited scenarios. For example, server authentication was not supported.</p></td>
<td><p>The <strong>Service References</strong> node has been removed from the AOT. You add a service reference in a .NET project and then add that project to the model store. Then you can access the external service from X++ code.</p></td>
<td><p>There is now full support for web services that have complex schemas, and also support for web service authentication. Because of the comprehensive deployment functionality in Microsoft Visual Studio, your service references are automatically deployed when you configure them for automatic deployment.</p></td>
<td><p><a href="consuming-external-web-services.md">Consuming External Web Services</a></p></td>
</tr>
</tbody>
</table>


## System services

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use system services to interact with and retrieve Microsoft Dynamics AX information.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>System services are WCF services that are included with Microsoft Dynamics AX. The system services include the following services:</p>
<ul>
<li><p>Metadata service – Use this service to query for data about the structure of your installation. You can retrieve metadata for labels, menus, tables, data types, enums, services, and so on. The metadata service should be used when you want to return information about the structures in Microsoft Dynamics AX to a client application.</p></li>
<li><p>Query service – Use this service to issue a query for data without using an AIF document service or creating a custom service. The query service returns data in a dataset and implements a paging mechanism, so that you can manage queries that return large amounts of data. When you call the query service, you can specify that the query run as a static query, a user-defined query, or a dynamic query.</p></li>
<li><p>User session service – Use this service to retrieve information about the calling user, such as the user’s default language, default company, and default company time zone.</p></li>
</ul></td>
<td><p>The system services open up Microsoft Dynamics AX development to other platforms by letting you retrieve system information via services. System services make it easier to develop applications that work with Microsoft Dynamics AX.</p></td>
<td><p><a href="aif-system-services.md">AIF System Services</a></p></td>
</tr>
</tbody>
</table>


## Support for new document service operations GetKeys and GetChangedKeys

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>You can implement change tracking by retrieving entity keys for only those records that match certain criteria, and that have changed since a specified date and time.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>The following two new service operations are supported:</p>
<ul>
<li><p>GetKeys – This operation returns a list of entity keys for documents, based on a document filter.</p></li>
<li><p>GetChangedKeys – This operation returns a list of entity keys for documents, based on criteria in a document filter. This operation also limits the list to keys for records that have changed since a specified date and time.</p></li>
</ul></td>
<td><p>Change tracking is supported for data exchanges. Because a list of entity keys is retrieved for only those records that have changed since the last update, performance is improved when you update data external to Microsoft Dynamics AX.</p></td>
<td><p><a href="configuring-aif-for-change-tracking.md">Configuring AIF for change tracking</a></p></td>
</tr>
</tbody>
</table>


## Improvements in troubleshooting

In AX 2009, troubleshooting and logging of AIF were performed at the service operation level. In AX 2012, troubleshooting and logging are performed at the integration port level.

AX 2012 supports the correlation of exceptions to messages and ports. In other words, you can view information about the related port, message, and message set in the **Exceptions** form. For more information, see [Configure troubleshooting options for integration ports](configure-troubleshooting-options-for-integration-ports.md) and [Monitoring services and AIF](monitoring-services-and-aif.md).

## More information

For more detailed information about services, see the white papers [Services in Microsoft Dynamics AX 2012](http://go.microsoft.com/fwlink/?linkid=213141) and [Consuming Web Services](http://go.microsoft.com/fwlink/?linkid=213142), and the topic [Services and Application Integration Framework (AIF)](services-and-application-integration-framework-aif.md).

For more information about how to use the services programming model together with AX 2012, see [Selecting the Best Development Technology for Your Application Development Scenario (White paper)](selecting-the-best-development-technology-for-your-application-development-scenario-white-paper.md).

  


