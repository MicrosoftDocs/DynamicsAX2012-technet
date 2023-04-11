---
title: (BRA) Set up a fixed asset group
TOCTitle: (BRA) Set up a fixed asset group
ms:assetid: b9d05a78-a854-4a7d-8f1c-718ba990f63c
ms:mtpsurl: https://technet.microsoft.com/library/Dn305882(v=AX.60)
ms:contentKeyID: 54912984
author: tonyafehr
ms.date: 07/06/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.AssetGroup
- MsDynAx060.Forms.AssetGroup
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up a fixed asset group 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Setting up fixed asset groups can help to simplify the setting up of individual fixed assets. These groups also help classify information for reporting.

You can use the same fixed asset group for assets that have the same characteristics. For example, cars or categories of machinery might be in the same asset groups. You can create posting profiles for each fixed asset group, and select ranges of asset groups in inquiries and on reports.


> [!NOTE]
> <P>This topic applies only if KB 2839295 and KB 2850595 for Microsoft Dynamics AX 2012 R2 are installed, if cumulative update 6 or later for AX 2012 R2 is installed, or if AX 2012 R3 is installed.</P>



## Set up a fixed asset group

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset groups**.

2.  Click **New** to create a fixed asset group. Enter a unique identifier and name.

3.  Click **Value models** and create the value models that will apply to all the fixed assets that are assigned to the fixed asset group.
    

    > [!NOTE]
    > <P>You must enter a value in the <STRONG>Fixed asset group</STRONG> field when you create a fixed asset. Default values for other fields for the fixed asset are inherited from the fixed asset group. These include the value model and its posting layers and depreciation profiles. In the <STRONG>Fixed asset group/value model</STRONG> form, you can view the posting layer of the value model that is created for the fixed asset group.</P>



4.  Close the **Fixed asset group/value model** form.

5.  Click **Depreciation books** and create the depreciation books that will apply to all fixed assets that are assigned to the fixed asset group.

6.  On the **General** tab in the **Fixed asset groups** form, select values in the **Number sequence code** fields, as necessary.
    
      - If you set up number sequences for the automatic numbering of fixed assets, select the **Autonumber fixed assets** check box, and select the number sequence for the fixed asset group in the **Number sequence code** field.
    
      - If you set up number sequences for the automatic numbering of bar codes, select the **Autonumber bar codes** check box, and select the number sequence for bar codes in the **Bar code number sequence** field.


> [!TIP]
> <P>If the system is set up to post acquisition transactions from Accounts payable, you can set up a capitalization threshold so that assets are depreciated by default if they meet a minimum acquisition amount, and if they were acquired from an Accounts payable invoice. For more information, see <A href="about-assets-acquired-through-procurement.md">About assets acquired through procurement</A>.</P>



## Fixed asset groups (Modified form)

Click **Fixed assets** \> **Setup** \> **Fixed asset groups**.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fiscal information FastTab</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Appropriate credit</strong></p></td>
<td><p>Select this check box if the fixed asset receives PIS and COFINS tax credit.</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>Select the method to appropriate the credit of fixed asset.</p>
<ol>
<li><p><strong>Depreciation</strong> – The credit amount is calculated based on the Depreciation transaction.</p></li>
<li><p><strong>Acquisition</strong> – The credit amount is calculated based on Fixed asset acquisition transaction or adjustment.</p></li>
<li><p><strong>Amortization</strong> – The credit amount is calculated based on the Depreciation transaction.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p><strong>Installments</strong></p></td>
<td><p>Enter the number of installments for PIS and COFINS tax credit. This option is available if the selected <strong>Method</strong> is <strong>Acquisition</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Group</strong></p></td>
<td><p>Select the group of fixed asset.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Utilization</strong></p></td>
<td><p>Select the type of utilization of fixed asset.</p></td>
</tr>
<tr class="even">
<td><p><strong>PIS taxation code</strong></p></td>
<td><p>Select the taxation code for PIS tax. The PIS taxation code is used to generate the credit appropriation transaction that is reported into the record F120 or F120 of SPED contributions.</p></td>
</tr>
<tr class="odd">
<td><p><strong>COFINS taxation code</strong></p></td>
<td><p>Select the taxation code for COFINS tax. The COFINS taxation code is used to generate the credit appropriation transaction that is reported into the record F120 or F120 of SPED contributions.</p></td>
</tr>
<tr class="even">
<td><p><strong>ICMS credit</strong></p></td>
<td><p>Select this check box if the fixed asset receives ICMS tax credit in installments.</p></td>
</tr>
<tr class="odd">
<td><p><strong>ICMS credit installments</strong></p></td>
<td><p>Enter the number of installments for ICMS tax credit.</p></td>
</tr>
</tbody>
</table>


## See also

[(BRA) Enter and post fiscal books adjustments, benefits, and incentives](bra-enter-and-post-fiscal-books-adjustments-benefits-and-incentives.md)

  


