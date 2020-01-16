---
title: EmployeeDataManager.GetAllStoreEmployees Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAllStoreEmployees Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetAllStoreEmployees(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.employeedatamanager.getallstoreemployees(v=AX.60)
ms:contentKeyID: 65317242
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetAllStoreEmployees
dev_langs:
- CSharp
- C++
- VB
---

# GetAllStoreEmployees Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetAllStoreEmployees ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of Employee)
'Usage
Dim instance As EmployeeDataManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of Employee)

returnValue = instance.GetAllStoreEmployees(settings)
```

``` csharp
public ReadOnlyCollection<Employee> GetAllStoreEmployees(
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<Employee^>^ GetAllStoreEmployees(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[EmployeeDataManager Class](employeedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

