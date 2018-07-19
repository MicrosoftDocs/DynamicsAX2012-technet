---
title: Use Retail Modern POS in offline mode
TOCTitle: Use Retail Modern POS in offline mode
ms:assetid: 5aa3ede6-267c-4f3a-b1f8-86dac1b889bc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn879453(v=AX.60)
ms:contentKeyID: 63810525
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Use Retail Modern POS in offline mode 


A Retail Modern POS device will go offline if the system is temporarily down or if the channel database is unavailable. When the connection with the channel database is lost, the POS automatically switches to the offline database.

If a data request does not succeed within the **Timeout interval** configured in the offline profile, Retail Modern POS will automatically switch to the offline database and continue the sales transaction.

Retail Modern POS will try to reconnect to either the Retail Server or the channel database after the **Reconnect attempt interval** configured in the offline profile. This reconnect attempt will only occur at the beginning of a transaction.

You can also set Retail Modern POS to connect to an offline document store to include images. For more information, see [Walkthrough: Adding an Image to Product Search Results](walkthrough-adding-an-image-to-product-search-results.md).

## Determine the connection mode of Retail Modern POS

The status header of Retail Modern POS provides an indicator of the current connection status.

![Retail Modern POS Connection Mode](images/Dn879453.RetailModernPOSConnectionMode(en-us,AX.60).png "Retail Modern POS Connection Mode")

The Connection status window in Retail Modern POS displays the status of the last synchronization attempt with the offline database.

![Retail Modern POS Connection Status](images/Dn879453.RetailModernPOSConnectionStatus(en-us,AX.60).png "Retail Modern POS Connection Status")

## Create a button to switch between online and offline modes manually

You can add a button to Retail Modern POS to manually switch between online and offline modes. Create a button for **POS operation 917 – Database connection status**. Use the button as a toggle to connect or disconnect.

## Operations that can be completed when the channel database is offline

You can complete the following operations when the channel database is offline.


> [!TIP]
> <P>Reports and other operations will only act on the data available in the offline database.</P>



