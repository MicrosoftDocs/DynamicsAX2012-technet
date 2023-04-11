---
title: GetItemAvailabilitiesByItemsServiceRequest.Items Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Items Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemsServiceRequest.Items
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailabilitiesbyitemsservicerequest.items(v=AX.60)
ms:contentKeyID: 62208806
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemsServiceRequest.Items
dev_langs:
- CSharp
- C++
- VB
---

# Items Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Items As IEnumerable(Of ItemVariantInventoryDimension)
    Get
    Private Set
'Usage
Dim instance As GetItemAvailabilitiesByItemsServiceRequest
Dim value As IEnumerable(Of ItemVariantInventoryDimension)

value = instance.Items
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemVariantInventoryDimension> Items { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemVariantInventoryDimension^>^ Items {
    IEnumerable<ItemVariantInventoryDimension^>^ get ();
    private: void set (IEnumerable<ItemVariantInventoryDimension^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetItemAvailabilitiesByItemsServiceRequest Class](getitemavailabilitiesbyitemsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

