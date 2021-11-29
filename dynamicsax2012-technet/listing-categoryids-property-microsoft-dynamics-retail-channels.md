---
title: Listing.CategoryIds Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: CategoryIds Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.CategoryIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.categoryids(v=AX.60)
ms:contentKeyID: 65317609
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.CategoryIds
dev_langs:
- CSharp
- C++
- VB
---

# CategoryIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CategoryIds As ICollection(Of Long)
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As ICollection(Of Long)

value = instance.CategoryIds
```

``` csharp
[DataMemberAttribute]
public ICollection<long> CategoryIds { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<long long>^ CategoryIds {
    ICollection<long long>^ get ();
    internal: void set (ICollection<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

