---
title: DiscountLine.CustomerDiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerDiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.CustomerDiscountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.customerdiscounttype(v=AX.60)
ms:contentKeyID: 49831481
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.CustomerDiscountType
dev_langs:
- CSharp
- C++
- VB
---

# CustomerDiscountType Property

The type of a customer discount, i.e line discount, multiline discount

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CUSTOMERDISCOUNTTYPE")> _
Public Property CustomerDiscountType As CustomerDiscountType
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As CustomerDiscountType

value = instance.CustomerDiscountType

instance.CustomerDiscountType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CUSTOMERDISCOUNTTYPE")]
public CustomerDiscountType CustomerDiscountType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CUSTOMERDISCOUNTTYPE")]
public:
property CustomerDiscountType CustomerDiscountType {
    CustomerDiscountType get ();
    void set (CustomerDiscountType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerDiscountType](customerdiscounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CustomerDiscountType](customerdiscounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

