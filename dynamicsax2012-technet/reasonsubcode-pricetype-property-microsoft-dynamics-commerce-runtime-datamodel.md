---
title: ReasonSubCode.PriceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.PriceType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasonsubcode.pricetype(v=AX.60)
ms:contentKeyID: 62210046
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.PriceType
dev_langs:
- CSharp
- C++
- VB
---

# PriceType Property

Gets the type of the price.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRICETYPE")> _
<IgnoreDataMemberAttribute> _
Public Property PriceType As PriceType
    Get
    Friend Set
'Usage
Dim instance As ReasonSubCode
Dim value As PriceType

value = instance.PriceType
```

``` csharp
[ColumnAttribute("PRICETYPE")]
[IgnoreDataMemberAttribute]
public PriceType PriceType { get; internal set; }
```

``` c++
[ColumnAttribute(L"PRICETYPE")]
[IgnoreDataMemberAttribute]
public:
property PriceType PriceType {
    PriceType get ();
    internal: void set (PriceType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceType](pricetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the price.  

## See Also

#### Reference

[ReasonSubCode Class](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

