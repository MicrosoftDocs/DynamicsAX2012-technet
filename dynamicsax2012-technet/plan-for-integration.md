---
title: Plan for integration
TOCTitle: Plan for integration
ms:assetid: bf482893-ceeb-4430-b8ca-769645153ae3
ms:mtpsurl: https://technet.microsoft.com/library/Dd362063(v=AX.60)
ms:contentKeyID: 35132845
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Plan for integration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic provides guidelines that you may have to consider when you plan your data integration. Every deployment of Microsoft Dynamics AX represents a unique situation. Your specific requirements may vary.</P>



Planning is an important part of any data integration effort. When you integrate Microsoft Dynamics AX with other systems, one of the first steps is the planning phase. In this phase, the implementation team must define high-level requirements and make decisions about the design of the integration. After these requirements are defined, the partner, IT staff, and development staff can work together to define the best way to implement the exchange in Application Integration Framework (AIF).

The decisions that must be made about the design of the integration fit into two primary categories: decisions about the data and decisions about the environment.

  - **Data** – At the core of data integration is the data itself. While you plan your data integration, many decisions must be made about the data that is being exchanged and the associated business rules. This phase often involves the expertise and knowledge of business users, because these users understand the meaning of the data and can define the requirements for integration.

  - **Environment** – Configuration requirements define the environment that is used for the data exchange. Factors that affect these requirements include the network configuration, the hardware and software configuration of the external system, and the level of trust between Microsoft Dynamics AX and the external system.

Before document exchanges are configured, we recommend that the implementation team consider the questions that are described in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Question</p></th>
<th><p>Effect on the design</p></th>
<th><p>Related topics</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Which business entities are involved, if any are involved?</p></td>
<td><p>This information helps you determine whether you can take advantage of an existing document service. If you cannot, you might have to create a new document service or a new custom service, or you might have to use one of the system services.</p></td>
<td><p><a href="standard-document-services.md">Standard Document Services</a></p>
<p><a href="using-custom-services.md">Using Custom Services</a></p>
<p><a href="aif-system-services.md">AIF System Services</a></p></td>
</tr>
<tr class="even">
<td><p>Is the data sent from Microsoft Dynamics AX to an external system, or is the data received by Microsoft Dynamics AX from an external system?</p></td>
<td><p>This information helps you determine whether you must use an inbound or outbound integration port.</p></td>
<td><p><a href="application-integration.md">Application integration</a></p>
<p><a href="integration-ports.md">Integration ports</a></p></td>
</tr>
<tr class="odd">
<td><p>Is the integration based on the &quot;pull&quot; model or the &quot;push&quot; model? In the &quot;pull&quot; model, the external system requests data from Microsoft Dynamics AX. In the &quot;push&quot; model, an event in the application causes data to be sent to the external system.</p></td>
<td><p>This information helps you determine how to configure a document exchange.</p></td>
<td><p><a href="application-integration.md">Application integration</a></p></td>
</tr>
<tr class="even">
<td><p>What business rules are associated with the data? For example, if data is created or updated, which data elements are required? If data is deleted, what are the conditions under which a record can be deleted?</p></td>
<td><p>This information helps you determine whether any customizations must be made to existing AIF documents.</p></td>
<td><p><a href="customize-service-contracts.md">Customize service contracts</a></p></td>
</tr>
<tr class="odd">
<td><p>Does the data have to be transformed? Do the transformations have to be performed before data is sent or when data is received? What is the extent of the data transformations? Are the transformations performed by Microsoft Dynamics AX or an external system, such as BizTalk?</p></td>
<td><p>This information helps you determine whether AIF value mapping, .NET transformations, or XSLT transformations must be used.</p></td>
<td><p><a href="messages-and-transforms-in-aif.md">Messages and transforms in AIF</a></p>
<p><a href="exchanging-documents-between-biztalk-server-and-aif.md">Exchanging documents between BizTalk Server and AIF</a></p></td>
</tr>
<tr class="even">
<td><p>Does the external system have any restrictions about how data is exchanged?</p></td>
<td><p>This information helps you determine the type of transport adapter that is required for the exchange.</p></td>
<td><p><a href="adapters.md">Adapters</a></p>
<p><a href="application-integration.md">Application integration</a></p></td>
</tr>
<tr class="odd">
<td><p>Is the external system an in-house system or an external trading partner?</p></td>
<td><p>This information helps you determine how users and security must be configured.</p></td>
<td><p><a href="services-and-aif-security-and-protection.md">Services and AIF security and protection</a></p></td>
</tr>
<tr class="even">
<td><p>What is the availability of the systems that are being integrated? What are the requirements for real-time data exchanges?</p></td>
<td><p>This information helps you determine whether you must use synchronous or asynchronous adapters.</p></td>
<td><p><a href="adapters.md">Adapters</a></p>
<p></p></td>
</tr>
<tr class="odd">
<td><p>What is the volume of transactions?</p></td>
<td><p>This information helps you determine which adapters you must use. The information also helps you determine the scale of the deployment, such as the number of computers that run Application Object Server (AOS).</p></td>
<td><p><a href="configuring-network-load-balancing-for-services.md">Configuring network load balancing for services</a></p>
<p><a href="application-integration-framework-topology.md">Application Integration Framework topology</a></p></td>
</tr>
</tbody>
</table>

  


