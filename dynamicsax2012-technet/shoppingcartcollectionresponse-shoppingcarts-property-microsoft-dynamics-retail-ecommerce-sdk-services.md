---
title: ShoppingCartCollectionResponse.ShoppingCarts Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ShoppingCarts Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartCollectionResponse.ShoppingCarts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.shoppingcartcollectionresponse.shoppingcarts(v=AX.60)
ms:contentKeyID: 65316467
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartCollectionResponse.ShoppingCarts
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCarts Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShoppingCarts As Collection(Of ShoppingCart)
    Get
    Friend Set
'Usage
Dim instance As ShoppingCartCollectionResponse
Dim value As Collection(Of ShoppingCart)

value = instance.ShoppingCarts
```

``` csharp
[DataMemberAttribute]
public Collection<ShoppingCart> ShoppingCarts { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<ShoppingCart^>^ ShoppingCarts {
    Collection<ShoppingCart^>^ get ();
    internal: void set (Collection<ShoppingCart^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[ShoppingCartCollectionResponse Class](shoppingcartcollectionresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

