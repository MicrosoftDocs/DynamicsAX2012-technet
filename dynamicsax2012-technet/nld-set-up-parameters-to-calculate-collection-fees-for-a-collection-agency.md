---
title: (NLD) Set up parameters to calculate collection fees for a collection agency
TOCTitle: (NLD) Set up parameters to calculate collection fees for a collection agency
ms:assetid: e6464942-79a6-42c2-a443-b9c920178c3c
ms:mtpsurl: https://technet.microsoft.com/library/Dn789108(v=AX.60)
ms:contentKeyID: 62519968
author: tonyafehr
ms.date: 07/14/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.Currency
- Forms.CustParameters
- Forms.CustCollectionLetterNote
- Forms.Dialog
- calculate collection fees
- collection agency
- collection fees for a collection agency
- Forms.CustCollectionAgencyFeeSetup_W
- collect overdue payments
- Forms.CustCollectionAgencyGracePeriodSetup_W
audience: Application User
ms.search.region: Netherlands
---

# (NLD) Set up parameters to calculate collection fees for a collection agency 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to enable the collection of overdue payments through a collection agency and how to define the criteria that are used to calculate collection fees.

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
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R3</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Netherland</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable parameters</p></td>
<td><p>To enable the collection of overdue payments through a collection agency, make sure to follow these steps:</p>
<ol>
<li><p>In the <strong>Accounts receivable parameters</strong> form, click <strong>Collections</strong> link, on the <strong>Collection letter</strong> FastTab, select the <strong>Refer to collection agency</strong> check box to enable the collection of overdue payments through a collection agency.</p></li>
<li><p>Optional: In the <strong>Collection agency tax rate</strong> field, enter the tax rate if VAT is applicable for the collection fee.</p></li>
<li><p>In the <strong>Grace period for dues transfer</strong> field, enter the number of days after which the overdue amount is transferred to the collection agency for collection.</p></li>
</ol>
<p></p></td>
</tr>
</tbody>
</table>


## Specify grace periods for customers

To set up grace periods for customers or customer groups, follow these steps:

1.  Click **Accounts receivable** \> **Setup** \> **Collections** \> **Collection letter**. Click **Collection agency** \> **Collection agency grace period setup**.

2.  Click **New** to create a new record. In the **Account code** field, select the account type.

3.  In the **Account/Group number** field, select the customer or customer group number.

4.  Optional: In the **From date** and **To date** fields, select the starting date and ending date of the period for which the grace period is valid.

5.  In the **Grace period in days after transaction date** field, enter the number of days for the grace period, by the end of which the payments must be made.

## Define criteria to calculate collection fees

Use the **Collection agency fee setup** form to set up the criteria that are used to calculate the collection fee for the overdue payment.

1.  Click **Accounts receivable** \> **Setup** \> **Collections** \> **Collection letter**. Click **Collection agency** \> **Collection agency fee setup**.

2.  Click **New** to create a new record. In the **Currency** field, select the currency that is used to calculate the collection fee.
    

    > [!NOTE]
    > <P>Select the <STRONG>Reference currency for triangulation</STRONG> check box in the <STRONG>Currencies</STRONG> form to triangulate the currencies and calculate the collection fee. For more information, see <A href="https://technet.microsoft.com/library/aa582902(v=ax.60)">Currencies (form)</A>.</P>



3.  Optional: In the **From date** and **To date** fields, select the starting date and ending date of the period for which the collection fee is valid for the currency.

4.  In the **Min fee** and **Max fee** fields, enter the minimum and maximum collection fee amounts that are collected for the overdue payment.

5.  In the lower pane, click **Add** to specify the amount ranges and rates that are used to calculate the collection fee.
    
    For example, following are the amount ranges and percentage of interest that are specified in the lower pane:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Amount range</p></th>
    <th><p>Percentage of interest</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>0 to EUR 2500</p></td>
    <td><p>15%</p></td>
    </tr>
    <tr class="even">
    <td><p>EUR 2500 to EUR 5000</p></td>
    <td><p>10%</p></td>
    </tr>
    <tr class="odd">
    <td><p>EUR 5000 to EUR 10000</p></td>
    <td><p>5%</p></td>
    </tr>
    <tr class="even">
    <td><p>EUR 10000 and above</p></td>
    <td><p>1%</p></td>
    </tr>
    </tbody>
    </table>
    
    Based on the values above, the collection fee for an overdue payment of EUR 3500 is calculated as follows:
    
    Overdue payment = EUR 3500 (EUR 2500 + EUR 1000)
    
    15% \* EUR 2500 = EUR 375
    
    10% \* EUR 1000 = EUR 100
    
    Total collection fee = EUR 475

6.  Create and post collection letters to view the calculated collection fee. For more information, see [Create collection letters](create-collection-letters.md) and [Print/post collection letters (form)](https://technet.microsoft.com/library/aa589938\(v=ax.60\)).

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Select the <strong>Collection letter</strong> configuration key.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To perform this task, you must be a member of the following security roles:</p>
<ul>
<li><p><strong>Collection agent</strong> (CollectionLetterCollectionsAgent)</p></li>
<li><p><strong>Collection manager</strong> (CollectionLetterCollectionsManager)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


