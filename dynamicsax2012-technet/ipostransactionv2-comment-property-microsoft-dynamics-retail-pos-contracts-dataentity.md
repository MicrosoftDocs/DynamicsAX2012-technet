---
title: IPosTransactionV2.Comment Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Comment Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV2.Comment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv2.comment(v=AX.60)
ms:contentKeyID: 49842677
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV2.Comment
dev_langs:
- CSharp
- C++
- VB
---

# Comment Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Set comment added by the operator

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
WriteOnly Property Comment As String
    Set
'Usage
Dim instance As IPosTransactionV2
Dim value As String

instance.Comment = value
```

``` csharp
string Comment { set; }
```

``` c++
property String^ Comment {
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IPosTransactionV2 Interface](ipostransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

