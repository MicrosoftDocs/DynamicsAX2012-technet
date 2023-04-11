---
title: Listing.ChangeActionValue Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: ChangeActionValue Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.ChangeActionValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.changeactionvalue(v=AX.60)
ms:contentKeyID: 65317330
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.ChangeActionValue
dev_langs:
- CSharp
- C++
- VB
---

# ChangeActionValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChangeActionValue As Integer
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As Integer

value = instance.ChangeActionValue
```

``` csharp
[DataMemberAttribute]
public int ChangeActionValue { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property int ChangeActionValue {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

