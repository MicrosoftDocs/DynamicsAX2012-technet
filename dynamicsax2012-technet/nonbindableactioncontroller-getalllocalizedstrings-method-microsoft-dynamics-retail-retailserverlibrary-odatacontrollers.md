---
title: NonBindableActionController.GetAllLocalizedStrings Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetAllLocalizedStrings Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetAllLocalizedStrings(System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getalllocalizedstrings(v=AX.60)
ms:contentKeyID: 62202761
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetAllLocalizedStrings
dev_langs:
- CSharp
- C++
- VB
---

# GetAllLocalizedStrings Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all localized strings.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Overridable Function GetAllLocalizedStrings ( _
    queryOptions As ODataQueryOptions(Of LocalizedString) _
) As IEnumerable(Of LocalizedString)
'Usage
Dim instance As NonBindableActionController
Dim queryOptions As ODataQueryOptions(Of LocalizedString)
Dim returnValue As IEnumerable(Of LocalizedString)

returnValue = instance.GetAllLocalizedStrings(queryOptions)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public virtual IEnumerable<LocalizedString> GetAllLocalizedStrings(
    ODataQueryOptions<LocalizedString> queryOptions
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
virtual IEnumerable<LocalizedString^>^ GetAllLocalizedStrings(
    ODataQueryOptions<LocalizedString^>^ queryOptions
)
```

#### Parameters

  - queryOptions  
    Type: ODataQueryOptions\<LocalizedString\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<LocalizedString\>  
A collection of localized strings.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

