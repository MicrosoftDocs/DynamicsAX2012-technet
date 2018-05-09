---
title: CustomerDisplay.Eval Method (String) (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: Eval Method (String)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.CustomerDisplay.Eval(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.customerdisplay.eval(v=AX.60)
ms:contentKeyID: 62204840
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Eval Method (String)

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
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
Returns [Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\)).  

## See Also

#### Reference

[CustomerDisplay Class](customerdisplay-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Eval Overload](customerdisplay-eval-method-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

