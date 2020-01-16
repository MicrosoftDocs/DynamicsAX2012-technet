---
title: Listing.Action Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: Action Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.Action
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.action(v=AX.60)
ms:contentKeyID: 65316835
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.Action
dev_langs:
- CSharp
- C++
- VB
---

# Action Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property Action As PublishingAction
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As PublishingAction

value = instance.Action
```

``` csharp
[IgnoreDataMemberAttribute]
public PublishingAction Action { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property PublishingAction Action {
    PublishingAction get ();
    internal: void set (PublishingAction value);
}
```

#### Property Value

Type: PublishingAction  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

