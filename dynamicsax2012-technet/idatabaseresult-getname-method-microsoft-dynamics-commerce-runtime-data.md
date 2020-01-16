---
title: IDatabaseResult.GetName Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetName Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.GetName(System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabaseresult.getname(v=AX.60)
ms:contentKeyID: 65318448
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.GetName
dev_langs:
- CSharp
- C++
- VB
---

# GetName Method

Gets the name of the field in a specific index.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetName ( _
    index As Integer _
) As String
'Usage
Dim instance As IDatabaseResult
Dim index As Integer
Dim returnValue As String

returnValue = instance.GetName(index)
```

``` csharp
string GetName(
    int index
)
```

``` c++
String^ GetName(
    int index
)
```

#### Parameters

  - index  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The name of the field.  

## See Also

#### Reference

[IDatabaseResult Interface](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

