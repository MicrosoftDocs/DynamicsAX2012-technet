---
title: TerminalDatabaseAccessor.GetTerminalByRecordId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTerminalByRecordId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TerminalDatabaseAccessor.GetTerminalByRecordId(System.Int64,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.terminaldatabaseaccessor.getterminalbyrecordid(v=AX.60)
ms:contentKeyID: 62211164
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TerminalDatabaseAccessor.GetTerminalByRecordId
dev_langs:
- CSharp
- C++
- VB
---

# GetTerminalByRecordId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets terminal entity by record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTerminalByRecordId ( _
    terminalRecordId As Long, _
    columns As ColumnSet _
) As Terminal
'Usage
Dim instance As TerminalDatabaseAccessor
Dim terminalRecordId As Long
Dim columns As ColumnSet
Dim returnValue As Terminal

returnValue = instance.GetTerminalByRecordId(terminalRecordId, _
    columns)
```

``` csharp
public Terminal GetTerminalByRecordId(
    long terminalRecordId,
    ColumnSet columns
)
```

``` c++
public:
virtual Terminal^ GetTerminalByRecordId(
    long long terminalRecordId, 
    ColumnSet^ columns
) sealed
```

#### Parameters

  - terminalRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Terminal](terminal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The terminal object.  

#### Implements

[ITerminalDataManager.GetTerminalByRecordId(Int64, ColumnSet)](iterminaldatamanager-getterminalbyrecordid-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[TerminalDatabaseAccessor Class](terminaldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

