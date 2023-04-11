---
title: ILoyaltyRewardPointLineV1.ExpirationDate Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ExpirationDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.ExpirationDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltyrewardpointlinev1.expirationdate(v=AX.60)
ms:contentKeyID: 62202543
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.ExpirationDate
dev_langs:
- CSharp
- C++
- VB
---

# ExpirationDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the expiration date of the earned reward points.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ExpirationDate As Nullable(Of DateTime)
    Get
    Set
'Usage
Dim instance As ILoyaltyRewardPointLineV1
Dim value As Nullable(Of DateTime)

value = instance.ExpirationDate

instance.ExpirationDate = value
```

``` csharp
Nullable<DateTime> ExpirationDate { get; set; }
```

``` c++
property Nullable<DateTime> ExpirationDate {
    Nullable<DateTime> get ();
    void set (Nullable<DateTime> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[ILoyaltyRewardPointLineV1 Interface](iloyaltyrewardpointlinev1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

