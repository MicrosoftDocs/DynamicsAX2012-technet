---
title: KitComponentInfo.KitLineIdentifier Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: KitLineIdentifier Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitComponentInfo.KitLineIdentifier
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.kitcomponentinfo.kitlineidentifier(v=AX.60)
ms:contentKeyID: 62206513
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitComponentInfo.KitLineIdentifier
dev_langs:
- CSharp
- C++
- VB
---

# KitLineIdentifier Property

Gets the kit line identifier.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitLineIdentifier As Long
    Get
    Set
'Usage
Dim instance As KitComponentInfo
Dim value As Long

value = instance.KitLineIdentifier

instance.KitLineIdentifier = value
```

``` csharp
[DataMemberAttribute]
public long KitLineIdentifier { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long KitLineIdentifier {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[KitComponentInfo Class](kitcomponentinfo-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

