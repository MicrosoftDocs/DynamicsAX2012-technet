---
title: NonBindableActionController.GetCustomerBalance Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetCustomerBalance Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetCustomerBalance(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getcustomerbalance(v=AX.60)
ms:contentKeyID: 62202431
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetCustomerBalance
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerBalance Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer balance.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Overridable Function GetCustomerBalance ( _
    parameters As ODataActionParameters _
) As CustomerBalances
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim returnValue As CustomerBalances

returnValue = instance.GetCustomerBalance(parameters)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public virtual CustomerBalances GetCustomerBalance(
    ODataActionParameters parameters
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
virtual CustomerBalances^ GetCustomerBalance(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: CustomerBalances  
An object of type CustomerBalances.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

