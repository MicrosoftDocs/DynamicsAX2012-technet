---
title: ILineItemV1.DescriptionAlias Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: DescriptionAlias Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineItemV1.DescriptionAlias
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ilineitemv1.descriptionalias(v=AX.60)
ms:contentKeyID: 49837021
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineItemV1.DescriptionAlias
dev_langs:
- CSharp
- C++
- VB
---

# DescriptionAlias Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

A description alias of the line item

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property DescriptionAlias As String
    Get
    Set
'Usage
Dim instance As ILineItemV1
Dim value As String

value = instance.DescriptionAlias

instance.DescriptionAlias = value
```

``` csharp
string DescriptionAlias { get; set; }
```

``` c++
property String^ DescriptionAlias {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ILineItemV1 Interface](ilineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

