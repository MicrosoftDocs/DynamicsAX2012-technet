---
title: Set up transportation management engines
TOCTitle: Set up transportation management engines
ms:assetid: 1c8a6fdb-12fd-4554-b4f9-90195be274f5
ms:mtpsurl: https://technet.microsoft.com/library/Dn553149(v=AX.60)
ms:contentKeyID: 62524893
author: tonyafehr
ms.date: 06/25/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up transportation management engines 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

To calculate rates, you must manually create one or more transportation management engines, or automatically initialize the base engine data. In Microsoft Dynamics AX 2012 R3, you can search for available shipment rates based on information such as travel distance or zones in a region. The search criteria are interpreted by transportation management engines that calculate the available rates.

This topic shows how to set up transportation management engines that you can use to calculate shipping carrier rates.

## Setting up transportation management engines

For the engines that are delivered with Microsoft Dynamics AX, the rate calculation is based on data that is controlled by metadata. Engines that are not delivered with Microsoft Dynamics AX can be applied without a metadata configuration. Some of the guidelines in the following sections include descriptions about how to configure metadata and define data. These descriptions do not apply to engines that retrieve data from sources outside Microsoft Dynamics AX. For more information, see “Do all engine configurations require metadata?” in [Transportation management engines](transportation-management-engines.md).

**File name extensions in assembly names**

The file name extension should always be included in the assembly name of an engine. For all of the transportation management engines listed in this topic, you must always include the file name extension, such as in Microsoft.Dynamics.Ax.Tms.dll.

## Set up a rate engine

Before you set up a rate engine to calculate rates, you must complete the following tasks:

  - Set up a rate base type to control the metadata that you use to search for rates. The structure of the rate base type is defined by the type of rate engine and by the type of rate base assigner that is associated with the engine. The rate base type of a rate engine must correspond to the rate base type of the shipping carrier’s rate master. For more information about how to set up a rate base type and how to associate it with a rate master, see [Set up rate masters](set-up-rate-masters.md).

  - Configure metadata for the engine. For more information about metadata and an example that shows how to configure metadata for an engine, see “How do I configure metadata for a transportation management engine?” in [Transportation management engines](transportation-management-engines.md).

To set up a rate engine, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Engines** \> **Rate engine**.

2.  Create a new rate engine.

3.  Enter an identifier (ID) and name for the rate engine.

4.  In the **Rate base type** field, select a rate base type.

5.  In the **Engine assembly** field, enter the assembly that defines the engine type, such as Microsoft.Dynamics.Ax.Tms.dll.

6.  In the **Engine type** field, enter the fully-qualified name of the .NET type that defines the engine. The name should contain a namespace without an assembly name, such as Microsoft.Dynamics.Ax.Tms.Bll.LtlRateEngine.

7.  Click **Parameters**, and create a new parameter. Enter a name and a parameter value. For example, enter Microsoft.Dynamics.Ax.Tms.dll|Microsoft.Dynamics.Ax.Tms.Bll.LtlRateBaseAssigner as the value for the engine parameter RateBaseAssigner.

## Set up a transit time engine

Set up a transit time engine to calculate the time that it takes to transport goods from point A to point B. The setup includes the following tasks:

  - Create a transit time engine.

  - Configure metadata. For more information about metadata, see “How is metadata used in transportation management engines?” in [Transportation management engines](transportation-management-engines.md).

  - Define data.

To create a transit time engine, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Engines** \> **Transit time engine**.

2.  Create a new transit time engine.

3.  Enter an ID and name for the transit time engine.

4.  In the **Engine assembly** field, enter the assembly that defines the engine type, such as Microsoft.Dynamics.Ax.Tms.dll.

5.  In the **Engine type** field, enter the fully-qualified name of the .NET type that defines the transportation management engine. The name should contain a namespace without an assembly name. For example, a code for the transportation management engine that corresponds to the type of calculation, such as Microsoft.Dynamics.Ax.Tms.P2PTransitTimeEngine.

