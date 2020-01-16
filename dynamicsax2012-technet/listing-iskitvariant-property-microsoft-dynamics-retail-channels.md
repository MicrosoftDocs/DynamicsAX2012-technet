---
title: Listing.IsKitVariant Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: IsKitVariant Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.IsKitVariant
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.iskitvariant(v=AX.60)
ms:contentKeyID: 65318168
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.IsKitVariant
dev_langs:
- CSharp
- C++
- VB
---

# IsKitVariant Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsKitVariant As Boolean
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As Boolean

value = instance.IsKitVariant
```

``` csharp
[DataMemberAttribute]
public bool IsKitVariant { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsKitVariant {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

