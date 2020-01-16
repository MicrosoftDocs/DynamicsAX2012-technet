---
title: 'Scenario: Single-company and cross-company payment settlements'
TOCTitle: 'Scenario: Single-company and cross-company payment settlements'
ms:assetid: 6effec68-65ad-4fba-b682-dc930b45ef26
ms:mtpsurl: https://technet.microsoft.com/library/Gg231813(v=AX.60)
ms:contentKeyID: 36655931
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Scenario: Single-company and cross-company payment settlements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can select transactions for settlement by using the scenarios that are described in this topic. The scenarios that are available to you depend on how the system is configured for your organization. The scenario that applies is determined by the legal entity that you select for the following legal entities that are involved in the payment settlement process:

  - Current legal entity – The legal entity that you are currently using in Microsoft Dynamics AX.

  - Legal entity of the payment – The legal entity that is generating the payment.

  - Legal entity of the invoice – The legal entity that generated the invoice.

In each scenario, you settle a payment with one or more invoices. If a settlement involves multiple legal entities, applicable due-to and due-from accounts are updated, based on the intercompany relationships that are set up for the affected legal entities in the **Intercompany accounting** form.

## Single-company settlement

In this scenario, the current legal entity when you perform the settlement is the same as both the legal entity of the payment and the legal entity of the invoice.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fabrikam</p></th>
<th><p>Fabrikam East</p></th>
<th><p>Fabrikam West</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Current legal entity</p>
<p>Legal entity of the payment</p>
<p>Legal entity of the invoice</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Intercompany payment

In this scenario, the current legal entity when you perform the settlement can differ from the legal entity of the payment. The legal entity of the payment is the same as the legal entity of the invoice.

You must set up intercompany accounting posting accounts between the current legal entity and the legal entity of the payment.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fabrikam</p></th>
<th><p>Fabrikam East</p></th>
<th><p>Fabrikam West</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Current legal entity</p></td>
<td><p>Legal entity of the payment</p>
<p>Legal entity of the invoice</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Intercompany settlement (centralized payments)

In this scenario, the legal entity of the payment and the legal entity of the invoice can differ, if the affected accounts are mapped to the same party ID and are included in an organizational hierarchy.

You must set up intercompany accounting posting accounts between the legal entity of the payment and the legal entity of the invoice.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fabrikam</p></th>
<th><p>Fabrikam East</p></th>
<th><p>Fabrikam West</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Current legal entity</p>
<p>Legal entity of the payment</p></td>
<td><p>Legal entity of the invoice</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Intercompany settlement (centralized payments) and intercompany payment

In this scenario, the current legal entity when you perform the settlement can differ from the legal entity of the payment or the legal entity of the invoice. The legal entity of the payment and the legal entity of the invoice can differ, if the affected accounts are mapped to the same party ID and are included in an organizational hierarchy.

You must set up intercompany accounting posting accounts between the legal entity of the payment and the legal entity of the invoice, and between the current legal entity and the legal entity of the payment.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fabrikam</p></th>
<th><p>Fabrikam East</p></th>
<th><p>Fabrikam West</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Current legal entity</p></td>
<td><p>Legal entity of the payment</p></td>
<td><p>Legal entity of the invoice</p></td>
</tr>
</tbody>
</table>


## See also

[About cross-company payment settlements](about-cross-company-payment-settlements.md)

  


