---
title: ShoppingCartHelper.AddColumns Method  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: AddColumns Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCartHelper.AddColumns(Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.shoppingcarthelper.addcolumns(v=AX.60)
ms:contentKeyID: 62206223
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCartHelper.AddColumns
dev_langs:
- CSharp
- C++
- VB
---

# AddColumns Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Parses the JSON formatted columns definition and add the specified columns to the shopping cart.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub AddColumns ( _
    shoppingCart As ShoppingCart, _
    columns As String _
)
'Usage
Dim shoppingCart As ShoppingCart
Dim columns As String

ShoppingCartHelper.AddColumns(shoppingCart, columns)
```

``` csharp
public static void AddColumns(
    ShoppingCart shoppingCart,
    string columns
)
```

``` c++
public:
static void AddColumns(
    ShoppingCart^ shoppingCart, 
    String^ columns
)
```

#### Parameters

  - shoppingCart  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-controls.md)  

<!-- end list -->

  - columns  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ShoppingCartHelper Class](shoppingcarthelper-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

