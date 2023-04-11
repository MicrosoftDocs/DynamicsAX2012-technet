---
title: KitComponentInfo.KitLineProductId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: KitLineProductId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitComponentInfo.KitLineProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.kitcomponentinfo.kitlineproductid(v=AX.60)
ms:contentKeyID: 62202570
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitComponentInfo.KitLineProductId
dev_langs:
- CSharp
- C++
- VB
---

# KitLineProductId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the productId of the product used in a kit as a component or substitute.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitLineProductId As Long
    Get
    Set
'Usage
Dim instance As KitComponentInfo
Dim value As Long

value = instance.KitLineProductId

instance.KitLineProductId = value
```

``` csharp
[DataMemberAttribute]
public long KitLineProductId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long KitLineProductId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[KitComponentInfo Class](kitcomponentinfo-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

