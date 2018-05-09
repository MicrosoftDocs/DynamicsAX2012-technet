---
title: ShiftDataManager.GetShiftRequiredAmountsPerTender Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetShiftRequiredAmountsPerTender Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.GetShiftRequiredAmountsPerTender(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.shiftdatamanager.getshiftrequiredamountspertender(v=AX.60)
ms:contentKeyID: 65319580
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.GetShiftRequiredAmountsPerTender
dev_langs:
- CSharp
- C++
- VB
---

# GetShiftRequiredAmountsPerTender Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetShiftRequiredAmountsPerTender ( _
    terminalId As String, _
    shiftId As String _
) As ReadOnlyCollection(Of ShiftTenderLine)
'Usage
Dim instance As ShiftDataManager
Dim terminalId As String
Dim shiftId As String
Dim returnValue As ReadOnlyCollection(Of ShiftTenderLine)

returnValue = instance.GetShiftRequiredAmountsPerTender(terminalId, _
    shiftId)
```

``` csharp
public ReadOnlyCollection<ShiftTenderLine> GetShiftRequiredAmountsPerTender(
    string terminalId,
    string shiftId
)
```

``` c++
public:
ReadOnlyCollection<ShiftTenderLine^>^ GetShiftRequiredAmountsPerTender(
    String^ terminalId, 
    String^ shiftId
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ShiftTenderLine](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ShiftDataManager Class](shiftdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

