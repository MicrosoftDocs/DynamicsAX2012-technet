---
title: NumberSequenceSeedDataManager.GetNextNumberSequenceValue Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetNextNumberSequenceValue Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.NumberSequenceSeedDataManager.GetNextNumberSequenceValue(Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.numbersequenceseeddatamanager.getnextnumbersequencevalue(v=AX.60)
ms:contentKeyID: 62209255
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.NumberSequenceSeedDataManager.GetNextNumberSequenceValue
dev_langs:
- CSharp
- C++
- VB
---

# GetNextNumberSequenceValue Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the next value of a number sequence. Creates the number sequence seed data if not exists.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetNextNumberSequenceValue ( _
    numberSequenceSeedType As NumberSequenceSeedType, _
    storeId As String, _
    terminalId As String _
) As Long
'Usage
Dim instance As NumberSequenceSeedDataManager
Dim numberSequenceSeedType As NumberSequenceSeedType
Dim storeId As String
Dim terminalId As String
Dim returnValue As Long

returnValue = instance.GetNextNumberSequenceValue(numberSequenceSeedType, _
    storeId, terminalId)
```

``` csharp
public long GetNextNumberSequenceValue(
    NumberSequenceSeedType numberSequenceSeedType,
    string storeId,
    string terminalId
)
```

``` c++
public:
long long GetNextNumberSequenceValue(
    NumberSequenceSeedType numberSequenceSeedType, 
    String^ storeId, 
    String^ terminalId
)
```

#### Parameters

  - numberSequenceSeedType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType](numbersequenceseedtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The next value.  

## See Also

#### Reference

[NumberSequenceSeedDataManager Class](numbersequenceseeddatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

