---
title: IDatabaseResult.GetValue(T) Method (String) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetValue(T) Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.GetValue``1(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn968350(v=AX.60)
ms:contentKeyID: 65320966
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetValue(T) Method (String)

Gets the value for a specific field in the current result set row.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetValue(Of T) ( _
    fieldName As String _
) As T
'Usage
Dim instance As IDatabaseResult
Dim fieldName As String
Dim returnValue As T

returnValue = instance.GetValue(fieldName)
```

``` csharp
T GetValue<T>(
    string fieldName
)
```

``` c++
generic<typename T>
T GetValue(
    String^ fieldName
)
```

#### Type Parameters

  - T

#### Parameters

  - fieldName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: T  
The field value read.  

## See Also

#### Reference

[IDatabaseResult Interface](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)

[GetValue\<T\> Overload](idatabaseresult-getvalue-t-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

