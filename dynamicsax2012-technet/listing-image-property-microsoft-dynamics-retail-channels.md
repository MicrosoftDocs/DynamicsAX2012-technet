---
title: Listing.Image Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: Image Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.Image
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.image(v=AX.60)
ms:contentKeyID: 65317590
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.Image
dev_langs:
- CSharp
- C++
- VB
---

# Image Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property Image As RichMediaLocations
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As RichMediaLocations

value = instance.Image
```

``` csharp
[IgnoreDataMemberAttribute]
public RichMediaLocations Image { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property RichMediaLocations^ Image {
    RichMediaLocations^ get ();
    internal: void set (RichMediaLocations^ value);
}
```

#### Property Value

Type: RichMediaLocations  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

