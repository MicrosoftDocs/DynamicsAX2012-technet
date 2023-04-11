---
title: NonBindableActionController.GetIncomeExpenseAccounts Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetIncomeExpenseAccounts Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetIncomeExpenseAccounts(System.Web.Http.OData.ODataActionParameters,System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getincomeexpenseaccounts(v=AX.60)
ms:contentKeyID: 62203724
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetIncomeExpenseAccounts
dev_langs:
- CSharp
- C++
- VB
---

# GetIncomeExpenseAccounts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the income or expense accounts.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Overridable Function GetIncomeExpenseAccounts ( _
    parameters As ODataActionParameters, _
    queryOptions As ODataQueryOptions(Of IncomeExpenseAccount) _
) As IEnumerable(Of IncomeExpenseAccount)
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim queryOptions As ODataQueryOptions(Of IncomeExpenseAccount)
Dim returnValue As IEnumerable(Of IncomeExpenseAccount)

returnValue = instance.GetIncomeExpenseAccounts(parameters, _
    queryOptions)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public virtual IEnumerable<IncomeExpenseAccount> GetIncomeExpenseAccounts(
    ODataActionParameters parameters,
    ODataQueryOptions<IncomeExpenseAccount> queryOptions
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public:
virtual IEnumerable<IncomeExpenseAccount^>^ GetIncomeExpenseAccounts(
    ODataActionParameters^ parameters, 
    ODataQueryOptions<IncomeExpenseAccount^>^ queryOptions
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

<!-- end list -->

  - queryOptions  
    Type: ODataQueryOptions\<IncomeExpenseAccount\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<IncomeExpenseAccount\>  
List of income or expense accounts.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

