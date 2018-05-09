---
title: RecordIdTableType Constructor (String, IEnumerable(Int64)) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: RecordIdTableType Constructor (String, IEnumerable(Int64))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.RecordIdTableType.#ctor(System.String,System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.types.recordidtabletype.recordidtabletype(v=AX.60)
ms:contentKeyID: 65319567
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RecordIdTableType Constructor (String, IEnumerable(Int64))

Initializes a new instance of the [RecordIdTableType](recordidtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    tableName As String, _
    recordIds As IEnumerable(Of Long) _
)
'Usage
Dim tableName As String
Dim recordIds As IEnumerable(Of Long)

Dim instance As New RecordIdTableType(tableName, _
    recordIds)
```

``` csharp
public RecordIdTableType(
    string tableName,
    IEnumerable<long> recordIds
)
```

``` c++
public:
RecordIdTableType(
    String^ tableName, 
    IEnumerable<long long>^ recordIds
)
```

#### Parameters

  - tableName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - recordIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[RecordIdTableType Class](recordidtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)

[RecordIdTableType Overload](recordidtabletype-constructor-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

