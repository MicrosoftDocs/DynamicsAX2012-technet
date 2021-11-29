---
title: EmployeeDataManager.GetEmployeeBreakCategoriesByActivity Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetEmployeeBreakCategoriesByActivity Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetEmployeeBreakCategoriesByActivity(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.employeedatamanager.getemployeebreakcategoriesbyactivity(v=AX.60)
ms:contentKeyID: 62213941
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetEmployeeBreakCategoriesByActivity
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeBreakCategoriesByActivity Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the employee break categories by activity names.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetEmployeeBreakCategoriesByActivity ( _
    activityNames As IEnumerable(Of String) _
) As ReadOnlyCollection(Of EmployeeActivity)
'Usage
Dim instance As EmployeeDataManager
Dim activityNames As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of EmployeeActivity)

returnValue = instance.GetEmployeeBreakCategoriesByActivity(activityNames)
```

``` csharp
public ReadOnlyCollection<EmployeeActivity> GetEmployeeBreakCategoriesByActivity(
    IEnumerable<string> activityNames
)
```

``` c++
public:
ReadOnlyCollection<EmployeeActivity^>^ GetEmployeeBreakCategoriesByActivity(
    IEnumerable<String^>^ activityNames
)
```

#### Parameters

  - activityNames  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[EmployeeActivity](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the employee break activities.  

## See Also

#### Reference

[EmployeeDataManager Class](employeedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

