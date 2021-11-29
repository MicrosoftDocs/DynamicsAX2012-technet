---
title: NonBindableActionController.GetDiscountCodesByOfferId Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetDiscountCodesByOfferId Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetDiscountCodesByOfferId(System.Web.Http.OData.ODataActionParameters,System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getdiscountcodesbyofferid(v=AX.60)
ms:contentKeyID: 62201741
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetDiscountCodesByOfferId
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountCodesByOfferId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets collection of discount codes filtered by offer identifier.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Overridable Function GetDiscountCodesByOfferId ( _
    parameters As ODataActionParameters, _
    queryOptions As ODataQueryOptions(Of DiscountCode) _
) As IEnumerable(Of DiscountCode)
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim queryOptions As ODataQueryOptions(Of DiscountCode)
Dim returnValue As IEnumerable(Of DiscountCode)

returnValue = instance.GetDiscountCodesByOfferId(parameters, _
    queryOptions)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public virtual IEnumerable<DiscountCode> GetDiscountCodesByOfferId(
    ODataActionParameters parameters,
    ODataQueryOptions<DiscountCode> queryOptions
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public:
virtual IEnumerable<DiscountCode^>^ GetDiscountCodesByOfferId(
    ODataActionParameters^ parameters, 
    ODataQueryOptions<DiscountCode^>^ queryOptions
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

<!-- end list -->

  - queryOptions  
    Type: ODataQueryOptions\<DiscountCode\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<DiscountCode\>  
A collection of discount codes.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

