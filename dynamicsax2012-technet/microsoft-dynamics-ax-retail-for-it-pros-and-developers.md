---
title: Microsoft Dynamics AX Retail for IT pros and developers
TOCTitle: Retail
ms:assetid: fb782d05-4648-4155-8185-4c587dff6352
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710398(v=AX.60)
ms:contentKeyID: 49384290
ms.date: 10/26/2016
mtps_version: v=AX.60
---

# Microsoft Dynamics AX Retail for IT pros and developers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Retail provides mid-market and large retailers a complete head-office and point of sale (POS) solution with support for online and brick-and-mortar stores. It can help retailers increase financial returns, improve service, manage growth, reach customers, and streamline efficiencies.

Retail consists of several components that are typically distributed across multiple computers and locations. For illustrations of how these components can be deployed, see [Deployment topologies for Retail](deployment-topologies-for-retail.md).

The following table briefly describes each component.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Function</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Retail headquarters</p></td>
<td><p>Retail headquarters for Microsoft Dynamics AX can be used to manage a chain of stores as one enterprise. It controls daily operations and tracks sales information for every store in the chain. Retail Scheduler coordinates communication between Microsoft Dynamics AX and the stores.</p>
<p>Retail headquarters can be used with any POS or online store system that can receive and transmit the necessary data.</p>
<div class="alert">

> [!IMPORTANT]
> <P>Building a custom POS or online store solution for Microsoft Dynamics AX is a complex task that requires extensive planning, development, and testing.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Commerce Data Exchange</p></td>
<td><p>Commerce Data Exchangeincludes several components that are used to exchange data between Microsoft Dynamics AX and the physical or online store.</p>
<p>For more information, see <a href="commerce-data-exchange.md">Commerce Data Exchange</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Channel database</p></td>
<td><p>A channel database holds Retail data for one or more retail channels, such as online stores or brick-and-mortar stores.</p></td>
</tr>
<tr class="even">
<td><p>Microsoft Dynamics AX for Retail POS</p></td>
<td><p>Retail POS provides a dynamic interface that can be customized to suit business and store procedures. In addition, Retail POS can work offline. This enables stores to continue operating even during network interruptions. All data is automatically synchronized when the connection is restored.</p></td>
</tr>
<tr class="odd">
<td><p>Retail Modern POS</p></td>
<td><p>Microsoft Dynamics AX 2012 for Retail Modern Point-of-Sale (POS) enables clients like PCs, tablets, and phones to process sales transactions, customer orders, daily operations, and perform inventory management.</p></td>
</tr>
<tr class="even">
<td><p>Commerce runtime</p></td>
<td><p>Commerce runtime serves as the intermediary between Microsoft Dynamics AX and an online store. Commerce runtime contains a data access layer, a services layer, a workflow layer, and an API layer.</p></td>
</tr>
<tr class="odd">
<td><p>Online store</p></td>
<td><p>The online store provides an online sales channel that is fully integrated with AX 2012. E-commerce investments include two starter online stores that are built on Microsoft SharePoint Server 2013 and can be customized for specific business needs to reach online customers. Developer tools and administrative and runtime components are provided to help integrate the online channel with AX 2012.</p></td>
</tr>
<tr class="even">
<td><p>Retail Server</p></td>
<td><p>Retail Server provides services and business logic for Modern Point of Sale (POS) clients.</p></td>
</tr>
<tr class="odd">
<td><p>Hardware Station</p></td>
<td><p>Microsoft Dynamics AX Retail Hardware Station provides services for Microsoft Dynamics AX Retail Retail Modern POS clients and peripherals such as printers, cash drawers, or payment devices that enable these devices to communicate with Microsoft Dynamics AX Retail Server.</p></td>
</tr>
<tr class="even">
<td><p>Retail Channel Configuration Utility (Retail Store Database Utility)</p></td>
<td><p>This utility is used at the point of sale to create and configure the offline database, create and identify the store database, and create the configuration file that is used to identify registers.</p></td>
</tr>
<tr class="odd">
<td><p>Retail SDK</p></td>
<td><p>The Retail SDK contains sample source code and templates that can be used to customize the Retail system.</p></td>
</tr>
</tbody>
</table>


This sections includes the following topics.

[Deployment topologies for Retail](deployment-topologies-for-retail.md)

[Online Store](online-store.md)

[Point of Sale](point-of-sale.md)

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

[Commerce Data Exchange](commerce-data-exchange.md)

[Commerce Runtime](commerce-runtime.md)

[Microsoft Dynamics AX Retail Hardware Station](microsoft-dynamics-ax-retail-hardware-station.md)

[Microsoft Dynamics AX Retail Server](microsoft-dynamics-ax-retail-server.md)

[Retail Salt Utility](retail-salt-utility.md)

[Retail SDK](retail-sdk.md)

[Mass deploy retail components](mass-deploy-retail-components.md)

  


