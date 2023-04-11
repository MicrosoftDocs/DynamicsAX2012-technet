---
title: ProductRefinerValue.Value Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefinervalue.value(v=AX.60)
ms:contentKeyID: 65319485
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of this refiner retrieved from the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("VALUE")> _
Public Property Value As String
    Get
    Set
'Usage
Dim instance As ProductRefinerValue
Dim value As String

value = instance.Value

instance.Value = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("VALUE")]
public string Value { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"VALUE")]
public:
property String^ Value {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductRefinerValue Class](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

