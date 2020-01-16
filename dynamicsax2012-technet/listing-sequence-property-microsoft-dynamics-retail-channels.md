---
title: Listing.Sequence Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: Sequence Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.Sequence
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.sequence(v=AX.60)
ms:contentKeyID: 65318535
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.Sequence
dev_langs:
- CSharp
- C++
- VB
---

# Sequence Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Sequence As Long
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As Long

value = instance.Sequence
```

``` csharp
[DataMemberAttribute]
public long Sequence { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property long long Sequence {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

