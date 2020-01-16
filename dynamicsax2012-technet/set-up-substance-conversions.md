---
title: Set up substance conversions
TOCTitle: Set up substance conversions
ms:assetid: aee08eb6-ce07-4cc4-97d1-e719c2fe30e1
ms:mtpsurl: https://technet.microsoft.com/library/Hh242709(v=AX.60)
ms:contentKeyID: 36058946
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up substance conversions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Conversions are used to model the relationships between the inputs and outputs of a process. Each incoming substance can be converted to multiple outgoing substance flows. For example, if a process consumes gasoline by burning it, you would create a conversion that describes how much carbon dioxide and nitrates are emitted when the gasoline is burned.

The following example shows conversions that have been created for the organization.

Contoso owns a fleet of vehicles that are used to transport material and personnel between multiple facilities. Because Contoso uses a service that provides fuel cards, Contoso can access monthly reports to see exactly how much fuel they have purchased and used.

To set up their conversions, Contoso will create three processes. One process represents the vehicles; one process represents the vendors that the fuel is purchased from; and the last process represents the environment. The following table summarizes the properties for the processes.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Process</p></th>
<th><p>Description</p></th>
<th><p>Scope</p></th>
<th><p>Sphere</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Vehicles</p></td>
<td><p>Owned and leased vehicles</p></td>
<td><p>Primary</p></td>
<td><p>Technosphere</p></td>
</tr>
<tr class="even">
<td><p>Fuel vendors</p></td>
<td><p>Vendors that provide fuel</p></td>
<td><p>Tertiary</p></td>
<td><p>Technosphere</p></td>
</tr>
<tr class="odd">
<td><p>Ecosphere</p></td>
<td><p>The general environment, generally air, water, or ground</p></td>
<td><p>None</p></td>
<td><p>Ecosphere</p></td>
</tr>
</tbody>
</table>


Based on these processes, Contoso can create one conversion to model the burning of gasoline by the fleet of vehicles. The conversion will be triggered by flows of gasoline into the *Vehicles* process.

For more information about processes, process scopes, and process spheres, see [Set up environmental processes](set-up-environmental-processes.md).

Use the following procedures to set up a substance conversion. The first procedure explains how to create a substance conversion. The second procedure explains how to define the conversion if it is triggered by substance flow. The last procedure explains how to define the outputs of the conversion.


> [!IMPORTANT]
> <P>If you create multiple substance conversions, it is possible to create a circular reference where an incoming substance is converted to another substance and eventually returns as in incoming substance. To prevent this situation, click <STRONG>Validate</STRONG> after you set up a conversion.</P>



## Create a substance conversion

1.  Click **Compliance and internal controls** \> **Common** \> **Environmental sustainability** \> **Environmental processes** \> **Environmental processes**. In the **Environmental processes** form, select a process, and then click **Environmental conversion**.

2.  Click **New**, and enter a description. If the conversion identifier is not automatically generated, enter a conversion identifier.

3.  Select whether the substance conversion is for an incoming or outgoing substance, and then select the scope of the conversion.
    
    If you select **None**, the conversion creates flows that have the same scope as the triggering flow. For example, if the substance conversion is for an outgoing substance, and you select **None**, the scope of the output flows will be the same as the scope of the flow that triggered the conversion.

4.  Enter a start date and end date for the conversion. These dates should not overlap with another conversion of the same substance.

5.  Select the substance, its base quantity, and the unit of measure for the substance.
    
    The quantity is used as a multiplier for resulting flows. For example, if you enter 100 in the **Quantity** field, you are specifying that 100 units of the incoming substance are converted to a designated quantity of the outgoing substance.

6.  Click **Validate** to verify that you have not created a circular reference.

## Define a triggered conversion

Some substance conversions do not occur unless they are triggered by another process. For example, a conversion for gasoline is not started until the gasoline starts to flow.

1.  Click **Compliance and internal controls** \> **Common** \> **Environmental sustainability** \> **Environmental processes** \> **Environmental processes**. In the **Environmental processes** form, select a process, and then click **Environmental conversion**.

2.  On the **Related processes** tab, click **New**, or select an existing process.
    
    This process defines the conversion as it is triggered by flows that are going into the related process. For example, a conversion is triggered when gasoline is converted in to carbon dioxide.

## Define conversion output

A conversion output is the result of the substance conversion. Any outputs entered for a substance conversion should be based on real-world data. If possible, use existing modeling efforts distributed by a trusted organization. These models are often referred to as emissions factors.

1.  Click **Compliance and internal controls** \> **Common** \> **Environmental sustainability** \> **Environmental processes** \> **Environmental processes**. In the **Environmental processes** form, select a process, and then click **Environmental conversion**.

2.  On the **Output flows** tab, click **Add**.

3.  Select the substance and enter the substance quantity.

4.  If appropriate, select a source and destination process for the substance output.
    
    If a conversion has multiple related processes, the **Source process** field can be left blank. Leaving this field blank indicates that the source process of the output flow should be determined in the future. For example, if you have two vehicle processes, you might not want to define a conversion for each one. Instead, you can include both processes as related processes. To make sure that the CO2e flows for each vehicle have the same source as the flows that are used for the destination process, the source process for the output flow can be left blank.

## See also

[Environmental conversion (form)](https://technet.microsoft.com/library/hh209652\(v=ax.60\))

[Set up environmental processes](set-up-environmental-processes.md)

[Set up substances for environmental tracking](set-up-substances-for-environmental-tracking.md)

[Set up substance flows between processes](set-up-substance-flows-between-processes.md)

  


