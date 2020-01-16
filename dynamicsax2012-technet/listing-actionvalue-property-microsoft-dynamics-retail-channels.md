---
title: Listing.ActionValue Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: ActionValue Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.ActionValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.actionvalue(v=AX.60)
ms:contentKeyID: 65317148
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.ActionValue
dev_langs:
- CSharp
- C++
- VB
---

# ActionValue Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ActionValue As Integer
    Get
    Set
'Usage
Dim instance As Listing
Dim value As Integer

value = instance.ActionValue

instance.ActionValue = value
```

``` csharp
[DataMemberAttribute]
public int ActionValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int ActionValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

