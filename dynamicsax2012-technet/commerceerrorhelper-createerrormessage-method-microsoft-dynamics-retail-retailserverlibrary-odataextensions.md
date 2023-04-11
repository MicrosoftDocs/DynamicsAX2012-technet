---
title: CommerceErrorHelper.CreateErrorMessage Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions)
TOCTitle: CreateErrorMessage Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CommerceErrorHelper.CreateErrorMessage(System.Exception,System.Net.Http.HttpRequestMessage)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odataextensions.commerceerrorhelper.createerrormessage(v=AX.60)
ms:contentKeyID: 62203396
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CommerceErrorHelper.CreateErrorMessage
dev_langs:
- CSharp
- C++
- VB
---

# CreateErrorMessage Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the odata error from [Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\)).

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Function CreateErrorMessage ( _
    exception As Exception, _
    request As HttpRequestMessage _
) As HttpResponseMessage
'Usage
Dim instance As CommerceErrorHelper
Dim exception As Exception
Dim request As HttpRequestMessage
Dim returnValue As HttpResponseMessage

returnValue = instance.CreateErrorMessage(exception, _
    request)
```

``` csharp
public HttpResponseMessage CreateErrorMessage(
    Exception exception,
    HttpRequestMessage request
)
```

``` c++
public:
HttpResponseMessage^ CreateErrorMessage(
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

Type: HttpResponseMessage  
The http response message.  

## See Also

#### Reference

[CommerceErrorHelper Class](commerceerrorhelper-class-microsoft-dynamics-retail-retailserverlibrary-odataextensions.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions Namespace](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)

