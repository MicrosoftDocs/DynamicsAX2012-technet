---
title: DataColumn.DefaultValue Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: DefaultValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumn.DefaultValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datacolumn.defaultvalue(v=AX.60)
ms:contentKeyID: 65317725
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumn.DefaultValue
dev_langs:
- CSharp
- C++
- VB
---

# DefaultValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the default value for the column.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property DefaultValue As Object
    Get
    Set
'Usage
Dim instance As DataColumn
Dim value As Object

value = instance.DefaultValue

instance.DefaultValue = value
```

``` csharp
public Object DefaultValue { get; set; }
```

``` c++
public:
property Object^ DefaultValue {
    Object^ get ();
    void set (Object^ value);
}
```

#### Property Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
Returns [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\)).  

## See Also

#### Reference

[DataColumn Class](datacolumn-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

