---
title: AddToCart.Eval Method (String) (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: Eval Method (String)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddToCart.Eval(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.addtocart.eval(v=AX.60)
ms:contentKeyID: 62205808
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Eval Method (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function Eval ( _
    expression As String _
) As Object
'Usage
Dim expression As String
Dim returnValue As Object

returnValue = Me.Eval(expression)
```

``` csharp
protected virtual Object Eval(
    string expression
)
```

``` c++
protected:
virtual Object^ Eval(
    String^ expression
)
```

#### Parameters

  - expression  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
Returns [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\)).  

## See Also

#### Reference

[AddToCart Class](addtocart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Eval Overload](addtocart-eval-method-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

