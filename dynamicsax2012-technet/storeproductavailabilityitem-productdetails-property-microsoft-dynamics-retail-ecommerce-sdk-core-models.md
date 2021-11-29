---
title: StoreProductAvailabilityItem.ProductDetails Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: ProductDetails Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.StoreProductAvailabilityItem.ProductDetails
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.storeproductavailabilityitem.productdetails(v=AX.60)
ms:contentKeyID: 65316808
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.StoreProductAvailabilityItem.ProductDetails
dev_langs:
- CSharp
- C++
- VB
---

# ProductDetails Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductDetails As String
    Get
    Set
'Usage
Dim instance As StoreProductAvailabilityItem
Dim value As String

value = instance.ProductDetails

instance.ProductDetails = value
```

``` csharp
[DataMemberAttribute]
public string ProductDetails { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ProductDetails {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[StoreProductAvailabilityItem Class](storeproductavailabilityitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

