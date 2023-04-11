---
title: IDatabaseResult.GetFieldIndex Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetFieldIndex Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.GetFieldIndex(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabaseresult.getfieldindex(v=AX.60)
ms:contentKeyID: 65318261
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.GetFieldIndex
dev_langs:
- CSharp
- C++
- VB
---

# GetFieldIndex Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the index of the field by a specific name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetFieldIndex ( _
    fieldName As String _
) As Integer
'Usage
Dim instance As IDatabaseResult
Dim fieldName As String
Dim returnValue As Integer

returnValue = instance.GetFieldIndex(fieldName)
```

``` csharp
int GetFieldIndex(
    string fieldName
)
```

``` c++
int GetFieldIndex(
    String^ fieldName
)
```

#### Parameters

  - fieldName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The index of the field.  

## See Also

#### Reference

[IDatabaseResult Interface](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

