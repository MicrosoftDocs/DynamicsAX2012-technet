---
title: NonBindableActionController.GetZipCodes Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetZipCodes Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetZipCodes(System.Web.Http.OData.ODataActionParameters,System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.ZipCodeInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getzipcodes(v=AX.60)
ms:contentKeyID: 62202414
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetZipCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetZipCodes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get all the zipcodes filtered by country/region, state province, county, city and district.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Overridable Function GetZipCodes ( _
    parameters As ODataActionParameters, _
    queryOptions As ODataQueryOptions(Of ZipCodeInfo) _
) As IEnumerable(Of ZipCodeInfo)
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim queryOptions As ODataQueryOptions(Of ZipCodeInfo)
Dim returnValue As IEnumerable(Of ZipCodeInfo)

returnValue = instance.GetZipCodes(parameters, _
    queryOptions)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public virtual IEnumerable<ZipCodeInfo> GetZipCodes(
    ODataActionParameters parameters,
    ODataQueryOptions<ZipCodeInfo> queryOptions
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
virtual IEnumerable<ZipCodeInfo^>^ GetZipCodes(
    ODataActionParameters^ parameters, 
    ODataQueryOptions<ZipCodeInfo^>^ queryOptions
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

<!-- end list -->

  - queryOptions  
    Type: ODataQueryOptions\<ZipCodeInfo\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<ZipCodeInfo\>  
A collection of zip codes.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

