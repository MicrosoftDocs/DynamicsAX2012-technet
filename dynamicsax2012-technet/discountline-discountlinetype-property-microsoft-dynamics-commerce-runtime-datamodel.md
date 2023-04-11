---
title: DiscountLine.DiscountLineType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountLineType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.DiscountLineType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.discountlinetype(v=AX.60)
ms:contentKeyID: 49836092
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.DiscountLineType
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLineType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the discount (i.e. customer discount, periodic discount, etc.)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("DISCOUNTLINETYPE")> _
Public Property DiscountLineType As DiscountLineType
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As DiscountLineType

value = instance.DiscountLineType

instance.DiscountLineType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("DISCOUNTLINETYPE")]
public DiscountLineType DiscountLineType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"DISCOUNTLINETYPE")]
public:
property DiscountLineType DiscountLineType {
    DiscountLineType get ();
    void set (DiscountLineType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLineType](discountlinetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DiscountLineType](discountlinetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

