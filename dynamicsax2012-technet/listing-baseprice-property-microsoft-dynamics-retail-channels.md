---
title: Listing.BasePrice Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: BasePrice Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.BasePrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.baseprice(v=AX.60)
ms:contentKeyID: 65316088
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.BasePrice
dev_langs:
- CSharp
- C++
- VB
---

# BasePrice Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property BasePrice As Decimal
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As Decimal

value = instance.BasePrice
```

``` csharp
[DataMemberAttribute]
public decimal BasePrice { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal BasePrice {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

