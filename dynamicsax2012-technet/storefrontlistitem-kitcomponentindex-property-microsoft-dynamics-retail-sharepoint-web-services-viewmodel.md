---
title: StorefrontListItem.KitComponentIndex Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: KitComponentIndex Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StorefrontListItem.KitComponentIndex
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.storefrontlistitem.kitcomponentindex(v=AX.60)
ms:contentKeyID: 62205467
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StorefrontListItem.KitComponentIndex
dev_langs:
- CSharp
- C++
- VB
---

# KitComponentIndex Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets key value pairs of line identifiers and parent kit identifiers.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitComponentIndex As String
    Get
    Set
'Usage
Dim instance As StorefrontListItem
Dim value As String

value = instance.KitComponentIndex

instance.KitComponentIndex = value
```

``` csharp
[DataMemberAttribute]
public string KitComponentIndex { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ KitComponentIndex {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[StorefrontListItem Class](storefrontlistitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

