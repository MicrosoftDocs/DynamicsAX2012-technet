---
title: ShiftDataManager.GetShiftTenderedAmount Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetShiftTenderedAmount Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.GetShiftTenderedAmount(System.String,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shiftdatamanager.getshifttenderedamount(v=AX.60)
ms:contentKeyID: 62214371
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.GetShiftTenderedAmount
dev_langs:
- CSharp
- C++
- VB
---

# GetShiftTenderedAmount Method

Get shift transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetShiftTenderedAmount ( _
    terminalId As String, _
    shiftId As Long _
) As ReadOnlyCollection(Of ShiftTenderLine)
'Usage
Dim instance As ShiftDataManager
Dim terminalId As String
Dim shiftId As Long
Dim returnValue As ReadOnlyCollection(Of ShiftTenderLine)

returnValue = instance.GetShiftTenderedAmount(terminalId, _
    shiftId)
```

``` csharp
public ReadOnlyCollection<ShiftTenderLine> GetShiftTenderedAmount(
    string terminalId,
    long shiftId
)
```

``` c++
public:
ReadOnlyCollection<ShiftTenderLine^>^ GetShiftTenderedAmount(
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

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ShiftTenderLine](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The Shift tender line collection object.  

## See Also

#### Reference

[ShiftDataManager Class](shiftdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

