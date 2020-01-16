---
title: Deployment topologies for Retail
TOCTitle: Deployment topologies for Retail
ms:assetid: eda17d27-a0e0-4117-92a9-6a7e52f1b917
ms:mtpsurl: https://technet.microsoft.com/library/JJ991928(v=AX.60)
ms:contentKeyID: 51595731
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Deployment topologies for Retail 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R3 Cumulative Update 8. For more information, see the section later in this topic.</P>



Before you install Microsoft Dynamics AX 2012 for Retail, you must decide on the system topology. This topic describes common topologies for a Retail system.

The topology at the head office is a standard Microsoft Dynamics AX deployment, with additional computers for retail functions. Depending on the requirements of your organization, you can use a computer for more than one purpose. We recommend that you load balance across multiple computers whenever load balancing is possible.


> [!NOTE]
> <P>For development and testing, you can install the complete Retail system on a single computer. However, a deployment of this kind is not a supported production scenario.</P>



This topic contains the following sections:

  - Deployment topologies for Retail in AX 2012 R3

  - Deployment topologies for Retail in AX 2012 R2 and AX 2012 Feature Pack

## Deployment topologies for Retail in AX 2012 R3

The following table lists the types of computers that are used in a typical Retail deployment with AX 2012 R3.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Deployment location</p></th>
<th><p>Types of computers</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Head office</p></td>
<td><ul>
<li><p>AOS computer with Retail headquarters component installed</p></li>
<li><p>Database server</p>
<p>You must modify the Microsoft Dynamics AX database server only if the settings for Microsoft SQL Server do not comply with the Payment Card Industry (PCI) Data Security Standard. For more information about PCI-compliant settings, see the <a href="https://go.microsoft.com/fwlink/?linkid=237283">Implementation Guide for PCI Compliance</a>.</p></li>
<li><p>Communications server that hosts Commerce Data Exchange: Real-time Service and Async Server (or Synch Service for versions prior to AX 2012 R3).</p>
<p>If you prefer, you can have two communications servers, one for each of these applications.</p></li>
<li><p>Microsoft Dynamics AX client computers with Retail headquarters component installed</p></li>
<li><p>Retail Server, if you are using Retail Modern POS</p></li>
<li><p>Web servers that host the online channel</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Brick-and-mortar stores</p></td>
<td><ul>
<li><p>Computer that hosts the channel database and Async Client (or Synch Service for versions prior to AX 2012 R3)</p></li>
<li><p>Retail Server (required for Retail Modern POS)</p></li>
<li><p>Point of sale (POS) registers</p></li>
<li><p>Point of sale (POS) registers</p></li>
</ul></td>
</tr>
</tbody>
</table>


### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")Topology diagrams for POS in AX 2012 R3

The following figures illustrate typical deployment topologies for a POS system in AX 2012 R3.

#### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")Each component of a POS system is hosted on a dedicated computer

In Figure 1, each component is hosted on a dedicated physical computer or virtual machine. Components that support multiple instances, such as AOS, Async Server and Real-time Service could be installed on additional computers for load balancing. This deployment topology is appropriate for a large retailer.

![Store topology with dedicated servers](images/JJ991928.Retail_DedicatedServersR3(en-us,AX.60).gif "Store topology with dedicated servers")

Figure 1 Hosting of POS components on dedicated computers

#### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")POS components are hosted on shared servers

In Figure 2, on the head office side, the Async Server instance, Real-time Service, and Enterprise Portal for Microsoft Dynamics AX have been combined on a single computer. A midsize retailer might want to consolidate these services on one computer or run them on virtual machines on a single physical server. On the store side, Async Client is installed on the same computer as the channel database server.

![Retail topology with shared servers](images/JJ991928.Retail_SharedServersR3(en-us,AX.60).gif "Retail topology with shared servers")

Figure 2 Shared hosting of POS components

#### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")Store-side database topologies

For Retail POS registers, the following store-side database topologies are supported:

  - POS registers have offline databases that are synchronized with the channel database within the store when the POS registers are connected.

  - POS registers do not have databases and must always be connected to the channel database within the store.

For Retail Modern POS, the following store-side database topologies are supported:

  - Retail Modern POS registers have offline databases that are synchronized with the channel database.

  - Retail Modern POS registers do not have databases and must always be connected to a Retail Server.

  - Retail Modern POS registers connect directly to a channel database without connecting to a Retail Server.

Figure 3 illustrates the supported topologies for POS registers. In the **POS portable** topology, the POS device uses the channel database by default, and synchronizes its local database and the channel database. If the channel database becomes inaccessible, the POS device uses its offline database until the connection to the channel database is re-established. In the **POS always online** topology, the POS device must always be online to connect with the channel database.

![Store database topology](images/JJ991928.Retail_StoreDBTopologyR3(en-us,AX.60).gif "Store database topology")

Figure 3 Supported database topologies for POS devices


> [!NOTE]
> <P>Async Server, Async Client, and Real-time Service have been omitted from Figure 3, because they are not affected.</P>



Figure 4 illustrates the supported topologies for Retail Modern POS registers.

![Retail Modern POS with direct database connection](images/JJ991928.RetailModernDirect(en-us,AX.60).png "Retail Modern POS with direct database connection")

![Retail Modern POS with Retail Server](images/JJ991928.RetailModernPOSRetailServer(en-us,AX.60).png "Retail Modern POS with Retail Server")

Figure 4 Supported topologies for Retail Modern POS devices

### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")Topology diagrams for online stores in AX 2012 R3

The following figures illustrate typical deployment topologies for an online store system in AX 2012 R3.

#### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")Each component of an online store is hosted on a dedicated computer

