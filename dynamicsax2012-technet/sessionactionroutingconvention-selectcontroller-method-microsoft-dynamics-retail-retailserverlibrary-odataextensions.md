---
title: SessionActionRoutingConvention.SelectController Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions)
TOCTitle: SelectController Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.SessionActionRoutingConvention.SelectController(System.Web.Http.OData.Routing.ODataPath,System.Net.Http.HttpRequestMessage)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odataextensions.sessionactionroutingconvention.selectcontroller(v=AX.60)
ms:contentKeyID: 62201896
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.SessionActionRoutingConvention.SelectController
dev_langs:
- CSharp
- C++
- VB
---

# SelectController Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the predefined controller name for all non-bindable action requests.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function SelectController ( _
    odataPath As ODataPath, _
    request As HttpRequestMessage _
) As String
'Usage
Dim instance As SessionActionRoutingConvention
Dim odataPath As ODataPath
Dim request As HttpRequestMessage
Dim returnValue As String

returnValue = instance.SelectController(odataPath, _
    request)
```

``` csharp
public override string SelectController(
    ODataPath odataPath,
    HttpRequestMessage request
)
```

``` c++
public:
virtual String^ SelectController(
    ODataPath^ odataPath, 
    HttpRequestMessage^ request
) override
```

#### Parameters

  - odataPath  
    Type: ODataPath  

<!-- end list -->

  - request  
    Type: HttpRequestMessage  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The controller name.  

#### Implements

IODataRoutingConventionSelectController(ODataPath, HttpRequestMessage)  

## See Also

#### Reference

[SessionActionRoutingConvention Class](sessionactionroutingconvention-class-microsoft-dynamics-retail-retailserverlibrary-odataextensions.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions Namespace](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)

