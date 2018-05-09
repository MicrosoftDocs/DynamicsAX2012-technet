---
title: LineDeliveryOption Constructor (String, Collection(DeliveryOption)) (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: LineDeliveryOption Constructor (String, Collection(DeliveryOption))
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LineDeliveryOption.#ctor(System.String,System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.DeliveryOption})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.linedeliveryoption.linedeliveryoption(v=AX.60)
ms:contentKeyID: 65316432
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# LineDeliveryOption Constructor (String, Collection(DeliveryOption))

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    lineId As String, _
    deliveryOptions As Collection(Of DeliveryOption) _
)
'Usage
Dim lineId As String
Dim deliveryOptions As Collection(Of DeliveryOption)

Dim instance As New LineDeliveryOption(lineId, _
    deliveryOptions)
```

``` csharp
public LineDeliveryOption(
    string lineId,
    Collection<DeliveryOption> deliveryOptions
)
```

``` c++
public:
LineDeliveryOption(
    String^ lineId, 
    Collection<DeliveryOption^>^ deliveryOptions
)
```

#### Parameters

  - lineId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - deliveryOptions  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[LineDeliveryOption Class](linedeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[LineDeliveryOption Overload](linedeliveryoption-constructor-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

