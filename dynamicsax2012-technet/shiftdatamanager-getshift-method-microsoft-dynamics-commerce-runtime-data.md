---
title: ShiftDataManager.GetShift Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetShift Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.GetShift(System.String,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shiftdatamanager.getshift(v=AX.60)
ms:contentKeyID: 62209568
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.GetShift
dev_langs:
- CSharp
- C++
- VB
---

# GetShift Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Loads a shift object from database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetShift ( _
    terminalId As String, _
    shiftId As Long _
) As Shift
'Usage
Dim instance As ShiftDataManager
Dim terminalId As String
Dim shiftId As Long
Dim returnValue As Shift

returnValue = instance.GetShift(terminalId, _
    shiftId)
```

``` csharp
public Shift GetShift(
    string terminalId,
    long shiftId
)
```

``` c++
public:
Shift^ GetShift(
    String^ terminalId, 
    long long shiftId
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The shift object.  

## See Also

#### Reference

[ShiftDataManager Class](shiftdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

