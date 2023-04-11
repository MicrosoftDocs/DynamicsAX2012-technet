---
title: AddressType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddressType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.addresstype(v=AX.60)
ms:contentKeyID: 49849793
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.AltDlv
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Business
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Delivery
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.FixedAsset
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Home
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Invoice
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.SWIFT
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.RemitTo
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Other
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Recruit
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Onetime
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.ShipCarrierThirdPartyShipping
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Payment
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Statement
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Service
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Consignment_IN
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Lading_W
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.SMS
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType.Unlading_W
dev_langs:
- CSharp
- C++
- VB
---

# AddressType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Customer Address Type. Ported over from the LogisticsLocationRoleType in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration AddressType
'Usage
Dim instance As AddressType
```

``` csharp
[DataContractAttribute]
public enum AddressType
```

``` c++
[DataContractAttribute]
public enum class AddressType
```

## Members

<table>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>None</td>
<td>No address type specified.</td>
</tr>
<tr class="even">
<td></td>
<td>Invoice</td>
<td>The address used on an invoice.</td>
</tr>
<tr class="odd">
<td></td>
<td>Delivery</td>
<td>A delivery address.</td>
</tr>
<tr class="even">
<td></td>
<td>AltDlv</td>
<td>An alternative delivery address.</td>
</tr>
<tr class="odd">
<td></td>
<td>SWIFT</td>
<td>A SWIFT address.</td>
</tr>
<tr class="even">
<td></td>
<td>Payment</td>
<td>A payment address.</td>
</tr>
<tr class="odd">
<td></td>
<td>Service</td>
<td>A service address.</td>
</tr>
<tr class="even">
<td></td>
<td>Home</td>
<td>A home address.</td>
</tr>
<tr class="odd">
<td></td>
<td>Other</td>
<td>An address not covered by other types (i.e. other).</td>
</tr>
<tr class="even">
<td></td>
<td>Business</td>
<td>A business address.</td>
</tr>
<tr class="odd">
<td></td>
<td>RemitTo</td>
<td>A remit to address.</td>
</tr>
<tr class="even">
<td></td>
<td>ShipCarrierThirdPartyShipping</td>
<td>A shipping carrier address.</td>
</tr>
<tr class="odd">
<td></td>
<td>Statement</td>
<td>A statement address.</td>
</tr>
<tr class="even">
<td></td>
<td>FixedAsset</td>
<td>A fixed asset address.</td>
</tr>
<tr class="odd">
<td></td>
<td>Onetime</td>
<td>A one-time address.</td>
</tr>
<tr class="even">
<td></td>
<td>Recruit</td>
<td>A recruit address.</td>
</tr>
<tr class="odd">
<td></td>
<td>SMS</td>
<td>The SMS address.</td>
</tr>
<tr class="even">
<td></td>
<td>Lading_W</td>
<td>The lading address for RU,LT,LV.</td>
</tr>
<tr class="odd">
<td></td>
<td>Unlading_W</td>
<td>The unlading address for RU,LT,LV.</td>
</tr>
<tr class="even">
<td></td>
<td>Consignment_IN</td>
<td>The consignment address for IN.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

