---
title: StoreProductAvailabilityResponse.Stores Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: Stores Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreProductAvailabilityResponse.Stores
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.storeproductavailabilityresponse.stores(v=AX.60)
ms:contentKeyID: 65316617
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StoreProductAvailabilityResponse.Stores
dev_langs:
- CSharp
- C++
- VB
---

# Stores Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Stores As Collection(Of StoreProductAvailability)
    Get
    Friend Set
'Usage
Dim instance As StoreProductAvailabilityResponse
Dim value As Collection(Of StoreProductAvailability)

value = instance.Stores
```

``` csharp
[DataMemberAttribute]
public Collection<StoreProductAvailability> Stores { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<StoreProductAvailability^>^ Stores {
    Collection<StoreProductAvailability^>^ get ();
    internal: void set (Collection<StoreProductAvailability^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[StoreProductAvailability](storeproductavailability-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[StoreProductAvailabilityResponse Class](storeproductavailabilityresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

