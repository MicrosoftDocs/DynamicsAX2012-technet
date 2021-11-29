---
title: Default offset accounts for vendor invoice journals
TOCTitle: Default offset accounts for vendor invoice journals
ms:assetid: ca0941c2-b422-4cb4-b38d-252f11823adc
ms:mtpsurl: https://technet.microsoft.com/library/Dn454568(v=AX.60)
ms:contentKeyID: 57085673
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Default offset accounts for vendor invoice journals 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains the options that are available if you want to specify the default accounts and offset accounts that are automatically displayed in vendor invoice journals. You can assign default offset accounts to vendor groups, vendor accounts, journal names, or journal headers. If you assign default offset accounts to journal names, you can specify whether to use a fixed offset account that can’t be changed, or whether to allow the default entry to be overridden.

Default offset accounts are used in the following vendor invoice journal forms:

  - **Invoice journal**

  - **Invoice register**

  - **Invoice approval journal**

  - **Vendor invoice pool excluding posting details**

## Decide where to assign default accounts

Use the following table to help you decide where to assign default accounts and offset accounts for invoice journals.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Set up default accounts here…</p></th>
<th><p>…to provide default accounts here</p></th>
<th><p>How this affects processing in Microsoft Dynamics AX</p></th>
<th><p>When to use this option</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Vendor group</strong></p>
<p>Set up default offset accounts for vendor groups by using the <strong>Default account setup</strong> form, which is opened from the <strong>Vendor groups</strong> form.</p></td>
<td><p>Vendor account</p>
<p>Journal entries for vendor accounts in the vendor group, if default accounts aren’t specified for vendor accounts</p></td>
<td><p>The default offset accounts for vendor groups are displayed as default offset accounts for vendors in the <strong>Default account setup</strong> form, which is opened from the <strong>All vendors</strong> list page.</p></td>
<td><p>Set up default offset accounts for vendor groups if you typically pay for the same types of things from the same vendor groups over time.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor account</strong></p>
<p>Set up default accounts for vendor accounts by using the <strong>Default account setup</strong> form, which is opened from the <strong>All vendors</strong> list page or the <strong>Vendors</strong> form.</p></td>
<td><p>Journal entries for the vendor account</p></td>
<td><p>The default offset accounts for vendor accounts are displayed as default offset accounts for journal entries for the vendor account.</p></td>
<td><p>Set up default offset accounts for vendors if you typically pay for the same types of things from the same vendors over time.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Journal names</strong></p>
<p>Set up default offset accounts for journals in the <strong>Journal names</strong> form.</p>
<p>Select the <strong>Fixed offset account</strong> check box.</p></td>
<td><p>Journal header that uses the journal name</p>
<p>Journal entries in journals that use the journal name</p></td>
<td><p>If the <strong>Fixed offset account</strong> check box in the <strong>Journal names</strong> form is selected, the offset account for the journal name overrides the default offset account for the vendor or vendor group.</p></td>
<td><p>Use this option to set up journals for specific costs and expenses that are charged to specific accounts, regardless of who the vendor is or what vendor group they are part of.</p></td>
</tr>
<tr class="even">
<td><p><strong>Journal names</strong></p>
<p>Set up default offset accounts for journals in the <strong>Journal names</strong> form.</p>
<p>Clear the <strong>Fixed offset account</strong> check box.</p></td>
<td><p>Journal header</p>
<p>Journal entries in journals that use the journal name</p></td>
<td><p>These default entries are used in journal header forms, and the offset account in the journal header form is used as a default entry in the journal voucher forms.</p>
<p>Default accounts from the <strong>Journal names</strong> form are used only if default accounts aren’t set up for the vendor account.</p></td>
<td><p>Use this option to set up default accounts to use when a default vendor offset account is not assigned.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Journal header</strong></p>
<p>Set up a default offset account for a journal to use as a default entry in the journal voucher forms.</p></td>
<td><p>Journal entries in the journal</p></td>
<td><p>The default offset account for a journal is used as the default entry in the journal voucher forms.</p></td>
<td><p>Use this option to help speed data entry if most entries in a journal have the same offset account.</p></td>
</tr>
</tbody>
</table>


## See also

[Default account setup (form)](https://technet.microsoft.com/library/aa583932\(v=ax.60\))

[Journal names (form)](https://technet.microsoft.com/library/aa617509\(v=ax.60\))

[Vendors (form)](https://technet.microsoft.com/library/aa592162\(v=ax.60\))

[Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\))

[Journal voucher - Invoice approval journal (form)](https://technet.microsoft.com/library/aa498954\(v=ax.60\))

[Journal voucher - Invoice journal (form)](https://technet.microsoft.com/library/aa616218\(v=ax.60\))

[Journal voucher - Invoice register (form)](https://technet.microsoft.com/library/aa575517\(v=ax.60\))

[Vendor invoice pool excluding posting details (form)](https://technet.microsoft.com/library/bb314782\(v=ax.60\))

  


