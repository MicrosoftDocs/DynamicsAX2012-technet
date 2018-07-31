---
title: Set up warehouse parameters for wave processing
TOCTitle: Set up warehouse parameters for wave processing
ms:assetid: 927e4216-abef-4be7-b8cb-138f6b646342
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553180(v=AX.60)
ms:contentKeyID: 62200119
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Wave
- Forms.WHSParameters
- MsDynAx060.Forms.WHSParameters
audience: Application User
ms.search.region: Global
---

# Set up warehouse parameters for wave processing 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to set up warehouse parameters for wave processing in Microsoft Dynamics AX 2012 R3. You can use wave processing to group picking work for multiple work orders into a single wave.

To use wave processing, specify the following in the **Warehouse management parameters** form:

  - If you can process waves by using a batch job.

  - If you collect information in a log file when waves are processed.

## Set up warehouse management parameters for wave processing

To set up warehouse parameters for wave processing, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse management parameters**.

2.  On the **Wave processing** FastTab, set up the following parameters.
    
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
    <td><p><strong>Wave processing batch group</strong></p></td>
    <td><p>Select the batch group to use when you process waves by using batch jobs. The batch group specifies the server that batch jobs will run on. For more information, see <a href="batch-processing-overview.md">Batch processing overview</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Process waves in batch</strong></p></td>
    <td><p>Select this check box to enable waves to be automatically processed by a batch job. You set up the batch job in the <strong>Process waves</strong> form.</p>
    <div class="alert">

    > [!NOTE]
    > <P>On the wave template that is used to process the wave, you can specify the settings that automate wave processing. If you set up a schedule for the batch job, you should coordinate the timing with the settings for automation in the wave template. For more information, see <A href="create-a-wave-template.md">Create a wave template</A>.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Create wave processing history log</strong></p></td>
    <td><p>Select this check box to automatically save information about a wave in a log file after the wave is processed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Create containerization history log</strong></p></td>
    <td><p>Select this check box to automatically save information about containerization for a wave in a log file after the wave is processed.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Wait for lock (ms)</strong></p></td>
    <td><p>Enter the time, in milliseconds, that an allocation step will wait for a system resource that is locked by another allocation step. When this time is exceeded, the wave is not processed and an error message is displayed.</p></td>
    </tr>
    </tbody>
    </table>



> [!NOTE]
> <P>If you are using <STRONG>Transportation management</STRONG> and <STRONG>Warehouse management</STRONG>, you can specify whether to consolidate loads when you process a wave. For example, this is useful when several small loads can be shipped at the same time. To consolidate loads when you process a wave, on the <STRONG>Loads</STRONG> tab, select the <STRONG>Consolidate loads during wave processing</STRONG> check box.</P>



## Set up full or partial reservation for production waves

For sales orders and kanban orders, inventory must be reserved before the order is released to the warehouse. Otherwise, the items or allocation lines cannot be processed in a wave. However, production orders are slightly more flexible. For production orders, you can specify the following:

  - Allow production orders to be released to the warehouse although all materials cannot be reserved. If you select this option, you must manually repeat the release to warehouse process when the additional materials become available. For example, this is useful if you have the materials that you need to start a production, and can wait until the additional materials become available.

  - Require that all materials are reserved before an order can be released to the warehouse.

To require full reservation or allow partial reservation, follow these steps:

1.  Click **Production control** \> **Setup** \> **Production control parameters**.

2.  On the **General** tab, in the **Release to warehouse** field, select the default setting.

## Next step

[Create a wave template](create-a-wave-template.md)

[Set up containerization](set-up-containerization.md)

## Related tasks

[Set up general warehouse parameters](set-up-general-warehouse-parameters.md)

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

  


