---
title: Set up provision types
TOCTitle: Set up provision types
ms:assetid: 942dba37-0831-4f41-bdbf-55f46c8b9ff2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498395(v=AX.60)
ms:contentKeyID: 36058593
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Set up provision types [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up an account for the revenue recognition of untransferred reserves in the **General ledger parameters** form. For information about the **Provision for reserve** and **Transfer from reserve** transaction types, see [About fixed asset reserves](about-fixed-asset-reserves.md).

## Basic and advanced options for handling profits on fixed assets that are sold

The profit on a fixed asset that is sold is the difference between the sales price and the net book value. The basic option for handling profits is to post both the sales price and the net book value to a profit and loss account to recognize the profit on a profit account in the year of the sale. This option does not require any specific setup. The fixed asset transactions will be posted according to the setup of the accounts for disposal.

## Example

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Sales price of the fixed asset</p></td>
<td><p>10,000</p></td>
</tr>
<tr class="even">
<td><p>Net book value</p></td>
<td><p>6,000</p></td>
</tr>
<tr class="odd">
<td><p>Profit</p></td>
<td><p>4,000</p></td>
</tr>
</tbody>
</table>


<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Profit and loss statement
  </p> </th>
    <th colspan="2"> <p>
   
	 Balance sheet
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p></p> </td>
    <td colspan="1"> <p>
   
	 Assets
  </p> </td>
    <td colspan="1"> <p>
   
	 Liabilities
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Account for profit on sold fixed assets
  </p> </td>
    <td colspan="1"> <p>
   
	 Bank account
  </p> </td>
    <td colspan="1"> <p></p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Credit 4,000
  </p> </td>
    <td colspan="1"> <p>
   
	 Debit 4,000
  </p> </td>
    <td colspan="1"> <p></p> </td>
  </tr>
</table>


The advanced option is used in countries/regions where the tax legislation lets you postpone the taxation of the profit on fixed assets. This option uses reserves. Instead of posting on a profit and loss account, the profit on the fixed asset is posted to the balance sheet as a liability.

## Example

For the same disposal transaction, the profit will be handled as a balance sheet transaction.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Profit and loss statement
  </p> </th>
    <th colspan="2"> <p>
   
	 Balance sheet
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p></p> </td>
    <td colspan="1"> <p>
   
	 Assets
  </p> </td>
    <td colspan="1"> <p>
   
	 Liabilities
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p></p> </td>
    <td colspan="1"> <p>
   
	 Bank account
  </p> </td>
    <td colspan="1"> <p>
   
	 Provision for reserves
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p></p> </td>
    <td colspan="1"> <p>
   
	 Debit 4,000
  </p> </td>
    <td colspan="1"> <p>
   
	 Credit 4,000
  </p> </td>
  </tr>
</table>


Not all profits on fixed assets can be handled as reserves. Usually the local legislation requires that only taxation of profits on fixed assets that have been owned by the organization for a specific period of time can be postponed by using the reserve option.

The local legislation usually defines how long a reserve can exist. Eventually, each reserve must be dissolved. Depending on whether the reserve is dissolved before or after the legal deadline for reserve dissolution, one of following dissolution options is used.

## Option 1: The reserve is dissolved on or before the deadline

If a new fixed asset is acquired as replacement for the old asset, the reserve can be posted as a reduction of the acquisition price of the new fixed asset. In this case, the former profit will not be recognized immediately as one amount in the chart of accounts, but instead, in increments. Because of the reduction of the acquisition price, the depreciation amounts for the new fixed asset will be smaller and the net income will be greater.

**Example**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Profit and loss statement
  </p> </th>
    <th colspan="2"> <p>
   
	 Balance sheet
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p></p> </td>
    <td colspan="1"> <p>
   
	 Assets
  </p> </td>
    <td colspan="1"> <p>
   
	 Liabilities
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p></p> </td>
    <td colspan="1"> <p>
   
	 Transfer from reserve
  </p> </td>
    <td colspan="1"> <p>
   
	 Provision for reserve
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p></p> </td>
    <td colspan="1"> <p>
   
	 Credit 4,000
  </p> </td>
    <td colspan="1"> <p>
   
	 Debit 4,000
  </p> </td>
  </tr>
</table>


## Option 2: The reserve is dissolved after the deadline

If no fixed asset has been acquired on or before the legal deadline, the reserve has to be transferred to the profit and loss statement.

**Example**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Profit and loss statement
  </p> </th>
    <th colspan="2"> <p>
   
	 Balance sheet
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p></p> </td>
    <td colspan="1"> <p>
   
	 Assets
  </p> </td>
    <td colspan="1"> <p>
   
	 Liabilities
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Transfer from reserve
  </p> </td>
    <td colspan="1"> <p></p> </td>
    <td colspan="1"> <p>
   
	 Provision for reserve
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Credit 4,000
  </p> </td>
    <td colspan="1"> <p></p> </td>
    <td colspan="1"> <p>
   
	 Debit 4,000
  </p> </td>
  </tr>
</table>


Use the **Fixed assets provision types** form to enter the legal requirements in the **Length of ownership** and **Months** fields to monitor the deadlines for reserve dissolution.

## See also

[About fixed asset reserves](about-fixed-asset-reserves.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

