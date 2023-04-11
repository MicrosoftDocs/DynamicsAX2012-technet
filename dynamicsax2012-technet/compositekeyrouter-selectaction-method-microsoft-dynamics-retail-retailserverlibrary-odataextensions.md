---
title: CompositeKeyRouter.SelectAction Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions)
TOCTitle: SelectAction Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CompositeKeyRouter.SelectAction(System.Web.Http.OData.Routing.ODataPath,System.Web.Http.Controllers.HttpControllerContext,System.Linq.ILookup{System.String,System.Web.Http.Controllers.HttpActionDescriptor})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odataextensions.compositekeyrouter.selectaction(v=AX.60)
ms:contentKeyID: 62202134
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CompositeKeyRouter.SelectAction
dev_langs:
- CSharp
- C++
- VB
---

# SelectAction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Selects an OData action.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function SelectAction ( _
    odataPath As ODataPath, _
    controllerContext As HttpControllerContext, _
    actionMap As ILookup(Of String, HttpActionDescriptor) _
) As String
'Usage
Dim instance As CompositeKeyRouter
Dim odataPath As ODataPath
Dim controllerContext As HttpControllerContext
Dim actionMap As ILookup(Of String, HttpActionDescriptor)
Dim returnValue As String

returnValue = instance.SelectAction(odataPath, _
    controllerContext, actionMap)
```

``` csharp
public override string SelectAction(
    ODataPath odataPath,
    HttpControllerContext controllerContext,
    ILookup<string, HttpActionDescriptor> actionMap
)
```

``` c++
public:
virtual String^ SelectAction(
    ODataPath^ odataPath, 
    HttpControllerContext^ controllerContext, 
    ILookup<String^, HttpActionDescriptor^>^ actionMap
) override
```

#### Parameters

  - odataPath  
    Type: ODataPath  

<!-- end list -->

  - controllerContext  
    Type: HttpControllerContext  

<!-- end list -->

  - actionMap  
    Type: [System.Linq.ILookup](https://technet.microsoft.com/library/bb534291\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), HttpActionDescriptor\>  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The action name.  

#### Implements

IODataRoutingConventionSelectAction(ODataPath, HttpControllerContext, ILookup\<String, HttpActionDescriptor\>)  

## See Also

#### Reference

[CompositeKeyRouter Class](compositekeyrouter-class-microsoft-dynamics-retail-retailserverlibrary-odataextensions.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions Namespace](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)

