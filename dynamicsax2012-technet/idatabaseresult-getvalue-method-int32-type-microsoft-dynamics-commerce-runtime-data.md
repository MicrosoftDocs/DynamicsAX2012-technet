---
title: IDatabaseResult.GetValue Method (Int32, Type) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetValue Method (Int32, Type)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.GetValue(System.Int32,System.Type)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.idatabaseresult.getvalue(v=AX.60)
ms:contentKeyID: 65319253
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetValue Method (Int32, Type)

Gets the value for a specific field in the current result set row.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetValue ( _
    index As Integer, _
    valueType As Type _
) As Object
'Usage
Dim instance As IDatabaseResult
Dim index As Integer
Dim valueType As Type
Dim returnValue As Object

returnValue = instance.GetValue(index, _
    valueType)
```

``` csharp
Object GetValue(
    int index,
    Type valueType
)
```

``` c++
Object^ GetValue(
    int index, 
    Type^ valueType
)
```

#### Parameters

  - index  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - valueType  
    Type: [System.Type](https://technet.microsoft.com/en-us/library/42892f65\(v=ax.60\))  

#### Return Value

Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
The field value read.  

## See Also

#### Reference

[IDatabaseResult Interface](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)

[GetValue Overload](idatabaseresult-getvalue-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