6.  In the **Transit time engine** form, click **Parameters** to enter additional engine parameters

To configure metadata, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Engines** \> **Transit time engine**.

2.  Click **Transit time field**, and then click **New** to create the metadata that you will use to search for rates.
    
    Enter information in the following fields.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Transit time engine</strong></p></td>
    <td><p>Select the transit time engine that you created in the <strong>Transit time engine</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Sequence</strong></p></td>
    <td><p>The sequence of the lookup fields on the <strong>Rate base assignment</strong> FastTab in the <strong>Rate master</strong> form.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>The field’s caption in the user interface.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data type</strong></p></td>
    <td><p>The type of data that is stored, such as numeric, alphanumeric, or string.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Lookup type</strong></p></td>
    <td><p>The type of lookup that is used to assign a value, such as a postal code, to the data record in the user interface.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Mandatory</strong></p></td>
    <td><p>Select this check box to make the data field for the metadata record required. If the check box is not selected, the data field is optional.</p></td>
    </tr>
    </tbody>
    </table>


To define data, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Engines** \> **Transit time engine**.

2.  In the **Transit time engine** form, on the **Details** FastTab, click **New**.

## Set up a mileage engine

Set up a mileage engine to calculate the transport distance. Setting up a mileage engine includes the following tasks:

  - Create a mileage engine.

  - Configure metadata.

  - Define data.

To create a mileage engine, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Engines** \> **Mileage engine**.

2.  Create a new mileage engine.

3.  Enter an ID and name for the mileage engine.

4.  On the **Information** FastTab, in the **Engine assembly** field, enter the assembly that defines the engine type, such as Microsoft.Dynamics.Ax.Tms.dll.

5.  In the **Engine type** field, enter the fully-qualified name of the .NET type that defines the engine. The name should contain a namespace without an assembly name, such as Microsoft.Dynamics.Ax.Tms.P2PMileageEngine for a point-to-point mileage engine.

6.  Select the **Default** check box to use the selected engine as the default engine to calculate shipping rates based on mileage.

7.  Click **Parameters** to enter additional engine parameters.

To configure metadata, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Engines** \> **Mileage engine**.

2.  Select a mileage engine.

3.  Click **Define mileage engine**, and then click **New** to create the metadata that you will use to search for rates.
    
    Enter information in the following fields.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Sequence</strong></p></td>
    <td><p>The sequence of the lookup fields on the <strong>Rate base assignment</strong> FastTab in the <strong>Rate master</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>The field’s caption in the user interface.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Data type</strong></p></td>
    <td><p>The type of data that is stored, such as numeric, alphanumeric, or string.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Lookup type</strong></p></td>
    <td><p>The type of lookup that is used to assign a value, such as a postal code, to the data record in the user interface.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Mandatory</strong></p></td>
    <td><p>Select this check box to make the data field for the metadata record required. If the check box is not selected, the data field is optional.</p></td>
    </tr>
    </tbody>
    </table>


4.  Close the **Mileage engine field** form.

To define data, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Engines** \> **Mileage engine**.

2.  In the **Mileage engine** form, on the **Details** FastTab, click **New**.

## Set up a zone engine

Set up a zone engine to identify the zone for an address or to calculate the number of zones that must be crossed during the transport of goods from address A to address B. Setting up a zone engine includes the following tasks:

  - Create a zone engine.

  - Create a zone master.

  - Configure metadata for the zone master.

  - Define data for the zone master’s metadata.

To create a zone engine, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Engines** \> **Zone engine**.

2.  Create a new zone engine.

3.  Enter a unique ID and name for the zone engine.

4.  Create a name for the zone engine, such as PostalCodeZoneEngine.

5.  In the **Engine assembly** field, enter the assembly that defines the engine type, such as Microsoft.Dynamics.Ax.Tms.dll.

6.  In the **Engine type** field, enter the fully-qualified name of the .NET type that defines the engine. The name should contain a namespace without an assembly name, such as Microsoft.Dynamics.Ax.Tms.PostalCodeZoneEngine for a postal code zone engine.

