---
title: NonBindableActionController.GetSalesTaxGroups Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetSalesTaxGroups Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetSalesTaxGroups(System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTaxGroup})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getsalestaxgroups(v=AX.60)
ms:contentKeyID: 62203376
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetSalesTaxGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesTaxGroups Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales tax groups.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Function GetSalesTaxGroups ( _
    queryOptions As ODataQueryOptions(Of SalesTaxGroup) _
) As IEnumerable(Of SalesTaxGroup)
'Usage
Dim instance As NonBindableActionController
Dim queryOptions As ODataQueryOptions(Of SalesTaxGroup)
Dim returnValue As IEnumerable(Of SalesTaxGroup)

returnValue = instance.GetSalesTaxGroups(queryOptions)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public IEnumerable<SalesTaxGroup> GetSalesTaxGroups(
    ODataQueryOptions<SalesTaxGroup> queryOptions
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
IEnumerable<SalesTaxGroup^>^ GetSalesTaxGroups(
    ODataQueryOptions<SalesTaxGroup^>^ queryOptions
)
```

#### Parameters

  - queryOptions  
    Type: ODataQueryOptions\<SalesTaxGroup\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<SalesTaxGroup\>  
A collection of sales tax groups.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

