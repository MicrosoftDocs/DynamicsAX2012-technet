---
title: Transportation management engines
TOCTitle: Transportation management engines
ms:assetid: c1e80525-3ccb-440f-824f-32108f74c53c
ms:mtpsurl: https://technet.microsoft.com/library/Dn770236(v=AX.60)
ms:contentKeyID: 62524897
author: Khairunj
ms.date: 06/25/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Transportation management engines 


Transportation management engines define the logic that is used to generate and process transportation rates in **Transportation management**. A transportation management engine calculates tasks, such as the carrier’s transportation rate. The engine system lets you change calculation strategies at runtime, based on data in Microsoft Dynamics AX. A transportation management engine resembles a plug-in that is related to a particular carrier contract.

## What engines are available?

The following table shows the transportation management engines that are available in AX 2012 R3.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transportation management engine</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Rate engine</strong></p></td>
<td><p>Calculates rates.</p></td>
</tr>
<tr class="even">
<td><p><strong>Generic engine</strong></p></td>
<td><p>Simple auxiliary engines that are used by other engines that do not require data from Microsoft Dynamics AX 2012 R3, for example, an apportionment engine. Apportionment engines are used to reduce the final costs of transportation to specific orders and lines, based on dimensions, such as volume and weight.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Mileage engine</strong></p></td>
<td><p>Calculates the transportation distance.</p></td>
</tr>
<tr class="even">
<td><p><strong>Transit time engine</strong></p></td>
<td><p>Calculates the time that is required to travel from the start to the end destination.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Zone engine</strong></p></td>
<td><p>Calculates the zone based on the current address and calculates the number of zones that must be crossed in order to travel from address A to address B.</p></td>
</tr>
<tr class="even">
<td><p><strong>Freight bill type</strong></p></td>
<td><p>Standardizes the freight invoice and the freight bill lines and is used for automatic freight bill matching.</p></td>
</tr>
</tbody>
</table>


## What engines must be configured to rate a shipment?

To rate a shipment using a specific carrier, you must configure multiple transportation management engines. The **Rate engine** is required, but other transportation management engines may be required to support the **Rate engine**. For example, the **Rate engine** can be used to retrieve data from the **Mileage engine** to calculate the rate based on mileage between the source and the destination.

## What’s required to initialize a transportation management engine?

A transportation management engine requires that you set up initialization data in order to function in a specific way. The setup can include the following types of data:

  - References to other transportation management engines. For details, see the configuration example in this section.

  - References to .NET types that are used by the transportation management engine.

  - Simple configuration data.

In most cases, you can click the **Parameters** button in the transportation management engine’s setup forms to configure the initialization data. For more information, see the guidelines for the individual transportation management engines in [Set up transportation management engines](set-up-transportation-management-engines.md).

**Example of the configuration of a rate engine that references a mileage engine**

The following example shows the setup that is required for a rate engine that is based on the .NET engine type Microsoft.Dynamics.Ax.Tms.Bll.MileageRateEngine and references a mileage engine.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>RateBaseAssigner</p></td>
<td><p>The .NET type that interprets the rate base assignment data for a particular schema. The syntax of the parameter value consists of two segments delimited by a vertical bar (|). The first segment contains the assembly name that defines the assigner type. The second segment defines the fully-qualified name of the assigner type. This includes the namespace of the type.</p></td>
</tr>
<tr class="even">
<td><p>MileageEngineCode</p></td>
<td><p>Mileage engine code that identifies the mileage engine record in the Microsoft Dynamics AX database.</p></td>
</tr>
<tr class="odd">
<td><p>ApportionmentEngine</p></td>
<td><p>Generic engine code that identifies the apportionment engine in the Microsoft Dynamics AX database.</p></td>
</tr>
</tbody>
</table>

  

For more information about how to set up a rate engine, see “Set up a rate engine” in [Set up transportation management engines](set-up-transportation-management-engines.md).

