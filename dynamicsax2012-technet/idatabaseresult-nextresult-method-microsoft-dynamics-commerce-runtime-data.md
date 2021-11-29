---
title: IDatabaseResult.NextResult Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: NextResult Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.NextResult
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabaseresult.nextresult(v=AX.60)
ms:contentKeyID: 65316551
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.NextResult
dev_langs:
- CSharp
- C++
- VB
---

# NextResult Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Moves to the next result set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function NextResult As Boolean
'Usage
Dim instance As IDatabaseResult
Dim returnValue As Boolean

returnValue = instance.NextResult()
```

``` csharp
bool NextResult()
```

``` c++
bool NextResult()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Whether new result set exists or not.  

## Remarks

No call to this method is require to read the initial result set.

## See Also

#### Reference

[IDatabaseResult Interface](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

