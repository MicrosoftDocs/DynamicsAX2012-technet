---
title: ShoppingCart.PromotionLines Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: PromotionLines Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCart.PromotionLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.shoppingcart.promotionlines(v=AX.60)
ms:contentKeyID: 65316503
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCart.PromotionLines
dev_langs:
- CSharp
- C++
- VB
---

# PromotionLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PromotionLines As Collection(Of String)
    Get
    Private Set
'Usage
Dim instance As ShoppingCart
Dim value As Collection(Of String)

value = instance.PromotionLines
```

``` csharp
[DataMemberAttribute]
public Collection<string> PromotionLines { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<String^>^ PromotionLines {
    Collection<String^>^ get ();
    private: void set (Collection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

