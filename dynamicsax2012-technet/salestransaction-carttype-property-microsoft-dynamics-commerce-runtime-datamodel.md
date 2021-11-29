---
title: SalesTransaction.CartType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CartType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.CartType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.carttype(v=AX.60)
ms:contentKeyID: 62210320
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.CartType
dev_langs:
- CSharp
- C++
- VB
---

# CartType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the shopping cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CARTTYPE")> _
<IgnoreDataMemberAttribute> _
Public Property CartType As CartType
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As CartType

value = instance.CartType

instance.CartType = value
```

``` csharp
[ColumnAttribute("CARTTYPE")]
[IgnoreDataMemberAttribute]
public CartType CartType { get; set; }
```

``` c++
[ColumnAttribute(L"CARTTYPE")]
[IgnoreDataMemberAttribute]
public:
property CartType CartType {
    CartType get ();
    void set (CartType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartType](carttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CartType](carttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

