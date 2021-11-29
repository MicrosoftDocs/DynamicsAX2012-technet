---
title: NonBindableActionController.GetButtonGrids Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetButtonGrids Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetButtonGrids(System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getbuttongrids(v=AX.60)
ms:contentKeyID: 62203389
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetButtonGrids
dev_langs:
- CSharp
- C++
- VB
---

# GetButtonGrids Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all button grids.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Overridable Function GetButtonGrids ( _
    queryOptions As ODataQueryOptions(Of ButtonGrid) _
) As IEnumerable(Of ButtonGrid)
'Usage
Dim instance As NonBindableActionController
Dim queryOptions As ODataQueryOptions(Of ButtonGrid)
Dim returnValue As IEnumerable(Of ButtonGrid)

returnValue = instance.GetButtonGrids(queryOptions)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public virtual IEnumerable<ButtonGrid> GetButtonGrids(
    ODataQueryOptions<ButtonGrid> queryOptions
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
virtual IEnumerable<ButtonGrid^>^ GetButtonGrids(
    ODataQueryOptions<ButtonGrid^>^ queryOptions
)
```

#### Parameters

  - queryOptions  
    Type: ODataQueryOptions\<ButtonGrid\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<ButtonGrid\>  
Collection of button grids.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

