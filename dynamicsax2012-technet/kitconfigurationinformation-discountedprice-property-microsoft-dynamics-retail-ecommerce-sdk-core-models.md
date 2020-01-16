---
title: KitConfigurationInformation.DiscountedPrice Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: DiscountedPrice Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.KitConfigurationInformation.DiscountedPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.kitconfigurationinformation.discountedprice(v=AX.60)
ms:contentKeyID: 65317248
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.KitConfigurationInformation.DiscountedPrice
dev_langs:
- CSharp
- C++
- VB
---

# DiscountedPrice Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountedPrice As Decimal
    Get
    Set
'Usage
Dim instance As KitConfigurationInformation
Dim value As Decimal

value = instance.DiscountedPrice

instance.DiscountedPrice = value
```

``` csharp
[DataMemberAttribute]
public decimal DiscountedPrice { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal DiscountedPrice {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[KitConfigurationInformation Class](kitconfigurationinformation-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

