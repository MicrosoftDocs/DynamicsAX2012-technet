---
title: EmployeesController.GetManagerActivityView Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetManagerActivityView Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.EmployeesController.GetManagerActivityView(System.Void,Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.employeescontroller.getmanageractivityview(v=AX.60)
ms:contentKeyID: 62203461
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.EmployeesController.GetManagerActivityView
dev_langs:
- CSharp
- C++
- VB
---

# GetManagerActivityView Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.TimeRegistration)> _
Public Overridable Function GetManagerActivityView ( _
    parameters As Void, _
    queryOptions As EmployeeActivity _
) As IReadOnlyCollection
'Usage
Dim instance As EmployeesController
Dim parameters As Void
Dim queryOptions As EmployeeActivity
Dim returnValue As IReadOnlyCollection

returnValue = instance.GetManagerActivityView(parameters, _
    queryOptions)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.TimeRegistration)]
public virtual IReadOnlyCollection GetManagerActivityView(
    void parameters,
    EmployeeActivity queryOptions
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::TimeRegistration)]
public:
virtual IReadOnlyCollection^ GetManagerActivityView(
    void parameters, 
    EmployeeActivity^ queryOptions
)
```

#### Parameters

  - parameters  
    Type: [System.Void](https://technet.microsoft.com/library/skf099af\(v=ax.60\))  

<!-- end list -->

  - queryOptions  
    Type: EmployeeActivity  

#### Return Value

Type: IReadOnlyCollection  
Returns IReadOnlyCollection.  

## See Also

#### Reference

[EmployeesController Class](employeescontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

