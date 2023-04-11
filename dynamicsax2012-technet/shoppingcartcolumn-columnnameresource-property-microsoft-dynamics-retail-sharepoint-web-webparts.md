---
title: ShoppingCartColumn.ColumnNameResource Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ColumnNameResource Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCartColumn.ColumnNameResource
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.shoppingcartcolumn.columnnameresource(v=AX.60)
ms:contentKeyID: 62206684
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCartColumn.ColumnNameResource
dev_langs:
- CSharp
- C++
- VB
---

# ColumnNameResource Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the column name resource key to look up.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Public Property ColumnNameResource As String
    Get
    Set
'Usage
Dim instance As ShoppingCartColumn
Dim value As String

value = instance.ColumnNameResource

instance.ColumnNameResource = value
```

``` csharp
public string ColumnNameResource { get; set; }
```

``` c++
public:
property String^ ColumnNameResource {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShoppingCartColumn Class](shoppingcartcolumn-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

