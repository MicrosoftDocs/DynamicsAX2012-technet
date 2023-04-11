---
title: EmployeeDataManager.GetOperationPermissions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetOperationPermissions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetOperationPermissions(Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.employeedatamanager.getoperationpermissions(v=AX.60)
ms:contentKeyID: 62214071
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetOperationPermissions
dev_langs:
- CSharp
- C++
- VB
---

# GetOperationPermissions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets Operation Permissions for the operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetOperationPermissions ( _
    operationId As RetailOperation, _
    columns As ColumnSet _
) As ReadOnlyCollection(Of OperationPermission)
'Usage
Dim instance As EmployeeDataManager
Dim operationId As RetailOperation
Dim columns As ColumnSet
Dim returnValue As ReadOnlyCollection(Of OperationPermission)

returnValue = instance.GetOperationPermissions(operationId, _
    columns)
```

``` csharp
public ReadOnlyCollection<OperationPermission> GetOperationPermissions(
    RetailOperation operationId,
    ColumnSet columns
)
```

``` c++
public:
ReadOnlyCollection<OperationPermission^>^ GetOperationPermissions(
    RetailOperation operationId, 
    ColumnSet^ columns
)
```

#### Parameters

  - operationId  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OperationPermission](operationpermission-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of OperationPermission object.  

## See Also

#### Reference

[EmployeeDataManager Class](employeedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

