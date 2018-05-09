---
title: About Environmental sustainability
TOCTitle: About Environmental sustainability
ms:assetid: 4ee44720-a987-440c-99fe-3bb5914c316b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208774(v=AX.60)
ms:contentKeyID: 36057061
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- environment
- environmental sustainability
- sustain
- sustainability
---

# About Environmental sustainability 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Environmental sustainability dashboard helps you determine your organization’s environmental footprint. By using the dashboard, you can track the raw materials and energy that your organization consumes. You can then calculate and record the flow of finished products to customers, and the flow of hazardous emissions into the environment. When you adjust the way that your organization views consumption, you can take the following steps:

  - Evaluate your organization’s current effect on the environment.

  - Identify opportunities to reduce your organization’s environmental footprint.

  - Calculate and record the flow of potentially hazardous substances into the environment.

  - Implement environmentally sustainable practices.

  - Maintain your status as a preferred vendor for customers.

You can use the reporting framework of the [Global Greenhouse Protocol (GHG)](http://go.microsoft.com/fwlink/?linkid=219185%26clcid=0x409) and the [Global Reporting Initiative (GRI)](http://go.microsoft.com/fwlink/?linkid=219186%26clcid=0x409) to help report on the acquisition and emission of multiple types of substances.

The following process flow illustrates the business process for Environmental sustainability.

![5623aa0e-650a-476b-9e1e-0da5a9aeae77](images/Hh242840.5623aa0e-650a-476b-9e1e-0da5a9aeae77(AX.60).gif "5623aa0e-650a-476b-9e1e-0da5a9aeae77")

## Example: How Fabrikam uses Environmental sustainability

This scenario describes the steps that Fabrikam takes to set up Environmental sustainability.

Fabrikam manufactures lamps. During the manufacturing and packaging processes, Fabrikam purchases raw materials, such as plastic pellets and steel. Fabrikam also produces indirect emissions, through its use of electricity, and direct emissions, through its use of fossil fuels for heating.

As it moves toward environmental sustainability, Fabrikam uses the Environmental sustainability dashboard to determine the impact that the organization's everyday business has on the environment, and to discover solutions for reducing the organization's environmental impact.

The following sections describe the high-level steps that Fabrikam takes to start measuring its environmental impact:

  - Prerequisites for setting up the Environmental sustainability dashboard

  - Setup of the Environmental sustainability dashboard

  - Reporting on collected data

## Setup prerequisites

Before the Environmental sustainability dashboard is set up, Fabrikam considers which features meet the requirements of the organization's operations. Considerations for environmental tracking include the following issues:

  - Organizational and operational boundaries – Determine which organizations and operations in Fabrikam are included.

  - Equity share vs. control – Determine the basis that is used to report on the impact of shared assets. Reporting can be based on the organization's partial ownership, or equity share. Alternatively, reporting can be based on the control that the organization exerts on the asset, or control.

  - Emissions sources and scope – Determine which emission sources and scope levels are included.

  - Measurement and calculation methods – Determine how Fabrikam measures the substances that it wants to track, and how it performs calculations.

  - Direct and indirect energy types – Determine which direct and indirect energy types are included.

Fabrikam purchases materials from several sources. The following list describes some of the materials that Fabrikam must purchase:

  - Water and electricity to cool and operate the organization's machinery

  - Oil to heat the organization's buildings

  - Steel for the organization's projects

  - Plastics for the organization's packaging

Before he sets up the Environmental sustainability dashboard, Vince, the Fabrikam operations manager, must perform a process analysis. This analysis examines how materials enter the company, and how much waste is created during regular business processes. After Vince identifies all parts of the operation, he creates a process map in Microsoft Dynamics AX. This map illustrates how materials pass through the Fabrikam organization.

Vince must make sure that he includes all the materials that the company wants to track. For example, water use and electricity use are not usually recorded, but they are tracked by financial cost. The plastic that is used for packaging is tracked in inventory and by financial cost, but the actual use may not always be tracked. As a result, there may be a surplus or a deficit of plastic in the organization’s inventory.

After Vince creates the process map, he can set up the Environmental sustainability dashboard in Microsoft Dynamics AX and begin tracking the usage of materials at Fabrikam. He can then create reports based on the information that he tracks.

## Setup

The following table contains a list of tasks that Vince must complete to set up the Environmental sustainability dashboard for Fabrikam. These tasks must be performed in the order in which they are listed.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1. <a href="set-up-environmental-parameters.md">Set up environmental parameters</a>.</p></td>
<td><p>Define the criteria that are used to create substance flows for purchase orders, and set number sequence codes and references.</p></td>
</tr>
<tr class="even">
<td><p>2. <a href="set-up-substance-categories.md">Set up substance categories</a>.</p></td>
<td><p>Define categories for the substances that are tracked.</p></td>
</tr>
<tr class="odd">
<td><p>3. <a href="set-up-substances-for-environmental-tracking.md">Set up substances for environmental tracking</a>.</p></td>
<td><p>Create records for the types of substances that are tracked.</p></td>
</tr>
<tr class="even">
<td><p>4. <a href="set-up-environmental-processes.md">Set up environmental processes</a>.</p></td>
<td><p>Create records that are used to track environmental acquisitions, conversions, and emission points.</p></td>
</tr>
<tr class="odd">
<td><p>5. <a href="set-up-substance-flows-between-processes.md">Set up substance flows between processes</a>.</p></td>
<td><p>Define references that link the substance flow between two processes.</p></td>
</tr>
<tr class="even">
<td><p>6. <a href="set-up-substance-conversions.md">Set up substance conversions</a>.</p></td>
<td><p>Set up records that contain conversion information for substances that can be linked to processes.</p></td>
</tr>
<tr class="odd">
<td><p>7. <a href="set-up-delete-or-deactivate-a-meter.md">Set up, delete, or deactivate a meter</a>.</p></td>
<td><p>Create records that contain meter readings, so that the inflow and outflow of substances such as electricity and water can be tracked.</p></td>
</tr>
<tr class="even">
<td><p>8. <a href="assign-a-worker-to-meters-or-process-references.md">Assign a worker to meters or process references</a>.</p></td>
<td><p>Assign responsibility for data collection to users or user groups.</p></td>
</tr>
</tbody>
</table>


After Vince sets up the Environmental sustainability dashboard in Microsoft Dynamics AX, Fabrikam workers can help track and report on the organization’s environmental impact.

## Entering and collecting data

After setup is complete, Fabrikam must gather enough data to calculate and report on the organization's environmental impact. Workers who belong to various roles throughout the organization help collect data. When the Environmental sustainability dashboard is activated, workers may be required to enter additional data into forms while they perform their regular job duties. The following table describes the tasks that various Fabrikam workers can perform to help collect data.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Worker</p></th>
<th><p>Task description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="create-a-purchase-order-for-items-that-have-an-environmental-impact.md">Create a purchase order for items that have an environmental impact</a>.</p></td>
<td><p>Alicia, purchasing agent</p></td>
<td><p>When Alicia creates a purchase order for a substance that is tracked, such as 500 gallons of oil, the <strong>Environment</strong> tab appears in the <strong>Purchase order</strong> form. A substance flow line is created for the 500 gallons of oil.</p></td>
</tr>
<tr class="even">
<td><p><a href="record-accidental-substance-flows.md">Record accidental substance flows</a>.</p></td>
<td><p>Karl, materials manager</p></td>
<td><p>If an accidental substance flow occurs, for example, a burst water pipe in a warehouse, Karl can create a record that documents the water usage. In this record, Karl can mark the water usage as an accidental substance flow. Later, when calculations and reporting are performed on the water usage in each warehouse, the calculations take account of the water that was spilled in the accidental flow.</p></td>
</tr>
<tr class="odd">
<td><p><a href="enter-a-meter-reading.md">Enter a meter reading</a>.</p></td>
<td><p>Karl, materials manager</p></td>
<td><p>If Fabrikam reports on the quarterly cycle of natural gas usage in its main warehouse, Karl reads a meter at the end of each quarter and enters the numbers in Microsoft Dynamics AX. Over time, Fabrikam can see how much natural gas is used per quarter, and what related hazardous materials are released into the atmosphere. Based on this data, Fabrikam can implement new strategies to reduce its natural gas usage.</p></td>
</tr>
<tr class="even">
<td><p>Enter information in <strong>My meter readings and substance entries</strong>.</p></td>
<td><p>Shannon, machine operator</p></td>
<td><p>When data cannot be collected by using an existing process, Vince can assign the responsibility for collecting the data to Shannon. Shannon can then log on to Enterprise Portal for Microsoft Dynamics AX and enter information about substance flows that are relevant to her work.</p></td>
</tr>
</tbody>
</table>


## Reporting collected data and information

After enough time has passed for Fabrikam to collect substantial data, reports can be created in either the Microsoft Dynamics AX client or Enterprise Portal.


> [!NOTE]
> <P>Depending on the setup and configuration of the reporting functionality that generates and publishes data, the actual reports and report details vary in complexity and in the range of data that can be displayed.</P>



The Environmental sustainability reports show the effects that Fabrikam’s business operations have on the environment. By using the data in these reports, Fabrikam can identify areas where the organization can modify its business practices to reduce its environmental impact. The following table lists the reports that Fabrikam can create in Enterprise Portal.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Report name</p></th>
<th><p>Report type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Energy consumption</p></td>
<td><p>Line graph</p></td>
<td><p>The x-axis of this graph represents increments of one month, and the y-axis represents the units of energy that are used. Typically, energy usage is measured in megajoules (MJ).</p></td>
</tr>
<tr class="even">
<td><p>Greenhouse gas emissions</p></td>
<td><p>Bar graph</p></td>
<td><p>The x-axis of this graph represents increments of one month, and the y-axis represents the units of greenhouse gasses that are emitted. Greenhouse gas emissions are measured in metric tons of CO2 equivalent (tCO2e).</p></td>
</tr>
<tr class="odd">
<td><p>Energy costs by energy type</p></td>
<td><p>Tabulated report</p></td>
<td><p>This report displays the cost of energy for each type of energy that is calculated. The dimensions include direct and indirect energy substances, and the destination process.</p></td>
</tr>
<tr class="even">
<td><p>Direct energy consumption mix</p></td>
<td><p>Pie chart</p></td>
<td><p>This chart displays the consumption of direct energy substances during the month that is selected in the Energy consumption graph.</p></td>
</tr>
<tr class="odd">
<td><p>Indirect energy consumption mix</p></td>
<td><p>Pie chart</p></td>
<td><p>This chart displays the consumption of indirect energy substances during the month that is selected in the Energy consumption graph.</p></td>
</tr>
<tr class="even">
<td><p>Greenhouse gas emissions by process</p></td>
<td><p>Tabulated report</p></td>
<td><p>This report groups processes by parent information, or scope, so that the child processes are included in the values. Totals are displayed at the parent level.</p></td>
</tr>
<tr class="odd">
<td><p>Substance entry status</p></td>
<td><p>Tabulated report</p></td>
<td><p>This report displays assignments for data entry and identifies whether data is entered on time.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

