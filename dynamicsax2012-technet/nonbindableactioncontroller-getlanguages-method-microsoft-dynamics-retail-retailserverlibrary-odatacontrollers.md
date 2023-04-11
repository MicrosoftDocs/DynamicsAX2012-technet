---
title: NonBindableActionController.GetLanguages Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetLanguages Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetLanguages(System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.SupportedLanguage})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getlanguages(v=AX.60)
ms:contentKeyID: 62201948
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetLanguages
dev_langs:
- CSharp
- C++
- VB
---

# GetLanguages Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets collection of supported languages.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Overridable Function GetLanguages ( _
    queryOptions As ODataQueryOptions(Of SupportedLanguage) _
) As IEnumerable(Of SupportedLanguage)
'Usage
Dim instance As NonBindableActionController
Dim queryOptions As ODataQueryOptions(Of SupportedLanguage)
Dim returnValue As IEnumerable(Of SupportedLanguage)

returnValue = instance.GetLanguages(queryOptions)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public virtual IEnumerable<SupportedLanguage> GetLanguages(
    ODataQueryOptions<SupportedLanguage> queryOptions
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
virtual IEnumerable<SupportedLanguage^>^ GetLanguages(
    ODataQueryOptions<SupportedLanguage^>^ queryOptions
)
```

#### Parameters

  - queryOptions  
    Type: ODataQueryOptions\<SupportedLanguage\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<SupportedLanguage\>  
A collection of supported languages.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

