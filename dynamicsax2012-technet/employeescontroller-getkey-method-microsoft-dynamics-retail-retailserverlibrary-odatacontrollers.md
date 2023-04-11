---
title: EmployeesController.GetKey Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetKey Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.EmployeesController.GetKey(Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.employeescontroller.getkey(v=AX.60)
ms:contentKeyID: 62203404
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.EmployeesController.GetKey
dev_langs:
- CSharp
- C++
- VB
---

# GetKey Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Staff identifier.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetKey ( _
    entity As Employee _
) As String
'Usage
Dim entity As Employee
Dim returnValue As String

returnValue = Me.GetKey(entity)
```

``` csharp
protected override string GetKey(
    Employee entity
)
```

``` c++
protected:
virtual String^ GetKey(
    Employee^ entity
) override
```

#### Parameters

  - entity  
    Type: Employee  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) key.  

## See Also

#### Reference

[EmployeesController Class](employeescontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

