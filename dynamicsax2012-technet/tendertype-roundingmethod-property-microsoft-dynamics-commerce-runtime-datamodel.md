---
title: TenderType.RoundingMethod Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RoundingMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.RoundingMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.roundingmethod(v=AX.60)
ms:contentKeyID: 62214927
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.RoundingMethod
dev_langs:
- CSharp
- C++
- VB
---

# RoundingMethod Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the rounding method.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ROUNDINGMETHOD")> _
Public Property RoundingMethod As RoundingMethod
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As RoundingMethod

value = instance.RoundingMethod

instance.RoundingMethod = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("ROUNDINGMETHOD")]
public RoundingMethod RoundingMethod { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ROUNDINGMETHOD")]
public:
property RoundingMethod RoundingMethod {
    RoundingMethod get ();
    void set (RoundingMethod value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingMethod](roundingmethod-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [RoundingMethod](roundingmethod-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

