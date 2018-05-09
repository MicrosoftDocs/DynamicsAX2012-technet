---
title: NonBindableActionController.GetReturnReasonCodes Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetReturnReasonCodes Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetReturnReasonCodes(System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReturnReasonCode})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getreturnreasoncodes(v=AX.60)
ms:contentKeyID: 62201925
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetReturnReasonCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetReturnReasonCodes Method

Gets reason codes by group or single code ID.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Overridable Function GetReturnReasonCodes ( _
    queryOptions As ODataQueryOptions(Of ReturnReasonCode) _
) As IEnumerable(Of ReturnReasonCode)
'Usage
Dim instance As NonBindableActionController
Dim queryOptions As ODataQueryOptions(Of ReturnReasonCode)
Dim returnValue As IEnumerable(Of ReturnReasonCode)

returnValue = instance.GetReturnReasonCodes(queryOptions)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public virtual IEnumerable<ReturnReasonCode> GetReturnReasonCodes(
    ODataQueryOptions<ReturnReasonCode> queryOptions
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public:
virtual IEnumerable<ReturnReasonCode^>^ GetReturnReasonCodes(
    ODataQueryOptions<ReturnReasonCode^>^ queryOptions
)
```

#### Parameters

  - queryOptions  
    Type: ODataQueryOptions\<ReturnReasonCode\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<ReturnReasonCode\>  
The collection of reason codes.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

