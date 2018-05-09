---
title: ShoppingCartHelper.AddKitComponentsColumns Method  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: AddKitComponentsColumns Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCartHelper.AddKitComponentsColumns(Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.shoppingcarthelper.addkitcomponentscolumns(v=AX.60)
ms:contentKeyID: 62205030
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCartHelper.AddKitComponentsColumns
dev_langs:
- CSharp
- C++
- VB
---

# AddKitComponentsColumns Method

Parses the JSON formatted columns definition and add the specified columns for kit components to the shopping cart.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub AddKitComponentsColumns ( _
    shoppingCart As ShoppingCart, _
    kitColumns As String _
)
'Usage
Dim shoppingCart As ShoppingCart
Dim kitColumns As String

ShoppingCartHelper.AddKitComponentsColumns(shoppingCart, _
    kitColumns)
```

``` csharp
public static void AddKitComponentsColumns(
    ShoppingCart shoppingCart,
    string kitColumns
)
```

``` c++
public:
static void AddKitComponentsColumns(
    ShoppingCart^ shoppingCart, 
    String^ kitColumns
)
```

#### Parameters

  - shoppingCart  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-controls.md)  

<!-- end list -->

  - kitColumns  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ShoppingCartHelper Class](shoppingcarthelper-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