In Figure 5, each component is hosted on a dedicated physical computer or virtual machine. Components that support multiple instances, such as AOS and online store sites, could be installed on additional computers for load balancing.

![Online store configuration with dedicated servers](images/JJ991928.Retail_DedicatedServers_OnlineStoreR3(en-us,AX.60).gif "Online store configuration with dedicated servers")

Figure 5 Hosting of online store components on dedicated computers

#### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")Online store components are hosted on shared servers

In Figure 6, Async Client, Real-time Service, and Enterprise Portal have been combined on a single computer. A midsize retailer might want to consolidate these services on one computer or run them on virtual machines on a single physical server.

![Online store topology with shared servers](images/JJ991928.Retail_SharedServers_OnlineStoreR3(en-us,AX.60).gif "Online store topology with shared servers")

Figure 6 Shared hosting of online store components

## Deployment topologies for Retail in AX 2012 R2 and AX 2012 Feature Pack

The following table lists the types of computers that are used in a typical Retail deployment with AX 2012 R2 or AX 2012 Feature Pack.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Deployment location</p></th>
<th><p>Types of computers</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Head office</p></td>
<td><ul>
<li><p>AOS computer</p></li>
<li><p>Database server</p>
<p>You must modify the Microsoft Dynamics AX database server only if the settings for Microsoft SQL Server do not comply with the Payment Card Industry (PCI) Data Security Standard. For more information about PCI-compliant settings, see the <a href="https://go.microsoft.com/fwlink/?linkid=237283">Implementation Guide for PCI Compliance</a>.</p></li>
<li><p>Communications server that hosts Commerce Data Exchange: Real-time Service and Commerce Data Exchange: Synch Service.</p>
<p>If you prefer, you can have two communications servers, one for each of these applications.</p></li>
<li><p>Microsoft Dynamics AX client computers</p></li>
<li><p>Web servers that host the online store</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Brick-and-mortar stores</p></td>
<td><ul>
<li><p>Database server</p></li>
<li><p>Communications server that hosts Synch Service</p></li>
<li><p>Point of sale (POS) registers</p></li>
</ul></td>
</tr>
</tbody>
</table>


Typically, head office and store computers where Synch Service is installed also have SQL Server Express Edition installed. However, this instance of SQL Server is used only for the Synch Service message database.

### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")Topology diagrams for POS in AX 2012 R2 and AX 2012 Feature Pack

The following figures illustrate typical deployment topologies for a POS system in AX 2012 R2 and AX 2012 Feature Pack.

#### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")Each component of a POS system is hosted on a dedicated computer

In Figure 1, each component is hosted on a dedicated physical computer or virtual machine. Components that support multiple instances, such as AOS and Synch Service, could be installed on additional computers for load balancing. This deployment topology is appropriate for a large retailer.

![Retail components on dedicated computers](images/JJ991928.Retail_BasicTopology(en-us,AX.60).png "Retail components on dedicated computers")

Figure 1 Hosting of Retail POS components on dedicated computers

#### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")POS components are hosted on shared servers

In Figure 2, on the head office side, the Synch Service instance, Real-time Service, and Enterprise Portal for Microsoft Dynamics AX have been combined on a single computer. A midsize retailer might want to consolidate these services on one computer or run them on virtual machines on a single physical server. On the store side, Synch Service is installed on the same computer as the store database server.

![Retail components on shared computers](images/JJ991928.Retail_SharedServersR3(en-us,AX.60).gif "Retail components on shared computers")

Figure 2 Shared hosting of Retail POS components

#### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")Store-side database topologies

Retail supports the following store-side database topologies:

  - POS registers have offline databases that are synchronized with the store database when the POS registers are connected.

  - POS registers do not have databases and must always be connected to the store database.

Figure 3 illustrates the two supported topologies. In the **POS portable** topology, the POS register uses the store database by default, and synchronizes its local database and the store database. If the store database becomes inaccessible, the POS register uses its offline database until the connection to the store database is re-established. In the **POS always online** topology, the POS register must always be online to connect with the store database.

![Retail database topologies](images/JJ991928.Retail_DatabaseTopologies(en-us,AX.60).png "Retail database topologies")

Figure 3 Supported database topologies for Retail POS registers


> [!NOTE]
> <P>Synch Service and Real-time Service have been omitted from Figure 3, because they are not affected.</P>



### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")Topology diagrams for online stores in AX 2012 R2 and AX 2012 Feature Pack

The following figures illustrate typical deployment topologies for an online store system in AX 2012 R2 and AX 2012 Feature Pack.

#### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")Each component of an online store is hosted on a dedicated computer

In Figure 4, each component is hosted on a dedicated physical computer or virtual machine. Components that support multiple instances, such as AOS, Synch Service, and online store sites, could be installed on additional computers for load balancing.

![Retail topology that includes the online store](images/JJ991928.Retail_DedicatedServers_OnlineStore(en-us,AX.60).png "Retail topology that includes the online store")

Figure 4 Hosting of Retail online store components on dedicated computers

#### ![JJ991928.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991928.collapse_all(en-us,AX.60).gif")Online store components are hosted on shared servers

In Figure 5, Synch Service, Real-time Service, and Enterprise Portal have been combined on a single computer. A midsize retailer might want to consolidate these services on one computer or run them on virtual machines on a single physical server.

![Retail online store topology with shared servers](images/JJ991928.Retail_SharedServers_OnlineStore(en-us,AX.60).png "Retail online store topology with shared servers")

Figure 5 Shared hosting of online store components

## See also

[Point of Sale](point-of-sale.md)

[Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)](create-a-store-database-or-an-offline-database-ax-2012-r2-and-ax-2012-feature-pack.md)

  


