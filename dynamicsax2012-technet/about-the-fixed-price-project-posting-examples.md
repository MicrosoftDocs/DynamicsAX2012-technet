---
title: About the fixed-price project posting examples
TOCTitle: About the fixed-price project posting examples
ms:assetid: d6a5c49d-baab-4c2f-aa5c-c98c4643e246
ms:mtpsurl: https://technet.microsoft.com/library/Aa499390(v=AX.60)
ms:contentKeyID: 36059537
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fixed-price
- project posting
audience: Application User
ms.search.region: Global
---

# About the fixed-price project posting examples 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Based on the parameters **On-account invoicing**, **Revenue recognition accounting rule**, and **Matching principle** in the **Project groups** form, transactions are posted to the General ledger in eight different ways. The posting examples in this section illustrate how transactions are posted to the General ledger with each of the eight setup combinations.

## Assumptions

A company wins a fixed-price contract of USD 200,000 based on the following milestone invoicing plan (on account).

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Action</p></th>
<th><p>Time</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>40 percent prepayment on signature</p></td>
<td><p>July</p></td>
<td><p>80,000</p></td>
</tr>
<tr class="even">
<td><p>25 percent on first delivery</p></td>
<td><p>September</p></td>
<td><p>50,000</p></td>
</tr>
<tr class="odd">
<td><p>35 percent on final delivery</p></td>
<td><p>November</p></td>
<td><p>70,000</p></td>
</tr>
</tbody>
</table>


The work takes place from July through November, during which the costs in the following table are consumed.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Time</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>July</p></td>
<td><p>12,000</p></td>
</tr>
<tr class="even">
<td><p>August</p></td>
<td><p>30,000</p></td>
</tr>
<tr class="odd">
<td><p>September</p></td>
<td><p>24,000</p></td>
</tr>
<tr class="even">
<td><p>October</p></td>
<td><p>36,000</p></td>
</tr>
<tr class="odd">
<td><p>November</p></td>
<td><p>18,000</p></td>
</tr>
</tbody>
</table>


Estimates are posted each month, from July through November.

The elimination is posted in December.

## Business example

<table xmlns="http://www.w3.org/1999/xhtml"> <tr><th colspan="1"> <p></p> </th><th colspan="1"> <p>
   
	 Per month
  </p> </th><th colspan="1"> <p>
   
	 Consumption cost
  </p> </th><th colspan="1"> <p>
   
	 Degree of completion
  </p> </th><th colspan="1"> <p>
   
	 Invoiced on-account amount
  </p> </th><th colspan="1"> <p>
   
	 Completed percentage
  </p> </th><th colspan="1"> <p>
   
	 Completed percentage
  </p> </th><th colspan="1"> <p>
   
	 Completed contract
  </p> </th><th colspan="1"> <p>
   
	 Completed contract
  </p> </th></tr> <tr><td colspan="1"> <p></p> </td><td colspan="1"> <p></p> </td><td colspan="1"> <p></p> </td><td colspan="1"> <p></p> </td><td colspan="1"> <p></p> </td><td colspan="1"> <p>
   
	 Cost
  </p> </td><td colspan="1"> <p>
   
	 Revenue
  </p> </td><td colspan="1"> <p>
   
	 Cost 
  </p> </td><td colspan="1"> <p>
   
	 Revenue
  </p> </td></tr> <tr><td colspan="1"> <p>
   
	 Estimate
  </p> </td><td colspan="1"> <p>
   
	 July
  </p> </td><td colspan="1"> <p>
   
	 12,000
  </p> </td><td colspan="1"> <p>
   
	 10
  </p> </td><td colspan="1"> <p>
   
	 80,000
  </p> </td><td colspan="1"> <p>
   
	 12,000
  </p> </td><td colspan="1"> <p>
   
	 20,000
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td></tr> <tr><td colspan="1"> <p>
   
	 Estimate
  </p> </td><td colspan="1"> <p>
   
	 August
  </p> </td><td colspan="1"> <p>
   
	 30,000
  </p> </td><td colspan="1"> <p>
   
	 25
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td><td colspan="1"> <p>
   
	 30,000
  </p> </td><td colspan="1"> <p>
   
	 50,000
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td><td colspan="2"> <p>
   
	 0
  </p> </td></tr> <tr><td colspan="1"> <p>
   
	 Estimate
  </p> </td><td colspan="1"> <p>
   
	 September
  </p> </td><td colspan="1"> <p>
   
	 24,000
  </p> </td><td colspan="1"> <p>
   
	 20
  </p> </td><td colspan="1"> <p>
   
	 50,000
  </p> </td><td colspan="1"> <p>
   
	 24,000
  </p> </td><td colspan="1"> <p>
   
	 40,000
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td><td colspan="2"> <p>
   
	 0
  </p> </td></tr> <tr><td colspan="1"> <p>
   
	 Estimate
  </p> </td><td colspan="1"> <p>
   
	 October
  </p> </td><td colspan="1"> <p>
   
	 36,000
  </p> </td><td colspan="1"> <p>
   
	 30
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td><td colspan="1"> <p>
   
	 36,000
  </p> </td><td colspan="1"> <p>
   
	 60,000
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td><td colspan="2"> <p>
   
	 0
  </p> </td></tr> <tr><td colspan="1"> <p>
   
	 Estimate
  </p> </td><td colspan="1"> <p>
   
	 November
  </p> </td><td colspan="1"> <p>
   
	 18,000
  </p> </td><td colspan="1"> <p>
   
	 15
  </p> </td><td colspan="1"> <p>
   
	 70,000
  </p> </td><td colspan="1"> <p>
   
	 18,000
  </p> </td><td colspan="1"> <p>
   
	 30,000
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td><td colspan="2"> <p>
   
	 0
  </p> </td></tr> <tr><td colspan="1"> <p>
   
	 Elimination
  </p> </td><td colspan="1"> <p>
   
	 December
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td><td colspan="1"> <p>
   
	 0
  </p> </td><td colspan="1"> <p>
   
	 120,000
  </p> </td><td colspan="2"> <p>
   
	 200,000
  </p> </td></tr> <tr><td colspan="1"> <p>
   
	 Total
  </p> </td><td colspan="1"> <p></p> </td><td colspan="1"> <p>
   
	 120,000
  </p> </td><td colspan="1"> <p>
   
	 100
  </p> </td><td colspan="1"> <p>
   
	 200,000
  </p> </td><td colspan="1"> <p>
   
	 120,000
  </p> </td><td colspan="1"> <p>
   
	 200,000
  </p> </td><td colspan="1"> <p>
   
	 120,000
  </p> </td><td colspan="2"> <p>
   
	 200,000
  </p> </td></tr> </table>


