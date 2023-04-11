---
title: EmployeeDataManager.GetEmployeeBreakCategoriesByJob Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetEmployeeBreakCategoriesByJob Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetEmployeeBreakCategoriesByJob(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.employeedatamanager.getemployeebreakcategoriesbyjob(v=AX.60)
ms:contentKeyID: 62204734
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetEmployeeBreakCategoriesByJob
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeBreakCategoriesByJob Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the employee break categories by job identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetEmployeeBreakCategoriesByJob ( _
    jobId As String _
) As ReadOnlyCollection(Of EmployeeActivity)
'Usage
Dim instance As EmployeeDataManager
Dim jobId As String
Dim returnValue As ReadOnlyCollection(Of EmployeeActivity)

returnValue = instance.GetEmployeeBreakCategoriesByJob(jobId)
```

``` csharp
public ReadOnlyCollection<EmployeeActivity> GetEmployeeBreakCategoriesByJob(
    string jobId
)
```

``` c++
public:
ReadOnlyCollection<EmployeeActivity^>^ GetEmployeeBreakCategoriesByJob(
    String^ jobId
)
```

#### Parameters

  - jobId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[EmployeeActivity](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the employee activity.  

## See Also

#### Reference

[EmployeeDataManager Class](employeedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

