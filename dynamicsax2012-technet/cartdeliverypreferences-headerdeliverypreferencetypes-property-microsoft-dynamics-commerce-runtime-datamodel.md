---
title: CartDeliveryPreferences.HeaderDeliveryPreferenceTypes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: HeaderDeliveryPreferenceTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartDeliveryPreferences.HeaderDeliveryPreferenceTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartdeliverypreferences.headerdeliverypreferencetypes(v=AX.60)
ms:contentKeyID: 65315999
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartDeliveryPreferences.HeaderDeliveryPreferenceTypes
dev_langs:
- CSharp
- C++
- VB
---

# HeaderDeliveryPreferenceTypes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of delivery preferences that have been computed for the entire cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property HeaderDeliveryPreferenceTypes As ReadOnlyCollection(Of DeliveryPreferenceType)
    Get
    Private Set
'Usage
Dim instance As CartDeliveryPreferences
Dim value As ReadOnlyCollection(Of DeliveryPreferenceType)

value = instance.HeaderDeliveryPreferenceTypes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<DeliveryPreferenceType> HeaderDeliveryPreferenceTypes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<DeliveryPreferenceType>^ HeaderDeliveryPreferenceTypes {
    ReadOnlyCollection<DeliveryPreferenceType>^ get ();
    private: void set (ReadOnlyCollection<DeliveryPreferenceType>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[DeliveryPreferenceType](deliverypreferencetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The order delivery preferences.  

## See Also

#### Reference

[CartDeliveryPreferences Class](cartdeliverypreferences-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

