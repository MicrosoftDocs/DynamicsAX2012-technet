---
title: ExtendedControllerSelector.SelectController Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: SelectController Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ExtendedControllerSelector.SelectController(System.Net.Http.HttpRequestMessage)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.extendedcontrollerselector.selectcontroller(v=AX.60)
ms:contentKeyID: 62201966
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ExtendedControllerSelector.SelectController
dev_langs:
- CSharp
- C++
- VB
---

# SelectController Method

Selects controller based on request.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function SelectController ( _
    request As HttpRequestMessage _
) As HttpControllerDescriptor
'Usage
Dim instance As ExtendedControllerSelector
Dim request As HttpRequestMessage
Dim returnValue As HttpControllerDescriptor

returnValue = instance.SelectController(request)
```

``` csharp
public override HttpControllerDescriptor SelectController(
    HttpRequestMessage request
)
```

``` c++
public:
virtual HttpControllerDescriptor^ SelectController(
    HttpRequestMessage^ request
) override
```

#### Parameters

  - request  
    Type: HttpRequestMessage  

#### Return Value

Type: HttpControllerDescriptor  
The HttpControllerDescriptor of the matched controller.  

#### Implements

IHttpControllerSelectorSelectController(HttpRequestMessage)  

## See Also

#### Reference

[ExtendedControllerSelector Class](extendedcontrollerselector-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

