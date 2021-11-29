---
title: LineDeliveryPreference Constructor (String, IEnumerable(DeliveryPreferenceType)) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDeliveryPreference Constructor (String, IEnumerable(DeliveryPreferenceType))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDeliveryPreference.#ctor(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryPreferenceType})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.linedeliverypreference.linedeliverypreference(v=AX.60)
ms:contentKeyID: 65320614
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# LineDeliveryPreference Constructor (String, IEnumerable(DeliveryPreferenceType))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [LineDeliveryPreference](linedeliverypreference-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    lineId As String, _
    deliveryPreferences As IEnumerable(Of DeliveryPreferenceType) _
)
'Usage
Dim lineId As String
Dim deliveryPreferences As IEnumerable(Of DeliveryPreferenceType)

Dim instance As New LineDeliveryPreference(lineId, _
    deliveryPreferences)
```

``` csharp
public LineDeliveryPreference(
    string lineId,
    IEnumerable<DeliveryPreferenceType> deliveryPreferences
)
```

``` c++
public:
LineDeliveryPreference(
    String^ lineId, 
    IEnumerable<DeliveryPreferenceType>^ deliveryPreferences
)
```

#### Parameters

  - lineId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - deliveryPreferences  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DeliveryPreferenceType](deliverypreferencetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[LineDeliveryPreference Class](linedeliverypreference-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[LineDeliveryPreference Overload](linedeliverypreference-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

