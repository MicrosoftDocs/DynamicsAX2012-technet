---
title: EmployeeManager.GetManagerActivityView Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetManagerActivityView Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.EmployeeManager.GetManagerActivityView(Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivitySearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.employeemanager.getmanageractivityview(v=AX.60)
ms:contentKeyID: 65321299
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.EmployeeManager.GetManagerActivityView
dev_langs:
- CSharp
- C++
- VB
---

# GetManagerActivityView Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetManagerActivityView ( _
    queryCriteria As EmployeeActivitySearchCriteria, _
    querySettings As QueryResultSettings _
) As PagedResult(Of EmployeeActivity)
'Usage
Dim instance As EmployeeManager
Dim queryCriteria As EmployeeActivitySearchCriteria
Dim querySettings As QueryResultSettings
Dim returnValue As PagedResult(Of EmployeeActivity)

returnValue = instance.GetManagerActivityView(queryCriteria, _
    querySettings)
```

``` csharp
public PagedResult<EmployeeActivity> GetManagerActivityView(
    EmployeeActivitySearchCriteria queryCriteria,
    QueryResultSettings querySettings
)
```

``` c++
public:
PagedResult<EmployeeActivity^>^ GetManagerActivityView(
    EmployeeActivitySearchCriteria^ queryCriteria, 
    QueryResultSettings^ querySettings
)
```

#### Parameters

  - queryCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivitySearchCriteria](employeeactivitysearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - querySettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[EmployeeActivity](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[EmployeeManager Class](employeemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

