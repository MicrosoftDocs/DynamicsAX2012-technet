---
title: Set up rate masters
TOCTitle: Set up rate masters
ms:assetid: b4285c73-d2db-444c-8fb1-f44678a46052
ms:mtpsurl: https://technet.microsoft.com/library/Dn553193(v=AX.60)
ms:contentKeyID: 62200141
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TMSRateMaster
- rate master
- rate masters
audience: Application User
ms.search.region: Global
---

# Set up rate masters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



Rate masters are part of the rating setup for a shipping carrier. You can use rate masters to determine the available rates for the shipping carrier and to determine whether the rates justify considering the shipping carrier for an assignment.

The rate master is associated with a shipping carrier in the carrier’s rating profile. For each rate master, you must define a rate base type and a rate base.

  - **Rate base type** – Before you set up a rate master, you must set up at least one rate base type. The rate base type can be applied to any rate master. It defines lookup criteria that are used to determine rates of a shipping carrier. Setting up a rate base type requires the following tasks:
    
      - Set up a rate base type with lookup criteria, such as postal code and carrier service.
    
      - Associate a rate master with the rate base type and, on the rate master, provide values for criteria, such as postal code and carrier service.
    
    When you plan transportation for a load, you can enter the values that you provide for the rate base type for the lookup criteria, to help determine the rates.

  - **Rate base** – If you want to set up a tariff structure for the rate master, you can create a rate base. The rate base structures rates in breakpoints.
    
    For example, distances are structured into breakpoints of 50, 100, and 150 miles. A distance of up to 50 miles is charged with 10 USD per assignment, between 50 and 100 miles is charged with 18 USD, and from 100 to 150 miles is charged with 20 USD.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Rate base criteria</p></th>
    <th><p>Break value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>50</p></td>
    <td><p>10 USD</p></td>
    </tr>
    <tr class="even">
    <td><p>100</p></td>
    <td><p>18 USD</p></td>
    </tr>
    <tr class="odd">
    <td><p>150</p></td>
    <td><p>20 USD</p></td>
    </tr>
    </tbody>
    </table>
    
    Before you can create a rate base with break values, you must set up a break master with the criteria for the break values. For more information, see the “Set up a break master” section later in this topic.

## Set up a rate base type

The rate base type is engine specific. You must set up a rate base type before you can set up a rate engine.

1.  Click **Transportation management** \> **Setup** \> **General** \> **Rate base type**.

2.  Click **New** to create a rate base type.

3.  Enter a unique ID and name for the rate base type.

4.  In the **Field type** field, select **Rate base** or **Assignment** to set up criteria fields.

5.  In the lower pane, click **New** to configure additional lookup criteria for the rate base or rate base assignment.
    
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
    <td><p>Indicates the sequence of the lookup fields on the <strong>Rate base assignment</strong> FastTab in the <strong>Rate master</strong> form. You can change the sequence, if needed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>Enter a name for the lookup criteria. The name that you enter here is used as a lookup field on the <strong>Rate base assignment</strong> FastTab in the <strong>Rate master</strong> form.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Field type</strong></p></td>
    <td><p>Specify the lookup criteria as rate based or assignment based.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data type</strong></p></td>
    <td><p>Select a data type for the break unit.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Lookup type</strong></p></td>
    <td><p>Select the criteria for the break unit.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Mandatory</strong></p></td>
    <td><p>Select this check box to make the user-defined fields mandatory for the selected rate base or rate base assignment.</p></td>
    </tr>
    </tbody>
    </table>


## Set up a rate master

Before you set up a rate master, you must set up a rate base type. For more information, see the “Set up a rate base type” section earlier in this topic.

To set up a rate master, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Rating** \> **Rate master**.

2.  Click **New** to create a new rate master.

3.  On the **Overview** FastTab, enter a unique identification and name for the rate master.

4.  In the **Rate base type** field, select the rate base type. When you associate a rate master with a shipping carrier, the rate base type must correspond to the rate base type of the shipping carrier’s rating engine.

5.  On the **Rate base assignment** FastTab, click **New** and enter details to assign the use of the rate master to specific lookup criteria.
    
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
    <td><p><strong>Name</strong></p></td>
    <td><p>Enter a unique ID for the rate base assignment.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Rate base</strong></p></td>
    <td><p>Select the rate base. To create a rate base for the rate master, click <strong>Rate base</strong>. For more information, see the “Create a rate base” section.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Service</strong></p></td>
    <td><p>Select a carrier service for the rate base assignment.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Effective start date and time</strong> and <strong>Effective end date and time</strong></p></td>
    <td><p>Enter a start date and end date and time for the rate base assignment to be in effect.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Additional fields on the <strong>Rate base assignment</strong> FastTab that may be displayed</p></td>
    <td><p>Define additional lookup criteria for the rate base type.</p></td>
    </tr>
    </tbody>
    </table>


## Set up a break master

The break master defines the break values that you must associate with the rate base.

To set up a break master, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Rating** \> **Break master**.

2.  Click **New**, and then enter the details for the break master.
    
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
    <td><p><strong>Break master</strong></p></td>
    <td><p>Enter a unique ID for the break master.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>Enter a descriptive name for the break master.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Data type</strong></p></td>
    <td><p>Select a data type for the value.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Comparison</strong></p></td>
    <td><p>Enter a mathematical comparison symbol for the break unit, such as the less than sign (&lt;). For example, you can use a break unit to specify that if the number of miles is below 100, the rate is 80 USD.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Break unit</strong></p></td>
    <td><p>Enter a unit for the breakpoints in the shipping carrier’s rate, such as Miles or Volume.</p></td>
    </tr>
    </tbody>
    </table>


3.  On the **Details** FastTab, click **New**. In the **Value** field, enter the break unit values.

## Create a rate base

You create rate bases by using the **Rate master** form. You do not have to create a rate base before you set up the rate master. You can create multiple rate bases for a rate master. The rate bases are unique to the rate master.

To create a rate base, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Rating** \> **Rate master**.

2.  Select a rate master, and then click **Rate base**.

3.  In the **Rate base** form, enter the details for the rate base.
    
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
    <td><p><strong>Rate base</strong> and <strong>Name</strong></p></td>
    <td><p>Enter a unique ID and a descriptive name for the rate base.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Break master</strong></p></td>
    <td><p>Select a break master to define the charges for each breakpoint.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Currency</strong></p></td>
    <td><p>The currency in which to rate the shipping carrier.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Minimum charge</strong> and <strong>Maximum charge</strong></p></td>
    <td><p>The minimum and the maximum charge for the shipping carrier.</p></td>
    </tr>
    </tbody>
    </table>


4.  On the **Detail** tab, add the charges for the break values on the line.
    
    The break values are derived from the values that are set up in the **Value** form on the **Details** FastTab.

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
<td><p><strong>Configuration key</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


