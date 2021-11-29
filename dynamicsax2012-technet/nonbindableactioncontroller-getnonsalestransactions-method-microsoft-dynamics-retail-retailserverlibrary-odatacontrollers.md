---
title: NonBindableActionController.GetNonSalesTransactions Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetNonSalesTransactions Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetNonSalesTransactions(System.Web.Http.OData.ODataActionParameters,System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getnonsalestransactions(v=AX.60)
ms:contentKeyID: 62202197
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetNonSalesTransactions
dev_langs:
- CSharp
- C++
- VB
---

# GetNonSalesTransactions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the aggregated amount for non sale tender operation.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Overridable Function GetNonSalesTransactions ( _
    parameters As ODataActionParameters, _
    queryOptions As ODataQueryOptions(Of NonSalesTransaction) _
) As IEnumerable(Of NonSalesTransaction)
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim queryOptions As ODataQueryOptions(Of NonSalesTransaction)
Dim returnValue As IEnumerable(Of NonSalesTransaction)

returnValue = instance.GetNonSalesTransactions(parameters, _
    queryOptions)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public virtual IEnumerable<NonSalesTransaction> GetNonSalesTransactions(
    ODataActionParameters parameters,
    ODataQueryOptions<NonSalesTransaction> queryOptions
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public:
virtual IEnumerable<NonSalesTransaction^>^ GetNonSalesTransactions(
    ODataActionParameters^ parameters, 
    ODataQueryOptions<NonSalesTransaction^>^ queryOptions
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

<!-- end list -->

  - queryOptions  
    Type: ODataQueryOptions\<NonSalesTransaction\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<NonSalesTransaction\>  
A collection of non sale transactions.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

