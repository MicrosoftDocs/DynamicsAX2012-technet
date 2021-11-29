---
title: ShoppingCart.AddKitComponentColumn Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: AddKitComponentColumn Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart.AddKitComponentColumn(System.String,Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCartElement[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.shoppingcart.addkitcomponentcolumn(v=AX.60)
ms:contentKeyID: 62205887
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart.AddKitComponentColumn
dev_langs:
- CSharp
- C++
- VB
---

# AddKitComponentColumn Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds a new column for kit component in the shopping cart grid with the specified class name and elements.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Sub AddKitComponentColumn ( _
    wrapperClass As String, _
    ParamArray elements As ShoppingCartElement() _
)
'Usage
Dim instance As ShoppingCart
Dim wrapperClass As String
Dim elements As ShoppingCartElement()

instance.AddKitComponentColumn(wrapperClass, _
    elements)
```

``` csharp
public void AddKitComponentColumn(
    string wrapperClass,
    params ShoppingCartElement[] elements
)
```

``` c++
public:
void AddKitComponentColumn(
    String^ wrapperClass, 
    ... array<ShoppingCartElement>^ elements
)
```

#### Parameters

  - wrapperClass  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - elements  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCartElement](shoppingcartelement-enumeration-microsoft-dynamics-retail-sharepoint-web-controls.md)\[\]  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

