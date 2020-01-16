---
title: NonBindableActionController.GetCashDeclarations Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetCashDeclarations Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetCashDeclarations(System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.CashDeclaration})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getcashdeclarations(v=AX.60)
ms:contentKeyID: 62203761
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetCashDeclarations
dev_langs:
- CSharp
- C++
- VB
---

# GetCashDeclarations Method

Gets all cash declarations for the specific store.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Overridable Function GetCashDeclarations ( _
    queryOptions As ODataQueryOptions(Of CashDeclaration) _
) As IEnumerable(Of CashDeclaration)
'Usage
Dim instance As NonBindableActionController
Dim queryOptions As ODataQueryOptions(Of CashDeclaration)
Dim returnValue As IEnumerable(Of CashDeclaration)

returnValue = instance.GetCashDeclarations(queryOptions)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public virtual IEnumerable<CashDeclaration> GetCashDeclarations(
    ODataQueryOptions<CashDeclaration> queryOptions
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
virtual IEnumerable<CashDeclaration^>^ GetCashDeclarations(
    ODataQueryOptions<CashDeclaration^>^ queryOptions
)
```

#### Parameters

  - queryOptions  
    Type: ODataQueryOptions\<CashDeclaration\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<CashDeclaration\>  
The cash declaration options.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

