---
title: ProductRules.CanPriceBeZero Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CanPriceBeZero Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.CanPriceBeZero
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.canpricebezero(v=AX.60)
ms:contentKeyID: 62207986
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.CanPriceBeZero
dev_langs:
- CSharp
- C++
- VB
---

# CanPriceBeZero Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the price of the product may be 0.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ZEROPRICEVALID")> _
<DataMemberAttribute> _
Public Property CanPriceBeZero As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As Boolean

value = instance.CanPriceBeZero
```

``` csharp
[ColumnAttribute("ZEROPRICEVALID")]
[DataMemberAttribute]
public bool CanPriceBeZero { get; internal set; }
```

``` c++
[ColumnAttribute(L"ZEROPRICEVALID")]
[DataMemberAttribute]
public:
property bool CanPriceBeZero {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ProductRules Class](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

