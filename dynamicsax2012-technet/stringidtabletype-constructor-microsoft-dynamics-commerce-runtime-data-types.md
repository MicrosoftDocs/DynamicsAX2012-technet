---
title: StringIdTableType Constructor  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: StringIdTableType Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.StringIdTableType.#ctor(System.Collections.Generic.IEnumerable{System.String},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.stringidtabletype.stringidtabletype(v=AX.60)
ms:contentKeyID: 65323061
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.StringIdTableType.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# StringIdTableType Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [StringIdTableType](stringidtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    stringIds As IEnumerable(Of String), _
    joinColumn As String _
)
'Usage
Dim stringIds As IEnumerable(Of String)
Dim joinColumn As String

Dim instance As New StringIdTableType(stringIds, _
    joinColumn)
```

``` csharp
public StringIdTableType(
    IEnumerable<string> stringIds,
    string joinColumn
)
```

``` c++
public:
StringIdTableType(
    IEnumerable<String^>^ stringIds, 
    String^ joinColumn
)
```

#### Parameters

  - stringIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - joinColumn  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[StringIdTableType Class](stringidtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

