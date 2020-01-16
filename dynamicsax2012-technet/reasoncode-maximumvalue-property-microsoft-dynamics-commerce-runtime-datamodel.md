---
title: ReasonCode.MaximumValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.MaximumValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.maximumvalue(v=AX.60)
ms:contentKeyID: 62215049
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.MaximumValue
dev_langs:
- CSharp
- C++
- VB
---

# MaximumValue Property

Gets the maximum value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MAXIMUMVALUE")> _
Public Property MaximumValue As Decimal
    Get
    Friend Set
'Usage
Dim instance As ReasonCode
Dim value As Decimal

value = instance.MaximumValue
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MAXIMUMVALUE")]
public decimal MaximumValue { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MAXIMUMVALUE")]
public:
property Decimal MaximumValue {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The maximum value.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

