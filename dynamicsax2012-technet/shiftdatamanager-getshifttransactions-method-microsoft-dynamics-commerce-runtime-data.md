---
title: ShiftDataManager.GetShiftTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetShiftTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.GetShiftTransactions(System.String,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.shiftdatamanager.getshifttransactions(v=AX.60)
ms:contentKeyID: 62213838
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.GetShiftTransactions
dev_langs:
- CSharp
- C++
- VB
---

# GetShiftTransactions Method

Get shift transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetShiftTransactions ( _
    terminalId As String, _
    shiftId As Long _
) As Shift
'Usage
Dim instance As ShiftDataManager
Dim terminalId As String
Dim shiftId As Long
Dim returnValue As Shift

returnValue = instance.GetShiftTransactions(terminalId, _
    shiftId)
```

``` csharp
public Shift GetShiftTransactions(
    string terminalId,
    long shiftId
)
```

``` c++
public:
Shift^ GetShiftTransactions(
    String^ terminalId, 
    long long shiftId
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The Shift collection object.  

## See Also

#### Reference

[ShiftDataManager Class](shiftdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

