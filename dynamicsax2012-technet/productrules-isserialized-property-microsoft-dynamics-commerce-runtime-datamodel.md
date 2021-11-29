---
title: ProductRules.IsSerialized Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsSerialized Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.IsSerialized
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.isserialized(v=AX.60)
ms:contentKeyID: 62207628
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.IsSerialized
dev_langs:
- CSharp
- C++
- VB
---

# IsSerialized Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the product is a serializable one.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISSERIALIZED")> _
Public Property IsSerialized As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As Boolean

value = instance.IsSerialized
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISSERIALIZED")]
public bool IsSerialized { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISSERIALIZED")]
public:
property bool IsSerialized {
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

