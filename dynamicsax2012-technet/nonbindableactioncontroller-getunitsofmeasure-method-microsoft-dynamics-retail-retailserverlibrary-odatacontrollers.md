---
title: NonBindableActionController.GetUnitsOfMeasure Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetUnitsOfMeasure Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetUnitsOfMeasure(System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasure})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getunitsofmeasure(v=AX.60)
ms:contentKeyID: 62203056
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetUnitsOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# GetUnitsOfMeasure Method

Get all the units of measure supported by the store.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Overridable Function GetUnitsOfMeasure ( _
    queryOptions As ODataQueryOptions(Of UnitOfMeasure) _
) As IEnumerable(Of UnitOfMeasure)
'Usage
Dim instance As NonBindableActionController
Dim queryOptions As ODataQueryOptions(Of UnitOfMeasure)
Dim returnValue As IEnumerable(Of UnitOfMeasure)

returnValue = instance.GetUnitsOfMeasure(queryOptions)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public virtual IEnumerable<UnitOfMeasure> GetUnitsOfMeasure(
    ODataQueryOptions<UnitOfMeasure> queryOptions
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
virtual IEnumerable<UnitOfMeasure^>^ GetUnitsOfMeasure(
    ODataQueryOptions<UnitOfMeasure^>^ queryOptions
)
```

#### Parameters

  - queryOptions  
    Type: ODataQueryOptions\<UnitOfMeasure\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<UnitOfMeasure\>  
A collection of units of measure.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

