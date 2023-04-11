---
title: EmployeeDataManager.EmployeeLogOnStore Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: EmployeeLogOnStore Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.EmployeeLogOnStore(System.Int64,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType,System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.employeedatamanager.employeelogonstore(v=AX.60)
ms:contentKeyID: 62209525
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.EmployeeLogOnStore
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeLogOnStore Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Logs On the user in the local Store DB.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function EmployeeLogOnStore ( _
    channelId As Long, _
    staffId As String, _
    passwordHash As String, _
    logOnKeyHash As String, _
    logOnType As LogOnType, _
    extraData As String, _
    columnSet As ColumnSet _
) As Employee
'Usage
Dim instance As EmployeeDataManager
Dim channelId As Long
Dim staffId As String
Dim passwordHash As String
Dim logOnKeyHash As String
Dim logOnType As LogOnType
Dim extraData As String
Dim columnSet As ColumnSet
Dim returnValue As Employee

returnValue = instance.EmployeeLogOnStore(channelId, _
    staffId, passwordHash, logOnKeyHash, _
    logOnType, extraData, columnSet)
```

``` csharp
public Employee EmployeeLogOnStore(
    long channelId,
    string staffId,
    string passwordHash,
    string logOnKeyHash,
    LogOnType logOnType,
    string extraData,
    ColumnSet columnSet
)
```

``` c++
public:
Employee^ EmployeeLogOnStore(
    long long channelId, 
    String^ staffId, 
    String^ passwordHash, 
    String^ logOnKeyHash, 
    LogOnType logOnType, 
    String^ extraData, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - passwordHash  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logOnKeyHash  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logOnType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType](logontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - extraData  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Employee object.  

## See Also

#### Reference

[EmployeeDataManager Class](employeedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

