---
title: Listing.ValidFrom Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: ValidFrom Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.ValidFrom
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.validfrom(v=AX.60)
ms:contentKeyID: 65315866
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.ValidFrom
dev_langs:
- CSharp
- C++
- VB
---

# ValidFrom Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ValidFrom As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As DateTimeOffset

value = instance.ValidFrom
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset ValidFrom { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset ValidFrom {
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

