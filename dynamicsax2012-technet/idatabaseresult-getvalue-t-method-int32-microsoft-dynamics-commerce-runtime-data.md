---
title: IDatabaseResult.GetValue(T) Method (Int32) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetValue(T) Method (Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.GetValue``1(System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/Dn968911(v=AX.60)
ms:contentKeyID: 65322275
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetValue(T) Method (Int32)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the value for a specific field in the current result set row.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetValue(Of T) ( _
    index As Integer _
) As T
'Usage
Dim instance As IDatabaseResult
Dim index As Integer
Dim returnValue As T

returnValue = instance.GetValue(index)
```

``` csharp
T GetValue<T>(
    int index
)
```

``` c++
generic<typename T>
T GetValue(
    int index
)
```

#### Type Parameters

  - T

#### Parameters

  - index  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: T  
The field value read.  

## See Also

#### Reference

[IDatabaseResult Interface](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)

[GetValue\<T\> Overload](idatabaseresult-getvalue-t-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

