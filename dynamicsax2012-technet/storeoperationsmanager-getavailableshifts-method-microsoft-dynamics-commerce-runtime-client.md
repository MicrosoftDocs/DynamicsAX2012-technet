---
title: StoreOperationsManager.GetAvailableShifts Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetAvailableShifts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.GetAvailableShifts(Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftStatus,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.storeoperationsmanager.getavailableshifts(v=AX.60)
ms:contentKeyID: 65320281
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.GetAvailableShifts
dev_langs:
- CSharp
- C++
- VB
---

# GetAvailableShifts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetAvailableShifts ( _
    status As ShiftStatus, _
    settings As QueryResultSettings _
) As PagedResult(Of Shift)
'Usage
Dim instance As StoreOperationsManager
Dim status As ShiftStatus
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of Shift)

returnValue = instance.GetAvailableShifts(status, _
    settings)
```

``` csharp
public PagedResult<Shift> GetAvailableShifts(
    ShiftStatus status,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<Shift^>^ GetAvailableShifts(
    ShiftStatus status, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - status  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftStatus](shiftstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[StoreOperationsManager Class](storeoperationsmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

