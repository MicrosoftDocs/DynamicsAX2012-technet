---
title: GetDeliveryOptionsResponse Constructor (IEnumerable(DeliveryOption), IEnumerable(SalesLineDeliveryOption)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetDeliveryOptionsResponse Constructor (IEnumerable(DeliveryOption), IEnumerable(SalesLineDeliveryOption))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryOptionsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption},System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineDeliveryOption})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getdeliveryoptionsresponse.getdeliveryoptionsresponse(v=AX.60)
ms:contentKeyID: 49846346
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDeliveryOptionsResponse Constructor (IEnumerable(DeliveryOption), IEnumerable(SalesLineDeliveryOption))

Initializes a new instance of the [GetDeliveryOptionsResponse](getdeliveryoptionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    orderLevelOptions As IEnumerable(Of DeliveryOption), _
    lineLevelOptions As IEnumerable(Of SalesLineDeliveryOption) _
)
'Usage
Dim orderLevelOptions As IEnumerable(Of DeliveryOption)
Dim lineLevelOptions As IEnumerable(Of SalesLineDeliveryOption)

Dim instance As New GetDeliveryOptionsResponse(orderLevelOptions, _
    lineLevelOptions)
```

``` csharp
public GetDeliveryOptionsResponse(
    IEnumerable<DeliveryOption> orderLevelOptions,
    IEnumerable<SalesLineDeliveryOption> lineLevelOptions
)
```

``` c++
public:
GetDeliveryOptionsResponse(
    IEnumerable<DeliveryOption^>^ orderLevelOptions, 
    IEnumerable<SalesLineDeliveryOption^>^ lineLevelOptions
)
```

#### Parameters

  - orderLevelOptions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - lineLevelOptions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLineDeliveryOption](saleslinedeliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetDeliveryOptionsResponse Class](getdeliveryoptionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetDeliveryOptionsResponse Overload](getdeliveryoptionsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

