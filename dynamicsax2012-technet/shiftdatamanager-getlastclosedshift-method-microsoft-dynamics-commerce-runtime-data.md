---
title: ShiftDataManager.GetLastClosedShift Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetLastClosedShift Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.GetLastClosedShift(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shiftdatamanager.getlastclosedshift(v=AX.60)
ms:contentKeyID: 62213907
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.GetLastClosedShift
dev_langs:
- CSharp
- C++
- VB
---

# GetLastClosedShift Method

Loads the last closed Shift object from database for the specific terminal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetLastClosedShift ( _
    terminalId As String _
) As Shift
'Usage
Dim instance As ShiftDataManager
Dim terminalId As String
Dim returnValue As Shift

returnValue = instance.GetLastClosedShift(terminalId)
```

``` csharp
public Shift GetLastClosedShift(
    string terminalId
)
```

``` c++
public:
Shift^ GetLastClosedShift(
    String^ terminalId
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The last closed Shift object.  

## See Also

#### Reference

[ShiftDataManager Class](shiftdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

