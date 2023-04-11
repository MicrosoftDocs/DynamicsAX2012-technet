---
title: ShoppingCart.AddColumn Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: AddColumn Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart.AddColumn(System.String,Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCartElement[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.shoppingcart.addcolumn(v=AX.60)
ms:contentKeyID: 62204188
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart.AddColumn
dev_langs:
- CSharp
- C++
- VB
---

# AddColumn Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds a new column to the shopping cart grid with the specified header text and column elements.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Sub AddColumn ( _
    headerTextResourceKey As String, _
    ParamArray elements As ShoppingCartElement() _
)
'Usage
Dim instance As ShoppingCart
Dim headerTextResourceKey As String
Dim elements As ShoppingCartElement()

instance.AddColumn(headerTextResourceKey, _
    elements)
```

``` csharp
public void AddColumn(
    string headerTextResourceKey,
    params ShoppingCartElement[] elements
)
```

``` c++
public:
void AddColumn(
    String^ headerTextResourceKey, 
    ... array<ShoppingCartElement>^ elements
)
```

#### Parameters

  - headerTextResourceKey  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - elements  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCartElement](shoppingcartelement-enumeration-microsoft-dynamics-retail-sharepoint-web-controls.md)\[\]  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

