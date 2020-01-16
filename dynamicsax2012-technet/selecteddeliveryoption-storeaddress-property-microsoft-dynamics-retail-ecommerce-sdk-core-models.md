---
title: SelectedDeliveryOption.StoreAddress Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: StoreAddress Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedDeliveryOption.StoreAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.selecteddeliveryoption.storeaddress(v=AX.60)
ms:contentKeyID: 65317809
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedDeliveryOption.StoreAddress
dev_langs:
- CSharp
- C++
- VB
---

# StoreAddress Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StoreAddress As StoreProductAvailability
    Get
    Set
'Usage
Dim instance As SelectedDeliveryOption
Dim value As StoreProductAvailability

value = instance.StoreAddress

instance.StoreAddress = value
```

``` csharp
[DataMemberAttribute]
public StoreProductAvailability StoreAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property StoreProductAvailability^ StoreAddress {
    StoreProductAvailability^ get ();
    void set (StoreProductAvailability^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.StoreProductAvailability](storeproductavailability-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[SelectedDeliveryOption Class](selecteddeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

