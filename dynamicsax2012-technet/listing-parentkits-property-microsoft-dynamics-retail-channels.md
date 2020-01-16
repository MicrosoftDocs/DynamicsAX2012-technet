---
title: Listing.ParentKits Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: ParentKits Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.ParentKits
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.parentkits(v=AX.60)
ms:contentKeyID: 65317351
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.ParentKits
dev_langs:
- CSharp
- C++
- VB
---

# ParentKits Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ParentKits As ICollection(Of KitComponent)
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As ICollection(Of KitComponent)

value = instance.ParentKits
```

``` csharp
[DataMemberAttribute]
public ICollection<KitComponent> ParentKits { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<KitComponent^>^ ParentKits {
    ICollection<KitComponent^>^ get ();
    internal: void set (ICollection<KitComponent^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<KitComponent\>  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

