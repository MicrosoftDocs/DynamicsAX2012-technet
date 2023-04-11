---
title: ProductProperty.IsReference Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsReference Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.IsReference
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.isreference(v=AX.60)
ms:contentKeyID: 65320621
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.IsReference
dev_langs:
- CSharp
- C++
- VB
---

# IsReference Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISREFERENCE")> _
<DataMemberAttribute> _
Public Property IsReference As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductProperty
Dim value As Boolean

value = instance.IsReference
```

``` csharp
[ColumnAttribute("ISREFERENCE")]
[DataMemberAttribute]
public bool IsReference { get; internal set; }
```

``` c++
[ColumnAttribute(L"ISREFERENCE")]
[DataMemberAttribute]
public:
property bool IsReference {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

