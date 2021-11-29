---
title: ReasonCode.RandomFactor Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RandomFactor Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.RandomFactor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.randomfactor(v=AX.60)
ms:contentKeyID: 62202472
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.RandomFactor
dev_langs:
- CSharp
- C++
- VB
---

# RandomFactor Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the random factor.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RANDOMFACTOR")> _
Public Property RandomFactor As Decimal
    Get
    Friend Set
'Usage
Dim instance As ReasonCode
Dim value As Decimal

value = instance.RandomFactor
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RANDOMFACTOR")]
public decimal RandomFactor { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RANDOMFACTOR")]
public:
property Decimal RandomFactor {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The random factor.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

