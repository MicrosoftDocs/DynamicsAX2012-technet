---
title: Architecture of Microsoft Dynamics AX Retail Server
TOCTitle: Retail Server architecture
ms:assetid: a3b1e382-24ec-4137-bc0f-08573bee0089
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741451(v=AX.60)
ms:contentKeyID: 62219727
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Architecture of Microsoft Dynamics AX Retail Server 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes the architecture of Retail Server. Retail Server provides services and business logic for Modern Point of Sale (POS) clients.

Retail Server is installed by using Microsoft Dynamics AX Setup.exe or Windows PowerShell. You can install it on a server in a store or in a datacenter. The Microsoft Dynamics AX Commerce runtime is wrapped in a Retail Server layer. Retail Server uses a web API with OData to support thin clients within the store like tablets and phones. Commerce runtime communicates through Commerce Data Exchange services to Microsoft Dynamics AX for Retail Headquarters.

Figure 1: Architecture of Microsoft Dynamics AX Retail Server

![The Dynamics AX Retail Server architecture](images/Dn741451.RetailServerArchitecture(en-us,AX.60).gif "The Dynamics AX Retail Server architecture")

Retail Server utilizes the following concepts.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Concept</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Entity type</p></td>
<td><p>An entity type is an entity that has a lifecycle you want to monitor. Each entity type has a key. An example of an entity type is Customer.</p></td>
</tr>
<tr class="even">
<td><p>Complex type</p></td>
<td><p>A complex type is an OData concept that is designed to avoid duplication by grouping certain related properties. These related properties can be reused in multiple entities. For example, Customer is an entity type that has a customer address, which is a wrapper that contains an address line, city, state, and zip code. Customer address is a complex type that can be reused by other entity types like Order, because the Order entity type would need the same address information that is associated with the Customer entity.</p></td>
</tr>
<tr class="odd">
<td><p>Controller</p></td>
<td><p>A controller is a mapping for an entity type that controls CRUD behaviors and actions for the entity type. Microsoft Dynamics AX provides a controller for each commerce entity. You can customize the following controllers:</p>
<p>Carts</p>
<p>Catalogs</p>
<p>Categories</p>
<p>Commerce</p>
<p>Commerce Lists</p>
<p>Composite Key Entity</p>
<p>Controller Assembly Resolver</p>
<p>Customers</p>
<p>Employees</p>
<p>Non-Bindable Action</p>
<p>Org Units</p>
<p>Picking Lists</p>
<p>Products</p>
<p>Purchase Orders</p>
<p>Sales Orders</p>
<p>Shifts</p>
<p>Stock Counts Journals</p>
<p>Transfer Orders</p></td>
</tr>
<tr class="even">
<td><p>Metadata</p></td>
<td><p>Metadata defines the contract between the client and the server.</p></td>
</tr>
</tbody>
</table>


You can create your own entity type or complex type, extend an existing controller, add a new controller, and customize the metadata. If you customize commerce runtime, you must also customize various components in Retail Server to expose those changes to your Modern POS clients.

## See also

[Microsoft Dynamics AX Retail Server](microsoft-dynamics-ax-retail-server.md)

[Install Retail Server](install-retail-server.md)

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

[Retail Modern POS architecture](retail-modern-pos-architecture.md)

[Create a new Retail Server Controller](create-a-new-retail-server-controller.md)

[Extend the metadata](extend-the-metadata.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

