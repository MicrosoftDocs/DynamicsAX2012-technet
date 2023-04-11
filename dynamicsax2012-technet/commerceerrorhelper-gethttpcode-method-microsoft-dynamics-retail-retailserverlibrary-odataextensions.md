---
title: CommerceErrorHelper.GetHttpCode Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions)
TOCTitle: GetHttpCode Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CommerceErrorHelper.GetHttpCode(System.Exception)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odataextensions.commerceerrorhelper.gethttpcode(v=AX.60)
ms:contentKeyID: 62202681
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CommerceErrorHelper.GetHttpCode
dev_langs:
- CSharp
- C++
- VB
---

# GetHttpCode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the HTTP code based on the exception.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetHttpCode ( _
    exception As Exception _
) As HttpStatusCode
'Usage
Dim exception As Exception
Dim returnValue As HttpStatusCode

returnValue = Me.GetHttpCode(exception)
```

``` csharp
protected virtual HttpStatusCode GetHttpCode(
    Exception exception
)
```

``` c++
protected:
virtual HttpStatusCode GetHttpCode(
    Exception^ exception
)
```

#### Parameters

  - exception  
    Type: [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  

#### Return Value

Type: [System.Net.HttpStatusCode](https://technet.microsoft.com/library/f92ssyy1\(v=ax.60\))  
The http status code.  

## See Also

#### Reference

[CommerceErrorHelper Class](commerceerrorhelper-class-microsoft-dynamics-retail-retailserverlibrary-odataextensions.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions Namespace](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)

