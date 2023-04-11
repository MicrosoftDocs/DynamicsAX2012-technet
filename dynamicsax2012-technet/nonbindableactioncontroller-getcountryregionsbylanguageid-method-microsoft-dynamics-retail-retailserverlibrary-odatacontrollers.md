---
title: NonBindableActionController.GetCountryRegionsByLanguageId Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetCountryRegionsByLanguageId Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetCountryRegionsByLanguageId(System.Web.Http.OData.ODataActionParameters,System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getcountryregionsbylanguageid(v=AX.60)
ms:contentKeyID: 62203215
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetCountryRegionsByLanguageId
dev_langs:
- CSharp
- C++
- VB
---

# GetCountryRegionsByLanguageId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get all the countries/regions filter by Languauge ID.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Overridable Function GetCountryRegionsByLanguageId ( _
    parameters As ODataActionParameters, _
    queryOptions As ODataQueryOptions(Of CountryRegionInfo) _
) As IEnumerable(Of CountryRegionInfo)
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim queryOptions As ODataQueryOptions(Of CountryRegionInfo)
Dim returnValue As IEnumerable(Of CountryRegionInfo)

returnValue = instance.GetCountryRegionsByLanguageId(parameters, _
    queryOptions)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public virtual IEnumerable<CountryRegionInfo> GetCountryRegionsByLanguageId(
    ODataActionParameters parameters,
    ODataQueryOptions<CountryRegionInfo> queryOptions
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
virtual IEnumerable<CountryRegionInfo^>^ GetCountryRegionsByLanguageId(
    ODataActionParameters^ parameters, 
    ODataQueryOptions<CountryRegionInfo^>^ queryOptions
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

<!-- end list -->

  - queryOptions  
    Type: ODataQueryOptions\<CountryRegionInfo\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<CountryRegionInfo\>  
A collection of cities.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

