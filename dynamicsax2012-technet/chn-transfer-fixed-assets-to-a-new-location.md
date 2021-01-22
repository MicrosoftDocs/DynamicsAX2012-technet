---
title: (CHN) Transfer fixed assets to a new location
TOCTitle: (CHN) Transfer fixed assets to a new location
ms:assetid: d8d75d98-19df-4884-8cec-3f86040dd076
ms:mtpsurl: https://technet.microsoft.com/library/Dn306808(v=AX.60)
ms:contentKeyID: 54925752
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Transfer
- Forms.AssetTransfer
- transfer fixed assets
- China
- Location tracking
- Track location
- Transfer fixed asset
- Track locations
- Transfers
- MsDynAx060.Forms.AssetTransfer
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Transfer fixed assets to a new location 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you transfer fixed assets to a new location within your company, you can track the transfer and record the details about the transfer in an XML file. You can export the XML file by using the **GB/T 24589-2010** form. Click **General ledger** \> **Periodic** \> **China** \> **GB/T 24589 Export**.

You can complete this task only If you are using Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2.

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
<td><p>Company information</p></td>
<td><p>Ensure that you have created a company record for your organization. For more information, see <a href="create-or-modify-a-legal-entity.md">Create or modify a legal entity</a>.</p></td>
</tr>
<tr class="even">
<td><p>Accounting</p></td>
<td><p>Create ledger accounts to post the depreciation costs for the operation units to. For more information, see <a href="about-main-accounts-for-fixed-assets.md">About main accounts for fixed assets</a>.</p></td>
</tr>
</tbody>
</table>


## Transfer a fixed asset to a new location

You can use the **Fixed assets** form to transfer the ownership of fixed assets from one location to another.

To transfer a fixed asset to a new location, follow these steps:

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Double-click the fixed asset to transfer.

3.  On the **Action Pane**, click **Transfer to location**.

4.  In the **Transfer the selected fixed asset** form, in the **Transfer location** field, select the location that you want to transfer the fixed asset to.

5.  In the **Transfer comments** field, you can enter comments that are related to the transfer of the fixed asset. For example, enter the reason for the transfer of the fixed asset.

6.  Click **Update**, and then in the **Fixed asset location transfer confirmation** form, click **Transfer** to transfer the fixed asset and close the form.


> [!NOTE]
> <P>Click <STRONG>Review transfer history</STRONG> to open the <STRONG>Fixed asset transfer history</STRONG> form, where you can view the details of this transfer and previous transfers.</P>



## Related tasks

[Basic setup of Fixed assets](basic-setup-of-fixed-assets.md)

[Create a fixed asset](create-a-fixed-asset.md)

[Transfer fixed assets](transfer-fixed-assets.md)

[(CHN, JPN) Fixed asset location transfer history](chn-jpn-fixed-asset-location-transfer-history.md)

[(CHN) Key tasks: Set up and export financial information for GB/T 24589-2010](chn-key-tasks-set-up-and-export-financial-information-for-gb-t-24589-2010.md)

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
<td><ol>
<li><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>.</p></li>
<li><p>Select the <strong>Fixed assets</strong> and <strong>Fixed asset depreciation books</strong> configuration keys.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Accounting supervisors, accounting managers, accountants, accounts payable managers, budget managers, and chief financial officers</p></td>
</tr>
</tbody>
</table>

  


