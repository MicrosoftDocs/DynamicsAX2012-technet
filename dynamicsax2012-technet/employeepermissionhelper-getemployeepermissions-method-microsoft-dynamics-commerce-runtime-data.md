---
title: EmployeePermissionHelper.GetEmployeePermissions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetEmployeePermissions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.EmployeePermissionHelper.GetEmployeePermissions(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.employeepermissionhelper.getemployeepermissions(v=AX.60)
ms:contentKeyID: 65317442
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.EmployeePermissionHelper.GetEmployeePermissions
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeePermissions Method

Gets the employee permission details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetEmployeePermissions ( _
    context As RequestContext, _
    staffId As String _
) As EmployeePermissions
'Usage
Dim context As RequestContext
Dim staffId As String
Dim returnValue As EmployeePermissions

returnValue = EmployeePermissionHelper.GetEmployeePermissions(context, _
    staffId)
```

``` csharp
public static EmployeePermissions GetEmployeePermissions(
    RequestContext context,
    string staffId
)
```

``` c++
public:
static EmployeePermissions^ GetEmployeePermissions(
    RequestContext^ context, 
    String^ staffId
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The employee permission request.  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="userauthenticationexception-class-microsoft-dynamics-commerce-runtime.md">UserAuthenticationException</a></td>
<td><p>When the employee does not exists.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[EmployeePermissionHelper Class](employeepermissionhelper-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

