---
title: Listing.Identity Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: Identity Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.Identity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.identity(v=AX.60)
ms:contentKeyID: 65317427
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.Identity
dev_langs:
- CSharp
- C++
- VB
---

# Identity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property Identity As String
    Get
'Usage
Dim instance As Listing
Dim value As String

value = instance.Identity
```

``` csharp
[IgnoreDataMemberAttribute]
public string Identity { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property String^ Identity {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

