---
title: Listing.InventoryDimension Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: InventoryDimension Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.InventoryDimension
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.inventorydimension(v=AX.60)
ms:contentKeyID: 65317006
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.InventoryDimension
dev_langs:
- CSharp
- C++
- VB
---

# InventoryDimension Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventoryDimension As String
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As String

value = instance.InventoryDimension
```

``` csharp
[DataMemberAttribute]
public string InventoryDimension { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventoryDimension {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

