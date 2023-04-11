---
title: Listing.AdjustedPrice Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: AdjustedPrice Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.AdjustedPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.adjustedprice(v=AX.60)
ms:contentKeyID: 65317277
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.AdjustedPrice
dev_langs:
- CSharp
- C++
- VB
---

# AdjustedPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AdjustedPrice As Decimal
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As Decimal

value = instance.AdjustedPrice
```

``` csharp
[DataMemberAttribute]
public decimal AdjustedPrice { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal AdjustedPrice {
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

