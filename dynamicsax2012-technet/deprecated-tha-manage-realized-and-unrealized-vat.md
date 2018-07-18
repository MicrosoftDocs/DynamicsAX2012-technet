---
title: 'Deprecated: (THA) Manage realized and unrealized VAT'
TOCTitle: (THA) Manage realized and unrealized VAT
ms:assetid: 732f7e28-5164-40c2-8eab-bc5039d892f8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527144(v=AX.60)
ms:contentKeyID: 59623273
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (THA) Manage realized and unrealized VAT 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX 2009 managed unrealized value-added tax (VAT) by using Thailand-specific functionality for “unrealized tax.” Microsoft Dynamics AX 2012 uses the standard Conditional sales tax features to manage both realized and unrealized VAT.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reason for deprecation</p></td>
<td><p>In AX 2012, the Thailand-specific features were moved from the GLS layer to the SYS layer. This consolidation gave us the opportunity to use the standard conditional sales tax functionality that is provided in the SYS layer of Microsoft Dynamics AX. A hotfix was released, and we are deprecating the Thailand-specific Unrealized VAT features. Instead, we will use the standard Conditional sales tax features that are provided in AX 2012.</p>
<p>These changes were released in a hotfix in 2012. See <a href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2636555">KB article 2636555</a>.</p>
<div>

> [!NOTE]
> <P>The code that corresponds to these features is still available but will be removed in a future release.</P>


</div>
<p>For more information, see the white paper that describes the changes that are included in the Thai hotfix:</p>
<ul>
<li><p><a href="https://mbs.microsoft.com/partnersource/deployment/documentation/whitepapers/ax2012_thailand_wp">Country-specific updates for Thailand (in English)</a></p></li>
<li><p><a href="https://mbs.microsoft.com/downloads/public/ax2012docs/country_specific_updates_for_thailand_ax2012_translation.pdf">Country-specific updates for Thailand (in Thai)</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Conditional sales tax for VAT calculations and new number sequences in the accounts receivable parameters (In the Thai hotfix, this feature is referred to as Manage Realized and Unrealized VAT.)</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>General ledger</p>
<p>Accounts payable</p>
<p>Accounts receivable</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>This change does not affect application upgrade.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

