---
title: WrongEndpointException.RedirectUri Property  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: RedirectUri Property
ms:assetid: P:Microsoft.Dynamics.Retail.RetailServerLibrary.WrongEndpointException.RedirectUri
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.wrongendpointexception.redirecturi(v=AX.60)
ms:contentKeyID: 62202531
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.WrongEndpointException.RedirectUri
dev_langs:
- CSharp
- C++
- VB
---

# RedirectUri Property

Gets the redirect URI object.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Property RedirectUri As Uri
    Get
    Private Set
'Usage
Dim instance As WrongEndpointException
Dim value As Uri

value = instance.RedirectUri
```

``` csharp
public Uri RedirectUri { get; private set; }
```

``` c++
public:
property Uri^ RedirectUri {
    Uri^ get ();
    private: void set (Uri^ value);
}
```

#### Property Value

Type: [System.Uri](https://technet.microsoft.com/library/txt7706a\(v=ax.60\))  
Returns [Uri](https://technet.microsoft.com/library/txt7706a\(v=ax.60\)).  

## See Also

#### Reference

[WrongEndpointException Class](wrongendpointexception-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

