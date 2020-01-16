---
title: IDatabaseResult.Read Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Read Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.Read
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabaseresult.read(v=AX.60)
ms:contentKeyID: 65320521
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.Read
dev_langs:
- CSharp
- C++
- VB
---

# Read Method

Reads the next result set row.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function Read As Boolean
'Usage
Dim instance As IDatabaseResult
Dim returnValue As Boolean

returnValue = instance.Read()
```

``` csharp
bool Read()
```

``` c++
bool Read()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Whether new result set row exists or not.  

## Remarks

To read the first row in the result set, as well as all subsequent rows, a call to this method is necessary for each row to be read.

## See Also

#### Reference

[IDatabaseResult Interface](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

