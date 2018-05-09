---
title: Listing.ParentProductId Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: ParentProductId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.ParentProductId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.channels.listing.parentproductid(v=AX.60)
ms:contentKeyID: 65317288
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.ParentProductId
dev_langs:
- CSharp
- C++
- VB
---

# ParentProductId Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ParentProductId As Long
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As Long

value = instance.ParentProductId
```

``` csharp
[DataMemberAttribute]
public long ParentProductId { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property long long ParentProductId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

