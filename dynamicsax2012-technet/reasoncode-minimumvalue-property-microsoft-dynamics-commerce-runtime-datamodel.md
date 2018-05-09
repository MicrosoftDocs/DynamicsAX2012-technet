---
title: ReasonCode.MinimumValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MinimumValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.MinimumValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.minimumvalue(v=AX.60)
ms:contentKeyID: 62214234
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.MinimumValue
dev_langs:
- CSharp
- C++
- VB
---

# MinimumValue Property

Gets the minimum value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MINIMUMVALUE")> _
<DataMemberAttribute> _
Public Property MinimumValue As Decimal
    Get
    Friend Set
'Usage
Dim instance As ReasonCode
Dim value As Decimal

value = instance.MinimumValue
```

``` csharp
[ColumnAttribute("MINIMUMVALUE")]
[DataMemberAttribute]
public decimal MinimumValue { get; internal set; }
```

``` c++
[ColumnAttribute(L"MINIMUMVALUE")]
[DataMemberAttribute]
public:
property Decimal MinimumValue {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The minimum value.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

