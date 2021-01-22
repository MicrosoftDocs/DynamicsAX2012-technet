---
title: CartDeliveryPreferences Constructor (IEnumerable(DeliveryPreferenceType), IEnumerable(LineDeliveryPreference)) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CartDeliveryPreferences Constructor (IEnumerable(DeliveryPreferenceType), IEnumerable(LineDeliveryPreference))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartDeliveryPreferences.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryPreferenceType},System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDeliveryPreference})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartdeliverypreferences.cartdeliverypreferences(v=AX.60)
ms:contentKeyID: 65319730
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CartDeliveryPreferences Constructor (IEnumerable(DeliveryPreferenceType), IEnumerable(LineDeliveryPreference))

Initializes a new instance of the [CartDeliveryPreferences](cartdeliverypreferences-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    headerLevelPreferences As IEnumerable(Of DeliveryPreferenceType), _
    lineLevelPreferences As IEnumerable(Of LineDeliveryPreference) _
)
'Usage
Dim headerLevelPreferences As IEnumerable(Of DeliveryPreferenceType)
Dim lineLevelPreferences As IEnumerable(Of LineDeliveryPreference)

Dim instance As New CartDeliveryPreferences(headerLevelPreferences, _
    lineLevelPreferences)
```

``` csharp
public CartDeliveryPreferences(
    IEnumerable<DeliveryPreferenceType> headerLevelPreferences,
    IEnumerable<LineDeliveryPreference> lineLevelPreferences
)
```

``` c++
public:
CartDeliveryPreferences(
    IEnumerable<DeliveryPreferenceType>^ headerLevelPreferences, 
    IEnumerable<LineDeliveryPreference^>^ lineLevelPreferences
)
```

#### Parameters

  - headerLevelPreferences  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DeliveryPreferenceType](deliverypreferencetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - lineLevelPreferences  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[LineDeliveryPreference](linedeliverypreference-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CartDeliveryPreferences Class](cartdeliverypreferences-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[CartDeliveryPreferences Overload](cartdeliverypreferences-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

