---
title: ShoppingCartColumn.DataFields Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: DataFields Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCartColumn.DataFields
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.shoppingcartcolumn.datafields(v=AX.60)
ms:contentKeyID: 62207392
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCartColumn.DataFields
dev_langs:
- CSharp
- C++
- VB
---

# DataFields Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the data fields that will be displayed within the column.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Public Property DataFields As String()
    Get
    Set
'Usage
Dim instance As ShoppingCartColumn
Dim value As String()

value = instance.DataFields

instance.DataFields = value
```

``` csharp
public string[] DataFields { get; set; }
```

``` c++
public:
property array<String^>^ DataFields {
    array<String^>^ get ();
    void set (array<String^>^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShoppingCartColumn Class](shoppingcartcolumn-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

