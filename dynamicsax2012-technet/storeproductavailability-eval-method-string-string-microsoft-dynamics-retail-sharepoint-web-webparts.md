---
title: StoreProductAvailability.Eval Method (String, String) (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: Eval Method (String, String)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.StoreProductAvailability.Eval(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.storeproductavailability.eval(v=AX.60)
ms:contentKeyID: 62206082
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Eval Method (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function Eval ( _
    expression As String, _
    format As String _
) As String
'Usage
Dim expression As String
Dim format As String
Dim returnValue As String

returnValue = Me.Eval(expression, _
    format)
```

``` csharp
protected virtual string Eval(
    string expression,
    string format
)
```

``` c++
protected:
virtual String^ Eval(
    String^ expression, 
    String^ format
)
```

#### Parameters

  - expression  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - format  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[StoreProductAvailability Class](storeproductavailability-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Eval Overload](storeproductavailability-eval-method-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

