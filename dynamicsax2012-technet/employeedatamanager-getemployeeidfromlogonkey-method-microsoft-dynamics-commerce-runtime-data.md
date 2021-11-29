---
title: EmployeeDataManager.GetEmployeeIdFromLogOnKey Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetEmployeeIdFromLogOnKey Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetEmployeeIdFromLogOnKey(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.employeedatamanager.getemployeeidfromlogonkey(v=AX.60)
ms:contentKeyID: 62211069
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetEmployeeIdFromLogOnKey
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeIdFromLogOnKey Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the employee identifier from the specified logon key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetEmployeeIdFromLogOnKey ( _
    logOnKeyHash As String, _
    logOnType As LogOnType _
) As String
'Usage
Dim instance As EmployeeDataManager
Dim logOnKeyHash As String
Dim logOnType As LogOnType
Dim returnValue As String

returnValue = instance.GetEmployeeIdFromLogOnKey(logOnKeyHash, _
    logOnType)
```

``` csharp
public string GetEmployeeIdFromLogOnKey(
    string logOnKeyHash,
    LogOnType logOnType
)
```

``` c++
public:
String^ GetEmployeeIdFromLogOnKey(
    String^ logOnKeyHash, 
    LogOnType logOnType
)
```

#### Parameters

  - logOnKeyHash  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logOnType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType](logontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The staff identifier.  

## See Also

#### Reference

[EmployeeDataManager Class](employeedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

