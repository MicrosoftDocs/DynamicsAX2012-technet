---
title: (BRA) Create a hierarchical chart of accounts
TOCTitle: (BRA) Create a hierarchical chart of accounts
ms:assetid: a378a6b4-897e-4feb-9870-19cecb8b837e
ms:mtpsurl: https://technet.microsoft.com/library/JJ710578(v=AX.60)
ms:contentKeyID: 49384470
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- ledger
- BRA
- Brazil
- parent ledger
- parent ledger with children
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create a hierarchical chart of accounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up a hierarchy of the charts of accounts for a legal entity to generate legal reports. You can specify an account as a parent main account and add other main accounts as children to the parent main account. You cannot delete an account after it is specified as a parent account.

The following table shows an example of an account structure.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Account number</strong></p></td>
<td><p><strong>Parent account</strong></p></td>
<td><p><strong>Level</strong></p></td>
</tr>
<tr class="even">
<td><p>1</p></td>
<td><p>None</p></td>
<td><p>1</p></td>
</tr>
<tr class="odd">
<td><p>11</p></td>
<td><p>1</p></td>
<td><p>2</p></td>
</tr>
<tr class="even">
<td><p>111</p></td>
<td><p>11</p></td>
<td><p>3</p></td>
</tr>
<tr class="odd">
<td><p>1111</p></td>
<td><p>111</p></td>
<td><p>4</p></td>
</tr>
<tr class="even">
<td><p>1112</p></td>
<td><p>111</p></td>
<td><p>4</p></td>
</tr>
<tr class="odd">
<td><p>1113</p></td>
<td><p>111</p></td>
<td><p>4</p></td>
</tr>
<tr class="even">
<td><p>115</p></td>
<td><p>11</p></td>
<td><p>3</p></td>
</tr>
<tr class="odd">
<td><p>1151</p></td>
<td><p>115</p></td>
<td><p>4</p></td>
</tr>
<tr class="even">
<td><p>1152</p></td>
<td><p>115</p></td>
<td><p>4</p></td>
</tr>
<tr class="odd">
<td><p>12</p></td>
<td><p>1</p></td>
<td><p>2</p></td>
</tr>
</tbody>
</table>


Use the **Main accounts - chart of accounts: %1** form to create a hierarchy of accounts.

1.  Click **General ledger** \> **Common** \> **Main accounts**. Double-click a main account, or on the **Action Pane**, click **Main account**.
    
    –or–
    
    Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**. On the **Main accounts** FastTab, double-click a main account, or click **New**.

2.  For a new account, in the **Main account** and **Name** fields, enter an account number and a name for the account.

3.  In the **Select the level of main account to display** field, select **Chart of accounts**.

4.  In the **Parent account** field, select an account number to indicate the parent account. Leave this field blank to indicate that this account does not have a parent account.

## See also

[(BRA) Chart of accounts report (LedgerCOAReport\_BR)](https://technet.microsoft.com/library/jj710460\(v=ax.60\))

[(BRA) Main accounts - chart of accounts (modified form)](https://technet.microsoft.com/library/jj710470\(v=ax.60\))

  


