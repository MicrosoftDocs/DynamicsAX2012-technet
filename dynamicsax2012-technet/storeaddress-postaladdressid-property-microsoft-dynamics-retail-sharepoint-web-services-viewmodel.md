---
title: StoreAddress.PostalAddressId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: PostalAddressId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreAddress.PostalAddressId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.storeaddress.postaladdressid(v=AX.60)
ms:contentKeyID: 62203211
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreAddress.PostalAddressId
dev_langs:
- CSharp
- C++
- VB
---

# PostalAddressId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the location record ID.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PostalAddressId As Long
    Get
    Set
'Usage
Dim instance As StoreAddress
Dim value As Long

value = instance.PostalAddressId

instance.PostalAddressId = value
```

``` csharp
[DataMemberAttribute]
public long PostalAddressId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long PostalAddressId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[StoreAddress Class](storeaddress-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

