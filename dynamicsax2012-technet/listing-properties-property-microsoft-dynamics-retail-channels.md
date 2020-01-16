---
title: Listing.Properties Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: Properties Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.Properties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.properties(v=AX.60)
ms:contentKeyID: 65317889
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.Properties
dev_langs:
- CSharp
- C++
- VB
---

# Properties Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property Properties As ProductPropertyDictionary
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As ProductPropertyDictionary

value = instance.Properties
```

``` csharp
[IgnoreDataMemberAttribute]
public ProductPropertyDictionary Properties { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ProductPropertyDictionary^ Properties {
    ProductPropertyDictionary^ get ();
    internal: void set (ProductPropertyDictionary^ value);
}
```

#### Property Value

Type: ProductPropertyDictionary  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

