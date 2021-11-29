---
title: SalesLineDeliveryOption Constructor (String, IEnumerable(DeliveryOption)) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesLineDeliveryOption Constructor (String, IEnumerable(DeliveryOption))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineDeliveryOption.#ctor(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.saleslinedeliveryoption.saleslinedeliveryoption(v=AX.60)
ms:contentKeyID: 49819657
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SalesLineDeliveryOption Constructor (String, IEnumerable(DeliveryOption))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SalesLineDeliveryOption](saleslinedeliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesLineId As String, _
    deliveryOptions As IEnumerable(Of DeliveryOption) _
)
'Usage
Dim salesLineId As String
Dim deliveryOptions As IEnumerable(Of DeliveryOption)

Dim instance As New SalesLineDeliveryOption(salesLineId, _
    deliveryOptions)
```

``` csharp
public SalesLineDeliveryOption(
    string salesLineId,
    IEnumerable<DeliveryOption> deliveryOptions
)
```

``` c++
public:
SalesLineDeliveryOption(
    String^ salesLineId, 
    IEnumerable<DeliveryOption^>^ deliveryOptions
)
```

#### Parameters

  - salesLineId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - deliveryOptions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SalesLineDeliveryOption Class](saleslinedeliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[SalesLineDeliveryOption Overload](saleslinedeliveryoption-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

