---
title: NonBindableActionController.GetReasonCodesByGroupOrSingleId Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetReasonCodesByGroupOrSingleId Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetReasonCodesByGroupOrSingleId(System.Web.Http.OData.ODataActionParameters,System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getreasoncodesbygrouporsingleid(v=AX.60)
ms:contentKeyID: 62202024
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetReasonCodesByGroupOrSingleId
dev_langs:
- CSharp
- C++
- VB
---

# GetReasonCodesByGroupOrSingleId Method

Gets the reason codes by group or single identifier.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<HttpPostAttribute> _
Public Overridable Function GetReasonCodesByGroupOrSingleId ( _
    parameters As ODataActionParameters, _
    queryOptions As ODataQueryOptions(Of ReasonCode) _
) As IEnumerable(Of ReasonCode)
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim queryOptions As ODataQueryOptions(Of ReasonCode)
Dim returnValue As IEnumerable(Of ReasonCode)

returnValue = instance.GetReasonCodesByGroupOrSingleId(parameters, _
    queryOptions)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public virtual IEnumerable<ReasonCode> GetReasonCodesByGroupOrSingleId(
    ODataActionParameters parameters,
    ODataQueryOptions<ReasonCode> queryOptions
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[HttpPostAttribute]
public:
virtual IEnumerable<ReasonCode^>^ GetReasonCodesByGroupOrSingleId(
    ODataActionParameters^ parameters, 
    ODataQueryOptions<ReasonCode^>^ queryOptions
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

<!-- end list -->

  - queryOptions  
    Type: ODataQueryOptions\<ReasonCode\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<ReasonCode\>  
A collection of reason codes.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

