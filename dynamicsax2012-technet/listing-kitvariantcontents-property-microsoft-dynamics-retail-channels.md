---
title: Listing.KitVariantContents Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: KitVariantContents Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.KitVariantContents
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.kitvariantcontents(v=AX.60)
ms:contentKeyID: 65316991
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.KitVariantContents
dev_langs:
- CSharp
- C++
- VB
---

# KitVariantContents Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitVariantContents As ICollection(Of KitComponentKey)
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As ICollection(Of KitComponentKey)

value = instance.KitVariantContents
```

``` csharp
[DataMemberAttribute]
public ICollection<KitComponentKey> KitVariantContents { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<KitComponentKey^>^ KitVariantContents {
    ICollection<KitComponentKey^>^ get ();
    internal: void set (ICollection<KitComponentKey^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<KitComponentKey\>  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

