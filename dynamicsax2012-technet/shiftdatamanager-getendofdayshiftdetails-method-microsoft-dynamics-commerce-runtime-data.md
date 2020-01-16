---
title: ShiftDataManager.GetEndOfDayshiftDetails Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetEndOfDayshiftDetails Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.GetEndOfDayshiftDetails(System.String,System.Int64,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shiftdatamanager.getendofdayshiftdetails(v=AX.60)
ms:contentKeyID: 62209974
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.GetEndOfDayshiftDetails
dev_langs:
- CSharp
- C++
- VB
---

# GetEndOfDayshiftDetails Method

Loads the shift sales data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetEndOfDayshiftDetails ( _
    terminalId As String, _
    shiftId As Long, _
    isTaxInclusive As Boolean _
) As Shift
'Usage
Dim instance As ShiftDataManager
Dim terminalId As String
Dim shiftId As Long
Dim isTaxInclusive As Boolean
Dim returnValue As Shift

returnValue = instance.GetEndOfDayshiftDetails(terminalId, _
    shiftId, isTaxInclusive)
```

``` csharp
public Shift GetEndOfDayshiftDetails(
    string terminalId,
    long shiftId,
    bool isTaxInclusive
)
```

``` c++
public:
Shift^ GetEndOfDayshiftDetails(
    String^ terminalId, 
    long long shiftId, 
    bool isTaxInclusive
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - isTaxInclusive  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The Shift object.  

## See Also

#### Reference

[ShiftDataManager Class](shiftdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

