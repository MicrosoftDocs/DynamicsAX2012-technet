---
title: EmployeeManager.GetAllStoreEmployees Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetAllStoreEmployees Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.EmployeeManager.GetAllStoreEmployees(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.employeemanager.getallstoreemployees(v=AX.60)
ms:contentKeyID: 65316754
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.EmployeeManager.GetAllStoreEmployees
dev_langs:
- CSharp
- C++
- VB
---

# GetAllStoreEmployees Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetAllStoreEmployees ( _
    settings As QueryResultSettings _
) As PagedResult(Of Employee)
'Usage
Dim instance As EmployeeManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of Employee)

returnValue = instance.GetAllStoreEmployees(settings)
```

``` csharp
public PagedResult<Employee> GetAllStoreEmployees(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<Employee^>^ GetAllStoreEmployees(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[EmployeeManager Class](employeemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

