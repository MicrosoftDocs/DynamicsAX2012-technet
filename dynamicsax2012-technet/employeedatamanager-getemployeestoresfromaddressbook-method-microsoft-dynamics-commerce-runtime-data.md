---
title: EmployeeDataManager.GetEmployeeStoresFromAddressBook Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetEmployeeStoresFromAddressBook Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetEmployeeStoresFromAddressBook(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.employeedatamanager.getemployeestoresfromaddressbook(v=AX.60)
ms:contentKeyID: 65321084
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetEmployeeStoresFromAddressBook
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeStoresFromAddressBook Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetEmployeeStoresFromAddressBook ( _
    staffId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of OrgUnit)
'Usage
Dim instance As EmployeeDataManager
Dim staffId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of OrgUnit)

returnValue = instance.GetEmployeeStoresFromAddressBook(staffId, _
    settings)
```

``` csharp
public ReadOnlyCollection<OrgUnit> GetEmployeeStoresFromAddressBook(
    string staffId,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<OrgUnit^>^ GetEmployeeStoresFromAddressBook(
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

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[EmployeeDataManager Class](employeedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

