---
title: ProductProperty.Value Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.Value
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.value(v=AX.60)
ms:contentKeyID: 62209555
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property

Gets or sets the value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property Value As Object
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As Object

value = instance.Value

instance.Value = value
```

``` csharp
[IgnoreDataMemberAttribute]
public Object Value { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property Object^ Value {
    Object^ get ();
    void set (Object^ value);
}
```

#### Property Value

Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
The value.  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

