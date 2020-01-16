---
title: Listing.CatalogId Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: CatalogId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.CatalogId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.catalogid(v=AX.60)
ms:contentKeyID: 65317780
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.CatalogId
dev_langs:
- CSharp
- C++
- VB
---

# CatalogId Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CatalogId As Long
    Get
    Set
'Usage
Dim instance As Listing
Dim value As Long

value = instance.CatalogId

instance.CatalogId = value
```

``` csharp
[DataMemberAttribute]
public long CatalogId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long CatalogId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

