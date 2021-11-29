---
title: EmployeeDataManager.ValidateEmployeePassword Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ValidateEmployeePassword Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.ValidateEmployeePassword(System.Int64,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.employeedatamanager.validateemployeepassword(v=AX.60)
ms:contentKeyID: 65322848
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.ValidateEmployeePassword
dev_langs:
- CSharp
- C++
- VB
---

# ValidateEmployeePassword Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function ValidateEmployeePassword ( _
    channelId As Long, _
    staffId As String, _
    passwordHash As String, _
    logOnKeyHash As String, _
    logOnType As LogOnType, _
    columnSet As ColumnSet _
) As Boolean
'Usage
Dim instance As EmployeeDataManager
Dim channelId As Long
Dim staffId As String
Dim passwordHash As String
Dim logOnKeyHash As String
Dim logOnType As LogOnType
Dim columnSet As ColumnSet
Dim returnValue As Boolean

returnValue = instance.ValidateEmployeePassword(channelId, _
    staffId, passwordHash, logOnKeyHash, _
    logOnType, columnSet)
```

``` csharp
public bool ValidateEmployeePassword(
    long channelId,
    string staffId,
    string passwordHash,
    string logOnKeyHash,
    LogOnType logOnType,
    ColumnSet columnSet
)
```

``` c++
public:
bool ValidateEmployeePassword(
    long long channelId, 
    String^ staffId, 
    String^ passwordHash, 
    String^ logOnKeyHash, 
    LogOnType logOnType, 
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

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[EmployeeDataManager Class](employeedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

