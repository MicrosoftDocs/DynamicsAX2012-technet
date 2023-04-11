---
title: Listing.ProductNumber Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: ProductNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.ProductNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.productnumber(v=AX.60)
ms:contentKeyID: 65315945
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.ProductNumber
dev_langs:
- CSharp
- C++
- VB
---

# ProductNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductNumber As String
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As String

value = instance.ProductNumber
```

``` csharp
[DataMemberAttribute]
public string ProductNumber { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ProductNumber {
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

