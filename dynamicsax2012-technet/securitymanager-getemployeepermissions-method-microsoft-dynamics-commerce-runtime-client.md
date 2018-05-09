---
title: SecurityManager.GetEmployeePermissions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetEmployeePermissions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.GetEmployeePermissions(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.securitymanager.getemployeepermissions(v=AX.60)
ms:contentKeyID: 62208550
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.GetEmployeePermissions
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeePermissions Method

Gets Employee permission settings.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetEmployeePermissions ( _
    staffId As String _
) As Employee
'Usage
Dim instance As SecurityManager
Dim staffId As String
Dim returnValue As Employee

returnValue = instance.GetEmployeePermissions(staffId)
```

``` csharp
public Employee GetEmployeePermissions(
    string staffId
)
```

``` c++
public:
Employee^ GetEmployeePermissions(
    String^ staffId
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
EmployeePermissions object.  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

