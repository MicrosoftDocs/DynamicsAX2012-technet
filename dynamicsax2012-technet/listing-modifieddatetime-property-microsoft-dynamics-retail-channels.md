---
title: Listing.ModifiedDateTime Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: ModifiedDateTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.ModifiedDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.modifieddatetime(v=AX.60)
ms:contentKeyID: 65318659
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.ModifiedDateTime
dev_langs:
- CSharp
- C++
- VB
---

# ModifiedDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ModifiedDateTime As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As DateTimeOffset

value = instance.ModifiedDateTime
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset ModifiedDateTime { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset ModifiedDateTime {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

