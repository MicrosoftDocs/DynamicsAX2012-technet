---
title: ISaleLineItemV1.TotalPeriodicOfferId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TotalPeriodicOfferId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.TotalPeriodicOfferId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.totalperiodicofferid(v=AX.60)
ms:contentKeyID: 49831376
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.TotalPeriodicOfferId
dev_langs:
- CSharp
- C++
- VB
---

# TotalPeriodicOfferId Property

Returns the 'overall' periodic offer Id. That is, if there is one periodic offer, return its Id.

Otherwise, return text representing total/aggregate offers.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TotalPeriodicOfferId As String
    Get
'Usage
Dim instance As ISaleLineItemV1
Dim value As String

value = instance.TotalPeriodicOfferId
```

``` csharp
string TotalPeriodicOfferId { get; }
```

``` c++
property String^ TotalPeriodicOfferId {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

