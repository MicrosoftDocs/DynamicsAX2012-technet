---
title: NonBindableActionController.GetCreditMemoById Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetCreditMemoById Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetCreditMemoById(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getcreditmemobyid(v=AX.60)
ms:contentKeyID: 62203734
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetCreditMemoById
dev_langs:
- CSharp
- C++
- VB
---

# GetCreditMemoById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get credit memo by identifier.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Overridable Function GetCreditMemoById ( _
    parameters As ODataActionParameters _
) As CreditMemo
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim returnValue As CreditMemo

returnValue = instance.GetCreditMemoById(parameters)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public virtual CreditMemo GetCreditMemoById(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public:
virtual CreditMemo^ GetCreditMemoById(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: CreditMemo  
Credit memo instance.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

