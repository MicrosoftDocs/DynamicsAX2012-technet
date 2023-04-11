---
title: DataColumn.DataType Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: DataType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumn.DataType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datacolumn.datatype(v=AX.60)
ms:contentKeyID: 65319150
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumn.DataType
dev_langs:
- CSharp
- C++
- VB
---

# DataType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the data type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property DataType As Type
    Get
    Set
'Usage
Dim instance As DataColumn
Dim value As Type

value = instance.DataType

instance.DataType = value
```

``` csharp
public Type DataType { get; set; }
```

``` c++
public:
property Type^ DataType {
    Type^ get ();
    void set (Type^ value);
}
```

#### Property Value

Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  
Returns [Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\)).  

## See Also

#### Reference

[DataColumn Class](datacolumn-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