## How is metadata used in transportation management engines?

Transportation management engines that rely on data that is defined in AX 2012 R3 may use different data schemas. The transportation management system enables different transportation management engines to use the same generic physical database tables. To make sure that run-time interpretation of engine data is correct, you can define metadata for the database tables. This reduces the cost of building new transportation management engines because additional table and form structures are not required in AX 2012 R3.

## What can be used as search data in rate calculations?

The data that you use when you calculate rates in Microsoft Dynamics AX is controlled by the metadata configuration. For example, if you want to search for rates based on postal codes you must set up metadata based on the lookup type of a postal code.

## Do all engine configurations require metadata?

No, transportation management engines that are used to retrieve the data that is required for rate calculation from external systems don’t need metadata. The rate data for these engines can be retrieved from external transportation carrier systems, usually through a web service. For example, in AX 2012 R3 you can use a mileage engine that retrieves data directly from Bing maps so that you don’t need a metadata for this engine.


> [!NOTE]
> <P>The transportation management engines that are delivered with Microsoft Dynamics AX 2012 R3 rely on data that is retrieved from the application. Engines that connect to external systems are not included with AX 2012 R3. However, the engine-based extensibility model lets you build extensions using Microsoft Dynamics AX Visual Studio Tools.</P>



## How do I configure metadata for a transportation management engine?

Metadata for transportation management engines is configured differently for the different types of engines.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transportation management engine</p></th>
<th><p>Metadata configuration</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Rate engine</strong></p></td>
<td><p>Requires a <strong>Rate base type</strong>. The rate base type contains metadata for the rate base data and the rate base assignment data. The structure of rate base metadata is determined by the type of rate engine. The structure of the rate base assignment metadata is determined by the type of rate base assigner that is associated with that rate engine. You set up the rate base type of a rate engine on the <strong>Rate engine</strong> form and on the <strong>Rate master</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Zone engine</strong></p></td>
<td><p>Requires metadata to be set up directly on the zone master.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Transit time engine</strong> and <strong>Mileage engine</strong></p></td>
<td><p>Retrieves the metadata directly from the mileage engine’s configuration setup form.</p></td>
</tr>
</tbody>
</table>

  

For more information, see the setup guidelines for the transportation management engines in [Set up transportation management engines](set-up-transportation-management-engines.md).

**Example of metadata for a rate engine**

The transportation management engine requires identification of the origin address, the destination state and country/region, and the start and end point of the shipment. By using these requirements, the metadata would look like the data in the following table. The table also includes information about what type of input data is required.

  - Define this information under **Transportation management** \> **Setup** in the **Rate base type** form.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Sequence</strong></p></th>
<th><p><strong>Name</strong></p></th>
<th><p><strong>Field type</strong></p></th>
<th><p><strong>Data type</strong></p></th>
<th><p><strong>Lookup type</strong></p></th>
<th><p><strong>Mandatory</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>Origin postal code</p></td>
<td><p>Assignment</p></td>
<td><p>String</p></td>
<td><p><strong>Postal Code</strong></p></td>
<td><p>Selected</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>Destination state</p></td>
<td><p>Assignment</p></td>
<td><p>String</p></td>
<td><p><strong>State</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>Destination start postal code</p></td>
<td><p>Assignment</p></td>
<td><p>String</p></td>
<td><p><strong>Postal Code</strong></p></td>
<td><p>Selected</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p>Destination end postal code</p></td>
<td><p>Assignment</p></td>
<td><p>String</p></td>
<td><p><strong>Postal Code</strong></p></td>
<td><p>Selected</p></td>
</tr>
<tr class="odd">
<td><p>5</p></td>
<td><p>Destination country</p></td>
<td><p>Assignment</p></td>
<td><p>String</p></td>
<td><p><strong>Country/region</strong></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[Set up transportation management engines](set-up-transportation-management-engines.md)

  


