---
title: ShoppingCart.LastModifiedDate Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: LastModifiedDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCart.LastModifiedDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.shoppingcart.lastmodifieddate(v=AX.60)
ms:contentKeyID: 65317303
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCart.LastModifiedDate
dev_langs:
- CSharp
- C++
- VB
---

# LastModifiedDate Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LastModifiedDate As DateTime
    Get
    Set
'Usage
Dim instance As ShoppingCart
Dim value As DateTime

value = instance.LastModifiedDate

instance.LastModifiedDate = value
```

``` csharp
[DataMemberAttribute]
public DateTime LastModifiedDate { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTime LastModifiedDate {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

