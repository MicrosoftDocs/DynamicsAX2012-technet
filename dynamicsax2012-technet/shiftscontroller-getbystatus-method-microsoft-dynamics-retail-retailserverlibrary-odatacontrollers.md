---
title: ShiftsController.GetByStatus Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetByStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController.GetByStatus(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.shiftscontroller.getbystatus(v=AX.60)
ms:contentKeyID: 62203063
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController.GetByStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetByStatus Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the shifts by status.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Overridable Function GetByStatus ( _
    parameters As ODataActionParameters _
) As IEnumerable(Of Shift)
'Usage
Dim instance As ShiftsController
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of Shift)

returnValue = instance.GetByStatus(parameters)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public virtual IEnumerable<Shift> GetByStatus(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public:
virtual IEnumerable<Shift^>^ GetByStatus(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<Shift\>  
The collection of shift objects.  

## Remarks

We do not have an AX operation mapping to this API, so permission checks are done at workflow level.

## See Also

#### Reference

[ShiftsController Class](shiftscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

