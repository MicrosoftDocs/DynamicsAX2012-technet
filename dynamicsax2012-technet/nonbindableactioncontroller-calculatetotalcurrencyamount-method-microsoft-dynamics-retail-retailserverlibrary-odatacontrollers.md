---
title: NonBindableActionController.CalculateTotalCurrencyAmount Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: CalculateTotalCurrencyAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.CalculateTotalCurrencyAmount(System.Web.Http.OData.ODataActionParameters,System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.calculatetotalcurrencyamount(v=AX.60)
ms:contentKeyID: 62203145
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.CalculateTotalCurrencyAmount
dev_langs:
- CSharp
- C++
- VB
---

# CalculateTotalCurrencyAmount Method

Calculates the total currency amount.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Overridable Function CalculateTotalCurrencyAmount ( _
    parameters As ODataActionParameters, _
    queryOptions As ODataQueryOptions(Of CurrencyAmount) _
) As CurrencyAmount
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim queryOptions As ODataQueryOptions(Of CurrencyAmount)
Dim returnValue As CurrencyAmount

returnValue = instance.CalculateTotalCurrencyAmount(parameters, _
    queryOptions)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public virtual CurrencyAmount CalculateTotalCurrencyAmount(
    ODataActionParameters parameters,
    ODataQueryOptions<CurrencyAmount> queryOptions
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
virtual CurrencyAmount^ CalculateTotalCurrencyAmount(
    ODataActionParameters^ parameters, 
    ODataQueryOptions<CurrencyAmount^>^ queryOptions
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

<!-- end list -->

  - queryOptions  
    Type: ODataQueryOptions\<CurrencyAmount\>  

#### Return Value

Type: CurrencyAmount  
The CurrencyAmount.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

