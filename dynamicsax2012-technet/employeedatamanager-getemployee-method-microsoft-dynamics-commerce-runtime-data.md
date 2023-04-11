---
title: EmployeeDataManager.GetEmployee Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetEmployee Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetEmployee(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.employeedatamanager.getemployee(v=AX.60)
ms:contentKeyID: 65318833
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetEmployee
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployee Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetEmployee ( _
    staffId As String, _
    settings As QueryResultSettings _
) As Employee
'Usage
Dim instance As EmployeeDataManager
Dim staffId As String
Dim settings As QueryResultSettings
Dim returnValue As Employee

returnValue = instance.GetEmployee(staffId, _
    settings)
```

``` csharp
public Employee GetEmployee(
    string staffId,
    QueryResultSettings settings
)
```

``` c++
public:
Employee^ GetEmployee(
    String^ staffId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[EmployeeDataManager Class](employeedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

