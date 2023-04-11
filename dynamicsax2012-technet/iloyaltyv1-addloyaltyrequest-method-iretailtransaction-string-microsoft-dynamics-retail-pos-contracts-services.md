---
title: ILoyaltyV1.AddLoyaltyRequest Method (IRetailTransaction, String) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddLoyaltyRequest Method (IRetailTransaction, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV1.AddLoyaltyRequest(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv1.addloyaltyrequest(v=AX.60)
ms:contentKeyID: 47343889
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddLoyaltyRequest Method (IRetailTransaction, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Prompts the user whether to overwrite the existing loyalty item or cancel the operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AddLoyaltyRequest ( _
    retailTransaction As IRetailTransaction, _
    cardNumber As String _
) As Boolean
'Usage
Dim instance As ILoyaltyV1
Dim retailTransaction As IRetailTransaction
Dim cardNumber As String
Dim returnValue As Boolean

returnValue = instance.AddLoyaltyRequest(retailTransaction, _
    cardNumber)
```

``` csharp
bool AddLoyaltyRequest(
    IRetailTransaction retailTransaction,
    string cardNumber
)
```

``` c++
bool AddLoyaltyRequest(
    IRetailTransaction^ retailTransaction, 
    String^ cardNumber
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - cardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if add or update loyalty item to transaction is successful.  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>Throws exception if retailTransaction is null.</p>
<p>-or-</p>
<p>Throws exception if cardNumber is null.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[ILoyaltyV1 Interface](iloyaltyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[AddLoyaltyRequest Overload](iloyaltyv1-addloyaltyrequest-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