> [!NOTE]
> <P>When the cost of hour, expenses, and items is posted in journals, it is generally posted directly to a Profit &amp; loss account on fixed-price projects.</P>



## Ledger posting examples

Click the links in the following table to see the various posting examples.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Topic</p></th>
<th><p>Revenue recognition accounting rule</p></th>
<th><p>Matching principle</p></th>
<th><p>On-account invoicing</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="posting-example-1-fixed-price-project.md">Posting example 1 - fixed-price project</a></p></td>
<td><p>Completed percentage</p></td>
<td><p>Sales value</p></td>
<td><p>Balance</p></td>
</tr>
<tr class="even">
<td><p><a href="posting-example-2-fixed-price-project.md">Posting example 2 - fixed-price project</a></p></td>
<td><p>Completed percentage</p></td>
<td><p>Sales value</p></td>
<td><p>Profit and loss</p></td>
</tr>
<tr class="odd">
<td><p><a href="posting-example-3-fixed-price-project.md">Posting example 3 - fixed-price project</a></p></td>
<td><p>Completed percentage</p></td>
<td><p>Production + profit</p></td>
<td><p>Balance</p></td>
</tr>
<tr class="even">
<td><p><a href="posting-example-4-fixed-price-project.md">Posting example 4 - fixed-price project</a></p></td>
<td><p>Completed Percentage</p></td>
<td><p>Production + profit</p></td>
<td><p>Profit and loss</p></td>
</tr>
<tr class="odd">
<td><p><a href="posting-example-5-fixed-price-project.md">Posting example 5 - fixed-price project</a></p></td>
<td><p>Completed contract</p></td>
<td><p>Sales value</p></td>
<td><p>Balance</p></td>
</tr>
<tr class="even">
<td><p><a href="posting-example-6-fixed-price-project.md">Posting example 6 - fixed-price project</a></p></td>
<td><p>Completed contract</p></td>
<td><p>Sales value</p></td>
<td><p>Profit and loss</p></td>
</tr>
<tr class="odd">
<td><p><a href="posting-example-7-fixed-price-project.md">Posting example 7 - fixed-price project</a></p></td>
<td><p>Completed contract</p></td>
<td><p>Production + profit</p></td>
<td><p>Balance</p></td>
</tr>
<tr class="even">
<td><p><a href="posting-example-8-fixed-price-project.md">Posting example 8 - fixed-price project</a></p></td>
<td><p>Completed contract</p></td>
<td><p>Production + profit</p></td>
<td><p>Profit and loss</p></td>
</tr>
</tbody>
</table>


## See also

[About invoicing fixed-price projects](about-invoicing-fixed-price-projects.md)

[Create an invoice for a fixed-price project](create-an-invoice-for-a-fixed-price-project.md)

[Project groups (form)](https://technet.microsoft.com/library/aa590435\(v=ax.60\))

[Configuring project groups](configuring-project-groups.md)

  


