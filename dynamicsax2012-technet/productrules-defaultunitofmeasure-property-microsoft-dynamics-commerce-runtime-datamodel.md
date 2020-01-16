---
title: ProductRules.DefaultUnitOfMeasure Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DefaultUnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.DefaultUnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.defaultunitofmeasure(v=AX.60)
ms:contentKeyID: 62205518
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.DefaultUnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# DefaultUnitOfMeasure Property

Gets the default unit of measure for the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DEFAULTUNITOFMEASURE")> _
<DataMemberAttribute> _
Public Property DefaultUnitOfMeasure As String
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As String

value = instance.DefaultUnitOfMeasure
```

``` csharp
[ColumnAttribute("DEFAULTUNITOFMEASURE")]
[DataMemberAttribute]
public string DefaultUnitOfMeasure { get; internal set; }
```

``` c++
[ColumnAttribute(L"DEFAULTUNITOFMEASURE")]
[DataMemberAttribute]
public:
property String^ DefaultUnitOfMeasure {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductRules Class](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

