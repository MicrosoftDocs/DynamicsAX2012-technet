---
title: NonBindableActionController.GetStateProvinces Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetStateProvinces Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetStateProvinces(System.Web.Http.OData.ODataActionParameters,System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.StateProvinceInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getstateprovinces(v=AX.60)
ms:contentKeyID: 62201959
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetStateProvinces
dev_langs:
- CSharp
- C++
- VB
---

# GetStateProvinces Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get all the states or provinces filtered by country region.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Overridable Function GetStateProvinces ( _
    parameters As ODataActionParameters, _
    queryOptions As ODataQueryOptions(Of StateProvinceInfo) _
) As IEnumerable(Of StateProvinceInfo)
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim queryOptions As ODataQueryOptions(Of StateProvinceInfo)
Dim returnValue As IEnumerable(Of StateProvinceInfo)

returnValue = instance.GetStateProvinces(parameters, _
    queryOptions)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public virtual IEnumerable<StateProvinceInfo> GetStateProvinces(
    ODataActionParameters parameters,
    ODataQueryOptions<StateProvinceInfo> queryOptions
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public:
virtual IEnumerable<StateProvinceInfo^>^ GetStateProvinces(
    ODataActionParameters^ parameters, 
    ODataQueryOptions<StateProvinceInfo^>^ queryOptions
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

<!-- end list -->

  - queryOptions  
    Type: ODataQueryOptions\<StateProvinceInfo\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<StateProvinceInfo\>  
A collection of cities.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

