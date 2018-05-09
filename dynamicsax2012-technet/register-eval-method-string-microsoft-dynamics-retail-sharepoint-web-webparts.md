---
title: Register.Eval Method (String) (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: Eval Method (String)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Register.Eval(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.register.eval(v=AX.60)
ms:contentKeyID: 62206814
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

[Register Class](register-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Eval Overload](register-eval-method-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