7.  Click **Parameters** to enter additional engine parameters.

To create a zone master, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Zone master**.

2.  Click **New** to create a new zone master.

3.  Enter a unique ID and name for the zone master.

4.  In the **Zone engine** field, select the transportation management engine that you created in the previous procedure, such as PostalCodeZoneEngine. This is used to associate the zone master with zone engines.

5.  In the **Zone type** field, select **Rating** or **Routing**.

To configure metadata for the zone master, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Zone master**.

2.  Click **Zone master field**.

3.  In the **Zone master field** form, click **New** to create new metadata records.

4.  Configure the fields for the zone engine using the same guidelines that you use to create metadata for a mileage engine. For more information, see “Set up a mileage engine” earlier in this topic.

5.  Close the **Zone master field** form.

To create new data records for the zone master, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Engines** \> **Zone engine**.

2.  In the **Zone master** form, on the **Details** FastTab, click **New**.

## Set up a generic engine

A generic engine calculates distribution of costs for a load, also referred to as apportion transportation charges. By using a generic engine, you can also provide additional auxiliary functions, such as calculations of control numbers for bar codes.

To set up a generic engine, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Engines** \> **Generic engine**.

2.  Create a new generic engine.

3.  Enter an ID and name for the generic engine.

4.  Select the **Default** check box to use the selected generic engine of the type **Apportionment** as the default engine for the breakdown of final costs of transportation to specific orders and lines. This is based on dimensions such as volume and weight.

5.  In the **Engine assembly** field, enter the assembly that defines the engine type, such as Microsoft.Dynamics.Ax.Tms.dll.

6.  In the **Engine parameter** field, enter an engine parameter, such as Microsoft.Dynamics.Ax.Tms.Bll.GenericApportionmentEngine for an apportionment engine.

7.  In the **Engine type** field, select the type of engine, such as **Apportionment engine**.

8.  Click **Parameters** to enter additional engine parameters.

## Set up a freight bill type engine

You can use a freight bill type engine to standardize a freight invoice and freight bill lines, and to automatically match the freight bill.

To set up a freight bill type engine, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Freight reconciliation** \> **Freight bill type**.

2.  Click **New** to create a new freight reconciliation bill type.

3.  In the **Freight bill type** field, enter a name for the freight bill type.

4.  In the **Engine assembly** field, enter the assembly that defines the engine type, such as Microsoft.Dynamics.Ax.tms.dll.

5.  In the **Engine type** field, enter the fully-qualified name of the .NET type that defines the engine. The name should contain a namespace without an assembly name, such as Microsoft.Dynamics.Ax.Tms.Bll.GenericNormalizer.

6.  Click the **Details** FastTab, and then click **New** to create lines for the freight bill type.

7.  In the **Sequence** field, enter the sequence that determines the order in which the fields for matching are normalized for freight bill matching.

8.  Enter a description and name for the engine type. The name is the field’s caption in the user interface.

9.  In the **Match required** field, select **Yes** or **No**. This determines whether the dimension value fields of the freight bill and the freight invoice should affect reconciliation of these two documents.
    
    Matching the freight invoice and the freight bill can be completed if the values of the fields are the same on the freight invoice and the freight bill. The **Match required** check box can also be used to determine what happens if the field values are not specified.
    
      - **Yes** – If the matched fields have no values specified, then matching cannot be completed.
    
      - **No** – If the matched fields have no values specified, then matching can be completed.

## Initialize base engine data automatically

You can automatically initialize base engine data to create engine setup data for all the engines that were included with Microsoft Dynamics AX 2012 R3.

If you initialize the base engine data in this manner, data is initialized per company and existing engine data that is set up in individual companies may be disregarded.

To initialize base engine data automatically, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Transportation management parameters**.

2.  Under the **General** link, click the **Engines** FastTab.

3.  Click the **Initialize base engine data** button.

## Related tasks

[Set up shipping carriers and carrier groups](set-up-shipping-carriers-and-carrier-groups.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


