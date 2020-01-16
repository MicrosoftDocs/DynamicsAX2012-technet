---
title: (BRA) Configure fiscal printers
TOCTitle: (BRA) Configure fiscal printers
ms:assetid: 0312a2c8-a0a6-4135-a745-25c78f4f34c7
ms:mtpsurl: https://technet.microsoft.com/library/Dn527704(v=AX.60)
ms:contentKeyID: 59626276
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Retail
- printer
- printers
- Brazil
- Forms.RetailConfiguration_BR
- configure printers
- Fiscal
- Fiscal printers
- fiscal printer
- MsDynAx060.Forms.RetailConfiguration_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Configure fiscal printers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Follow the steps in this topic to set up parameters for a fiscal printer configuration, and then associate a fiscal printer configuration with multiple stores or associate a store with multiple fiscal printer configurations.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## Prerequisites

The following table shows the prerequisites that must be in place before you start.

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
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 7 or later</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Brazil</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup task</strong></p></td>
<td><p>Set up retail stores. For more information, see <a href="set-up-a-retail-store.md">Set up a retail store</a>.</p></td>
</tr>
</tbody>
</table>


## Set up and associate a fiscal printer configuration with multiple stores

Use this procedure to set up parameters for a fiscal printer configuration, and then associate a fiscal printer configuration with multiple stores.

To perform this task, follow these steps:

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Fiscal printer configurations**.

2.  In the **Configure by** field, select **Fiscal printer configurations**.

3.  In the **Configuration type** field, select the configuration type to filter the list of fiscal printer configurations by.
    
    Use the information in the following table to determine what configuration type to filter by.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Type</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>None</strong></p></td>
    <td><p>Display the fiscal printer configurations for all of the configuration types.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tax percentage</strong></p></td>
    <td><p>Display the fiscal printer configurations that have a configuration type of <strong>Tax percentage</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Non-fiscal totalizer</strong></p></td>
    <td><p>Display the fiscal printer configurations that have a configuration type of <strong>Non-fiscal totalizer</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Management report</strong></p></td>
    <td><p>Display the fiscal printer configurations that have a configuration type of <strong>Management report</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Payment method</strong></p></td>
    <td><p>Display the fiscal printer configurations that have a configuration type of <strong>Payment method</strong>.</p></td>
    </tr>
    </tbody>
    </table>


4.  To create a fiscal printer configuration record, click **New**, and then specify values in the following fields:
    
    1.  The **Configuration type** field is updated with the configuration type that you selected. You can modify the configuration type.
    
    2.  In the **Configuration purpose** field, select the purpose of the fiscal printer configuration.
        
        Use the information in the following table to decide what configuration purpose to use.
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Purpose</p></th>
        <th><p>Description</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p><strong>User defined</strong></p></td>
        <td><p>Enter a user defined configuration value in the <strong>Configuration value</strong> field.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>Gift card</strong></p></td>
        <td><p>Enter a non-fiscal totalizer value that is used to issue gift cards in the <strong>Configuration value</strong> field.</p>
        <div class="alert">

        > [!NOTE]
        > <P>This option is available only if you select <STRONG>Non-fiscal totalizer</STRONG> in the <STRONG>Configuration type</STRONG> field.</P>


        </div></td>
        </tr>
        <tr class="odd">
        <td><p><strong>Payment method</strong></p></td>
        <td><p>Enter a management report value that is used for the payment method report in the <strong>Configuration value</strong> field.</p>
        <div class="alert">

        > [!NOTE]
        > <P>This option is available only if you select <STRONG>Management report</STRONG> in the <STRONG>Configuration type</STRONG> field.</P>


        </div></td>
        </tr>
        <tr class="even">
        <td><p><strong>Configuration</strong></p></td>
        <td><p>Enter a management report value that is used for the Programa Aplicativo Fiscal - Emissor de Cupom Fiscal (PAF-ECF) configuration report in the <strong>Configuration value</strong> field.</p>
        <div class="alert">

        > [!NOTE]
        > <P>This option is available only if you select <STRONG>Management report</STRONG> in the <STRONG>Configuration type</STRONG> field.</P>


        </div></td>
        </tr>
        <tr class="odd">
        <td><p><strong>Identification</strong></p></td>
        <td><p>Enter a management report value that is used for the PAF-ECF identification report in the <strong>Configuration value</strong> field.</p>
        <div class="alert">

        > [!NOTE]
        > <P>This option is available only if you select <STRONG>Management report</STRONG> in the <STRONG>Configuration type</STRONG> field.</P>


        </div></td>
        </tr>
        <tr class="even">
        <td><p><strong>EFT</strong></p></td>
        <td><p>Enter a payment method value that is used for the Electronic Funds Transfer (EFT) payments in the <strong>Configuration value</strong> field.</p>
        <div class="alert">

        > [!NOTE]
        > <P>This option is available only if you select <STRONG>Payment method</STRONG> in the <STRONG>Configuration type</STRONG> field.</P>


        </div></td>
        </tr>
        </tbody>
        </table>
    
    –or–
    
    To use an existing fiscal printer configuration, select the fiscal printer configuration.

5.  In the **Available Stores** list, select the stores to associate with the selected fiscal printer configuration.

6.  Click **Add** to move the selected stores to the **Selected Stores** list.

## Associate a store with multiple fiscal printer configurations

Use this procedure to associate a store with multiple fiscal printer configurations.

To perform this task, follow these steps:

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Fiscal printer configurations**.

2.  In the **Configure by** field, select **Stores**.

3.  Select a store to associate with fiscal printers.

4.  In the **Available Fiscal printer configurations** list, in the **Configuration type** field, select the configuration type to filter the list of fiscal printer configurations by.
    
    Use the information in the following table to determine what configuration type to filter by.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Type</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>None</strong></p></td>
    <td><p>Display the fiscal printer configurations for all of the configuration types.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tax percentage</strong></p></td>
    <td><p>Display the fiscal printer configurations that have a configuration type of <strong>Tax percentage</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Non-fiscal totalizer</strong></p></td>
    <td><p>Display the fiscal printer configurations that have a configuration type of <strong>Non-fiscal totalizer</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Management report</strong></p></td>
    <td><p>Display the fiscal printer configurations that have a configuration type of <strong>Management report</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Payment method</strong></p></td>
    <td><p>Display the fiscal printer configurations that have a configuration type of <strong>Payment method</strong>.</p></td>
    </tr>
    </tbody>
    </table>


5.  Select the fiscal printer configurations to associate with the selected store.

6.  Click **Add** to move the selected fiscal printer configurations to the **Selected Fiscal printer configurations** list.

## Next step

Perform data integration between Microsoft Dynamics AX and Retail Point of sale (POS). For more information, see “Set up integration with Microsoft Dynamics AX” in [Point of Sale for Microsoft Dynamics AX Retail](point-of-sale.md).

## Related tasks

[About retail stores](about-retail-stores.md)

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
<td><p>Ensure that you select the <strong>Retail</strong> configuration key.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must be a member of the <strong>-SYSADMIN-</strong> security role.</p>
<p>To configure fiscal printers, you must be a member of a security role that includes the <strong>Maintain retail register profiles</strong> (RetailTerminalProfilesMaintain) duty.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the <strong>Maintain retail hardware profile</strong> (RetailHardwareProfileMaintain) privilege.</p></td>
</tr>
</tbody>
</table>

  


