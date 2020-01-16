---
title: GetItemAvailabilitiesRequest.ItemQuantities Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ItemQuantities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailabilitiesRequest.ItemQuantities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitemavailabilitiesrequest.itemquantities(v=AX.60)
ms:contentKeyID: 49822649
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailabilitiesRequest.ItemQuantities
dev_langs:
- CSharp
- C++
- VB
---

# ItemQuantities Property

Gets or sets the item and quantity combinations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemQuantities As IEnumerable(Of ItemQuantity)
    Get
    Set
'Usage
Dim instance As GetItemAvailabilitiesRequest
Dim value As IEnumerable(Of ItemQuantity)

value = instance.ItemQuantities

instance.ItemQuantities = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemQuantity> ItemQuantities { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemQuantity^>^ ItemQuantities {
    IEnumerable<ItemQuantity^>^ get ();
    void set (IEnumerable<ItemQuantity^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemQuantity](itemquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The item quantities.  

## See Also

#### Reference

[GetItemAvailabilitiesRequest Class](getitemavailabilitiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

