---
title: EmployeeManager.GetEmployeeStores Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetEmployeeStores Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.EmployeeManager.GetEmployeeStores(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.employeemanager.getemployeestores(v=AX.60)
ms:contentKeyID: 65318387
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.EmployeeManager.GetEmployeeStores
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeStores Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetEmployeeStores ( _
    querySettings As QueryResultSettings _
) As PagedResult(Of OrgUnit)
'Usage
Dim instance As EmployeeManager
Dim querySettings As QueryResultSettings
Dim returnValue As PagedResult(Of OrgUnit)

returnValue = instance.GetEmployeeStores(querySettings)
```

``` csharp
public PagedResult<OrgUnit> GetEmployeeStores(
    QueryResultSettings querySettings
)
```

``` c++
public:
PagedResult<OrgUnit^>^ GetEmployeeStores(
    QueryResultSettings^ querySettings
)
```

#### Parameters

  - querySettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[EmployeeManager Class](employeemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

