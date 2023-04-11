---
title: CommerceErrorHelper.IsExceptionSupported Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions)
TOCTitle: IsExceptionSupported Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CommerceErrorHelper.IsExceptionSupported(System.Exception,System.Net.Http.HttpRequestMessage)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odataextensions.commerceerrorhelper.isexceptionsupported(v=AX.60)
ms:contentKeyID: 62202662
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CommerceErrorHelper.IsExceptionSupported
dev_langs:
- CSharp
- C++
- VB
---

# IsExceptionSupported Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checks if expcetion is supported or not.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function IsExceptionSupported ( _
    exception As Exception, _
    request As HttpRequestMessage _
) As Boolean
'Usage
Dim exception As Exception
Dim request As HttpRequestMessage
Dim returnValue As Boolean

returnValue = Me.IsExceptionSupported(exception, _
    request)
```

``` csharp
protected virtual bool IsExceptionSupported(
    Exception exception,
    HttpRequestMessage request
)
```

``` c++
protected:
virtual bool IsExceptionSupported(
    Exception^ exception, 
    HttpRequestMessage^ request
)
```

#### Parameters

  - exception  
    Type: [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  

<!-- end list -->

  - request  
    Type: HttpRequestMessage  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Whether the exception is supported or not.  

## See Also

#### Reference

[CommerceErrorHelper Class](commerceerrorhelper-class-microsoft-dynamics-retail-retailserverlibrary-odataextensions.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions Namespace](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)