<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Operation ID</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>100</p></td>
<td><p>Product sale</p></td>
</tr>
<tr class="even">
<td><p>101</p></td>
<td><p>Price check</p></td>
</tr>
<tr class="odd">
<td><p>102</p></td>
<td><p>Void product</p></td>
</tr>
<tr class="even">
<td><p>103</p></td>
<td><p>Product comment</p></td>
</tr>
<tr class="odd">
<td><p>104</p></td>
<td><p>Price override</p></td>
</tr>
<tr class="even">
<td><p>105</p></td>
<td><p>Set quantity</p></td>
</tr>
<tr class="odd">
<td><p>106</p></td>
<td><p>Clear quantity</p></td>
</tr>
<tr class="even">
<td><p>108</p></td>
<td><p>Product search</p></td>
</tr>
<tr class="odd">
<td><p>109</p></td>
<td><p>Return product</p></td>
</tr>
<tr class="even">
<td><p>115</p></td>
<td><p>Show journal</p></td>
</tr>
<tr class="odd">
<td><p>117</p></td>
<td><p>Add loyalty card</p></td>
</tr>
<tr class="even">
<td><p>123</p></td>
<td><p>Change unit of measure</p></td>
</tr>
<tr class="odd">
<td><p>128</p></td>
<td><p>Override transaction tax from list</p></td>
</tr>
<tr class="even">
<td><p>130</p></td>
<td><p>Override line product tax from list</p></td>
</tr>
<tr class="odd">
<td><p>132</p></td>
<td><p>Deposit override</p></td>
</tr>
<tr class="even">
<td><p>134</p></td>
<td><p>Add affiliation</p></td>
</tr>
<tr class="odd">
<td><p>135</p></td>
<td><p>Add affiliation from list</p></td>
</tr>
<tr class="even">
<td><p>200</p></td>
<td><p>Pay cash</p></td>
</tr>
<tr class="odd">
<td><p>202</p></td>
<td><p>Pay customer account</p></td>
</tr>
<tr class="even">
<td><p>203</p></td>
<td><p>Pay currency</p></td>
</tr>
<tr class="odd">
<td><p>206</p></td>
<td><p>Pay cash quick</p></td>
</tr>
<tr class="even">
<td><p>211</p></td>
<td><p>Void payment</p></td>
</tr>
<tr class="odd">
<td><p>214</p></td>
<td><p>Pay gift card</p></td>
</tr>
<tr class="even">
<td><p>300</p></td>
<td><p>Line discount amount</p></td>
</tr>
<tr class="odd">
<td><p>301</p></td>
<td><p>Line discount percent</p></td>
</tr>
<tr class="even">
<td><p>302</p></td>
<td><p>Total discount amount</p></td>
</tr>
<tr class="odd">
<td><p>303</p></td>
<td><p>Total discount percent</p></td>
</tr>
<tr class="even">
<td><p>500</p></td>
<td><p>Void transaction</p></td>
</tr>
<tr class="odd">
<td><p>501</p></td>
<td><p>Transaction comment</p></td>
</tr>
<tr class="even">
<td><p>503</p></td>
<td><p>Suspend transaction</p></td>
</tr>
<tr class="odd">
<td><p>512</p></td>
<td><p>Issue gift card</p></td>
</tr>
<tr class="even">
<td><p>515</p></td>
<td><p>Recall order</p></td>
</tr>
<tr class="odd">
<td><p>519</p></td>
<td><p>Add to gift card</p></td>
</tr>
<tr class="even">
<td><p>520</p></td>
<td><p>Gift card balance</p></td>
</tr>
<tr class="odd">
<td><p>602</p></td>
<td><p>Customer search</p></td>
</tr>
<tr class="even">
<td><p>603</p></td>
<td><p>Customer clear</p></td>
</tr>
<tr class="odd">
<td><p>612</p></td>
<td><p>Customer add</p></td>
</tr>
<tr class="even">
<td><p>622</p></td>
<td><p>Search</p></td>
</tr>
<tr class="odd">
<td><p>623</p></td>
<td><p>Edit customer</p></td>
</tr>
<tr class="even">
<td><p>701</p></td>
<td><p>Log off</p></td>
</tr>
<tr class="odd">
<td><p>703</p></td>
<td><p>Lock register</p></td>
</tr>
<tr class="even">
<td><p>801</p></td>
<td><p>Inventory lookup</p></td>
</tr>
<tr class="odd">
<td><p>802</p></td>
<td><p>Stock count</p></td>
</tr>
<tr class="even">
<td><p>917</p></td>
<td><p>Database connection status</p></td>
</tr>
<tr class="odd">
<td><p>920</p></td>
<td><p>Time clock</p></td>
</tr>
<tr class="even">
<td><p>921</p></td>
<td><p>View time clock entries</p></td>
</tr>
<tr class="odd">
<td><p>922</p></td>
<td><p>View product details</p></td>
</tr>
<tr class="even">
<td><p>1003</p></td>
<td><p>View reports</p></td>
</tr>
<tr class="odd">
<td><p>1052</p></td>
<td><p>Tender declaration</p></td>
</tr>
<tr class="even">
<td><p>1200</p></td>
<td><p>Declare start amount</p></td>
</tr>
<tr class="odd">
<td><p>1201</p></td>
<td><p>Float entry</p></td>
</tr>
<tr class="even">
<td><p>1210</p></td>
<td><p>Tender removal</p></td>
</tr>
<tr class="odd">
<td><p>1211</p></td>
<td><p>Safe drop</p></td>
</tr>
<tr class="even">
<td><p>1212</p></td>
<td><p>Bank drop</p></td>
</tr>
</tbody>
</table>


## Operations that can’t be completed when the channel database is offline

You can’t complete the following operations when the channel database is offline.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Operation ID</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>207</p></td>
<td><p>Pay loyalty card</p></td>
</tr>
<tr class="even">
<td><p>707</p></td>
<td><p>Activate device</p></td>
</tr>
<tr class="odd">
<td><p>708</p></td>
<td><p>Inactivate device</p></td>
</tr>
<tr class="even">
<td><p>1053</p></td>
<td><p>Blind close shift</p></td>
</tr>
<tr class="odd">
<td><p>1054</p></td>
<td><p>Suspend shift</p></td>
</tr>
<tr class="even">
<td><p>1055</p></td>
<td><p>Close shift</p></td>
</tr>
<tr class="odd">
<td><p>1056</p></td>
<td><p>Print X</p></td>
</tr>
<tr class="even">
<td><p>1057</p></td>
<td><p>Reprint Z</p></td>
</tr>
</tbody>
</table>

  


