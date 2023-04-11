---
title: GetItemAvailableQuantitiesRequest.ItemUnits Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ItemUnits Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailableQuantitiesRequest.ItemUnits
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitemavailablequantitiesrequest.itemunits(v=AX.60)
ms:contentKeyID: 49837904
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailableQuantitiesRequest.ItemUnits
dev_langs:
- CSharp
- C++
- VB
---

# ItemUnits Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the item and unit of measure combinations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemUnits As IEnumerable(Of ItemUnit)
    Get
    Set
'Usage
Dim instance As GetItemAvailableQuantitiesRequest
Dim value As IEnumerable(Of ItemUnit)

value = instance.ItemUnits

instance.ItemUnits = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemUnit> ItemUnits { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemUnit^>^ ItemUnits {
    IEnumerable<ItemUnit^>^ get ();
    void set (IEnumerable<ItemUnit^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemUnit](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The item quantities.  

## See Also

#### Reference

[GetItemAvailableQuantitiesRequest Class](getitemavailablequantitiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

