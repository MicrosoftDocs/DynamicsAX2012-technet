---
title: ShoppingCartResponse.ShoppingCart Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ShoppingCart Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartResponse.ShoppingCart
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.shoppingcartresponse.shoppingcart(v=AX.60)
ms:contentKeyID: 65318588
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartResponse.ShoppingCart
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCart Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShoppingCart As ShoppingCart
    Get
    Set
'Usage
Dim instance As ShoppingCartResponse
Dim value As ShoppingCart

value = instance.ShoppingCart

instance.ShoppingCart = value
```

``` csharp
[DataMemberAttribute]
public ShoppingCart ShoppingCart { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ShoppingCart^ ShoppingCart {
    ShoppingCart^ get ();
    void set (ShoppingCart^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[ShoppingCartResponse Class](shoppingcartresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

