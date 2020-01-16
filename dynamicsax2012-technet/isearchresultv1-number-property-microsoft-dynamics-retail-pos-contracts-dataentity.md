---
title: ISearchResultV1.Number Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Number Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISearchResultV1.Number
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isearchresultv1.number(v=AX.60)
ms:contentKeyID: 49851981
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISearchResultV1.Number
dev_langs:
- CSharp
- C++
- VB
---

# Number Property

Gets the number.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Number As String
    Get
'Usage
Dim instance As ISearchResultV1
Dim value As String

value = instance.Number
```

``` csharp
string Number { get; }
```

``` c++
property String^ Number {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

e.g. Customer number for customer result.

## See Also

#### Reference

[ISearchResultV1 Interface](isearchresultv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

