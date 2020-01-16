---
title: GetItemAvailableQuantitiesResponse.ItemAvailableQuantities Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ItemAvailableQuantities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailableQuantitiesResponse.ItemAvailableQuantities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitemavailablequantitiesresponse.itemavailablequantities(v=AX.60)
ms:contentKeyID: 49843500
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailableQuantitiesResponse.ItemAvailableQuantities
dev_langs:
- CSharp
- C++
- VB
---

# ItemAvailableQuantities Property

Gets the collection of item available quantities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemAvailableQuantities As ReadOnlyCollection(Of ItemAvailableQuantity)
    Get
    Private Set
'Usage
Dim instance As GetItemAvailableQuantitiesResponse
Dim value As ReadOnlyCollection(Of ItemAvailableQuantity)

value = instance.ItemAvailableQuantities
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ItemAvailableQuantity> ItemAvailableQuantities { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ItemAvailableQuantity^>^ ItemAvailableQuantities {
    ReadOnlyCollection<ItemAvailableQuantity^>^ get ();
    private: void set (ReadOnlyCollection<ItemAvailableQuantity^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ItemAvailableQuantity](itemavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetItemAvailableQuantitiesResponse Class](getitemavailablequantitiesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

