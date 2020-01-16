---
title: EmployeeManager.GetLatestEmployeeActivity Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetLatestEmployeeActivity Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.EmployeeManager.GetLatestEmployeeActivity(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.employeemanager.getlatestemployeeactivity(v=AX.60)
ms:contentKeyID: 65320095
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.EmployeeManager.GetLatestEmployeeActivity
dev_langs:
- CSharp
- C++
- VB
---

# GetLatestEmployeeActivity Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetLatestEmployeeActivity ( _
    querySettings As QueryResultSettings _
) As EmployeeActivity
'Usage
Dim instance As EmployeeManager
Dim querySettings As QueryResultSettings
Dim returnValue As EmployeeActivity

returnValue = instance.GetLatestEmployeeActivity(querySettings)
```

``` csharp
public EmployeeActivity GetLatestEmployeeActivity(
    QueryResultSettings querySettings
)
```

``` c++
public:
EmployeeActivity^ GetLatestEmployeeActivity(
    QueryResultSettings^ querySettings
)
```

#### Parameters

  - querySettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[EmployeeManager Class](employeemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

