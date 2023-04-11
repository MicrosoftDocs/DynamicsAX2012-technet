---
title: DataColumn.MaxLength Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: MaxLength Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumn.MaxLength
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datacolumn.maxlength(v=AX.60)
ms:contentKeyID: 65319007
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumn.MaxLength
dev_langs:
- CSharp
- C++
- VB
---

# MaxLength Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the maximum length of the column.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property MaxLength As Integer
    Get
    Set
'Usage
Dim instance As DataColumn
Dim value As Integer

value = instance.MaxLength

instance.MaxLength = value
```

``` csharp
public int MaxLength { get; set; }
```

``` c++
public:
property int MaxLength {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[DataColumn Class](datacolumn-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

