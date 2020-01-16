---
title: ProductRules.DateOfBlocking Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DateOfBlocking Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.DateOfBlocking
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.dateofblocking(v=AX.60)
ms:contentKeyID: 62207973
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.DateOfBlocking
dev_langs:
- CSharp
- C++
- VB
---

# DateOfBlocking Property

Gets the date of blocking.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DATEBLOCKED")> _
Public Property DateOfBlocking As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As DateTimeOffset

value = instance.DateOfBlocking
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DATEBLOCKED")]
public DateTimeOffset DateOfBlocking { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DATEBLOCKED")]
public:
property DateTimeOffset DateOfBlocking {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[ProductRules Class](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

