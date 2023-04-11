---
title: NonBindableActionController.GetDiscountCodes Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetDiscountCodes Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetDiscountCodes(System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getdiscountcodes(v=AX.60)
ms:contentKeyID: 62202529
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetDiscountCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountCodes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets collection of discount codes.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Overridable Function GetDiscountCodes ( _
    queryOptions As ODataQueryOptions(Of DiscountCode) _
) As IEnumerable(Of DiscountCode)
'Usage
Dim instance As NonBindableActionController
Dim queryOptions As ODataQueryOptions(Of DiscountCode)
Dim returnValue As IEnumerable(Of DiscountCode)

returnValue = instance.GetDiscountCodes(queryOptions)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public virtual IEnumerable<DiscountCode> GetDiscountCodes(
    ODataQueryOptions<DiscountCode> queryOptions
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
virtual IEnumerable<DiscountCode^>^ GetDiscountCodes(
    ODataQueryOptions<DiscountCode^>^ queryOptions
)
```

#### Parameters

  - queryOptions  
    Type: ODataQueryOptions\<DiscountCode\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<DiscountCode\>  
A collection of discount codes.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

