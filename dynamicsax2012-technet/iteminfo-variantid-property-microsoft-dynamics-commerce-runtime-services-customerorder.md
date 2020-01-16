---
title: ItemInfo.VariantId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: VariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.ItemInfo.VariantId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.iteminfo.variantid(v=AX.60)
ms:contentKeyID: 62211192
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.ItemInfo.VariantId
dev_langs:
- CSharp
- C++
- VB
---

# VariantId Property

Gets or sets the variant identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property VariantId As String
    Get
    Set
'Usage
Dim instance As ItemInfo
Dim value As String

value = instance.VariantId

instance.VariantId = value
```

``` csharp
public string VariantId { get; set; }
```

``` c++
public:
property String^ VariantId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ItemInfo Class](iteminfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

