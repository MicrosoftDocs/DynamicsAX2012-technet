---
title: (RUS) Set up Microsoft Dynamics AX to redeem and return loyalty points
TOCTitle: (RUS) Set up Microsoft Dynamics AX to redeem and return loyalty points
ms:assetid: 5095aa35-ea1f-4ff8-ae22-976b2439398a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497735(v=AX.60)
ms:contentKeyID: 62200263
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailParameters
- Forms.RetailOperations
- redeem
- Forms.RetailLoyaltySchemes
- loyalty point
- loyalty points
- redeem point
- redeem points
- return points
- return point
- return loyalty points
- return loyalty point
- set up loyalty
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up Microsoft Dynamics AX to redeem and return loyalty points 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Follow the steps in this topic to set up a discount loyalty scheme, set up retail parameters for loyalty schemes, and set up an operation to redeem loyalty points at the point of sale (POS).

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
<td><p>Retail in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Set up card types and card numbers. For more information, see <a href="set-up-card-types-and-card-numbers.md">Set up card types and card numbers</a>.</p></li>
<li><p>Set up loyalty programs. For more information, see <a href="set-up-loyalty-programs.md">Set up loyalty programs</a>.</p></li>
<li><p>Set up loyalty schemes, and loyalty customers. For more information, see <a href="set-up-loyalty-schemes.md">Set up loyalty schemes</a> and <a href="set-up-loyalty-customers.md">Set up loyalty customers</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up a discount loyalty scheme

Use the **Loyalty schemes** form to create a redemption rule for a loyalty scheme that is used to redeem loyalty points as discounts for sales transactions at the POS.


> [!NOTE]
> <P>You can’t create a loyalty points discount redemption line and a tender line that have an overlapping effective period for a loyalty scheme.</P>



To perform this task, follow these steps:

1.  Click **Retail** \> **Common** \> **Loyalty** \> **Loyalty schemes**.

2.  Select a loyalty scheme, and then click **Edit**.

3.  On the **Redemption rules** FastTab, click **Add line**, and then specify the program tier, identification code of the loyalty reward point, reward points, amount or quantity, currency, start date, and end date for the redemption rule.
    
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
    <td><p><strong>Program tier</strong></p></td>
    <td><p>Select the loyalty program tier for the redemption rule.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reward point ID</strong></p></td>
    <td><p>Select the loyalty reward point identification code for the redemption rule.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Reward points</strong></p></td>
    <td><p>Enter the number of loyalty points that are deducted when the redemption rule is applied.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Redemption type</strong></p></td>
    <td><p>Select <strong>Loyalty points discount</strong> as the redemption type for the redemption rule.</p>
    <div class="alert">

    > [!NOTE]
    > <P>When you select <STRONG>Loyalty points discount</STRONG> in this field, you can only update the <STRONG>Program tier</STRONG>, <STRONG>Reward point ID</STRONG>, <STRONG>Reward points</STRONG>, <STRONG>Amount or quantity</STRONG>, <STRONG>Currency</STRONG>, <STRONG>Start date</STRONG>, and <STRONG>End date</STRONG> fields on the <STRONG>Redemption rules</STRONG> FastTab.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Amount or quantity</strong></p></td>
    <td><p>Enter an amount or quantity that can be redeemed for the number of loyalty points that you specify in the <strong>Reward points</strong> field. The value in this field depends on the reward point type for the loyalty reward point identification code that you selected in the <strong>Reward point ID</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Currency</strong></p></td>
    <td><p>Enter the currency for the redemption rule.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Start date</strong></p></td>
    <td><p>Select the starting date from which the redemption rule is valid.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>End date</strong></p></td>
    <td><p>Select the ending date until which the redemption rule is valid.</p></td>
    </tr>
    </tbody>
    </table>


## 2\. Set up retail parameters for loyalty schemes

Use the **Retail parameters** form to set up retail parameters for loyalty schemes.

To perform this task, follow these steps:

1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**.

2.  Click **Loyalty**, and then in the **Loyalty** area, select the **Automatically calculate refund points** check box to automatically calculate the number of points to refund for a return transaction.

3.  Select the **Award loyalty points for a partial redemption** check box to award loyalty points for the remaining transaction amount that is paid in cash when you redeem the loyalty points.

## 3\. Set up operations to redeem and check loyalty points

Use the **Operations** form to set up retail operations that are used to redeem loyalty points and check loyalty points balances.

To perform this task, follow these steps:

1.  Click **Retail** \> **Setup** \> **POS** \> **Operations**.

2.  Click **New** or press CTRL+N to create a record.

3.  In the **Operation ID** field, enter 305 as the identification code for the operation.

4.  To create an operation that is used to redeem loyalty points, in the **Operation name** field, enter Redeem loyalty points.
    
    –or–
    
    To create an operation that is used to check loyalty points balances, in the **Operation name** field, enter Loyalty card points balance.

5.  Specify additional details. For more information, see “Set up operations” in [Set up permissions and operations](set-up-permissions-and-operations.md).

## Related tasks

[(RUS) View the loyalty points discount amount for a retail store transaction](rus-view-the-loyalty-points-discount-amount-for-a-retail-store-transaction.md)

[(RUS) Set up the refund payment method control](rus-set-up-the-refund-payment-method-control.md)

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
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the <strong>Maintain retail loyalty</strong> (RetailLoyaltyMaintain) duty.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the following privileges:</p>
<ul>
<li><p><strong>Maintain retail loyalty cards</strong> (RetailLoyaltyCardsMaintain)</p></li>
<li><p><strong>Maintain retail loyalty schemes</strong> (RetailLoyaltySchemesMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


