---
title: GetItemAvailabilitiesByItemQuantitiesServiceRequest.ItemQuantities Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ItemQuantities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemQuantitiesServiceRequest.ItemQuantities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailabilitiesbyitemquantitiesservicerequest.itemquantities(v=AX.60)
ms:contentKeyID: 62213295
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemQuantitiesServiceRequest.ItemQuantities
dev_langs:
- CSharp
- C++
- VB
---

# ItemQuantities Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of item and quantities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemQuantities As IEnumerable(Of ItemQuantity)
    Get
    Private Set
'Usage
Dim instance As GetItemAvailabilitiesByItemQuantitiesServiceRequest
Dim value As IEnumerable(Of ItemQuantity)

value = instance.ItemQuantities
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemQuantity> ItemQuantities { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemQuantity^>^ ItemQuantities {
    IEnumerable<ItemQuantity^>^ get ();
    private: void set (IEnumerable<ItemQuantity^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemQuantity](itemquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetItemAvailabilitiesByItemQuantitiesServiceRequest Class](getitemavailabilitiesbyitemquantitiesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

