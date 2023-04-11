---
title: RecordIdTableType Constructor (IEnumerable(Int64), String) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: RecordIdTableType Constructor (IEnumerable(Int64), String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.RecordIdTableType.#ctor(System.Collections.Generic.IEnumerable{System.Int64},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.recordidtabletype.recordidtabletype(v=AX.60)
ms:contentKeyID: 65319247
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RecordIdTableType Constructor (IEnumerable(Int64), String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [RecordIdTableType](recordidtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    recordIds As IEnumerable(Of Long), _
    joinColumn As String _
)
'Usage
Dim recordIds As IEnumerable(Of Long)
Dim joinColumn As String

Dim instance As New RecordIdTableType(recordIds, _
    joinColumn)
```

``` csharp
public RecordIdTableType(
    IEnumerable<long> recordIds,
    string joinColumn
)
```

``` c++
public:
RecordIdTableType(
    IEnumerable<long long>^ recordIds, 
    String^ joinColumn
)
```

#### Parameters

  - recordIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - joinColumn  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[RecordIdTableType Class](recordidtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)

[RecordIdTableType Overload](recordidtabletype-constructor-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

