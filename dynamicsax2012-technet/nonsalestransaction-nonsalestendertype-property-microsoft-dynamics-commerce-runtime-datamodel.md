---
title: NonSalesTransaction.NonSalesTenderType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NonSalesTenderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.NonSalesTenderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.nonsalestransaction.nonsalestendertype(v=AX.60)
ms:contentKeyID: 62213089
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.NonSalesTenderType
dev_langs:
- CSharp
- C++
- VB
---

# NonSalesTenderType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the drawer entry transaction type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TYPE")> _
<IgnoreDataMemberAttribute> _
Public Property NonSalesTenderType As NonSalesTenderType
    Get
    Set
'Usage
Dim instance As NonSalesTransaction
Dim value As NonSalesTenderType

value = instance.NonSalesTenderType

instance.NonSalesTenderType = value
```

``` csharp
[ColumnAttribute("TYPE")]
[IgnoreDataMemberAttribute]
public NonSalesTenderType NonSalesTenderType { get; set; }
```

``` c++
[ColumnAttribute(L"TYPE")]
[IgnoreDataMemberAttribute]
public:
property NonSalesTenderType NonSalesTenderType {
    NonSalesTenderType get ();
    void set (NonSalesTenderType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTenderType](nonsalestendertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [NonSalesTenderType](nonsalestendertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[NonSalesTransaction Class](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

