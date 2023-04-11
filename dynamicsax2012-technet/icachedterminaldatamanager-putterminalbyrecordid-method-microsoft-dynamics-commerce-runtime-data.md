---
title: ICachedTerminalDataManager.PutTerminalByRecordId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutTerminalByRecordId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedTerminalDataManager.PutTerminalByRecordId(System.Int64,Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.Terminal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedterminaldatamanager.putterminalbyrecordid(v=AX.60)
ms:contentKeyID: 62204794
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedTerminalDataManager.PutTerminalByRecordId
dev_langs:
- CSharp
- C++
- VB
---

# PutTerminalByRecordId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Puts terminal entity into cache by record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutTerminalByRecordId ( _
    terminalRecordId As Long, _
    columns As ColumnSet, _
    result As Terminal _
)
'Usage
Dim instance As ICachedTerminalDataManager
Dim terminalRecordId As Long
Dim columns As ColumnSet
Dim result As Terminal

instance.PutTerminalByRecordId(terminalRecordId, _
    columns, result)
```

``` csharp
void PutTerminalByRecordId(
    long terminalRecordId,
    ColumnSet columns,
    Terminal result
)
```

``` c++
void PutTerminalByRecordId(
    long long terminalRecordId, 
    ColumnSet^ columns, 
    Terminal^ result
)
```

#### Parameters

  - terminalRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Terminal](terminal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedTerminalDataManager Interface](icachedterminaldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

