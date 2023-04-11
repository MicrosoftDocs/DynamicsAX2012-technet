---
title: UnableToDetermineQuantityNotification.InventVariantIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventVariantIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToDetermineQuantityNotification.InventVariantIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unabletodeterminequantitynotification.inventvariantids(v=AX.60)
ms:contentKeyID: 65323091
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToDetermineQuantityNotification.InventVariantIds
dev_langs:
- CSharp
- C++
- VB
---

# InventVariantIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the list of inventory variant dimension Ids for the product runtime can not find the quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventVariantIds As IEnumerable(Of ItemVariantInventoryDimension)
    Get
    Private Set
'Usage
Dim instance As UnableToDetermineQuantityNotification
Dim value As IEnumerable(Of ItemVariantInventoryDimension)

value = instance.InventVariantIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemVariantInventoryDimension> InventVariantIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemVariantInventoryDimension^>^ InventVariantIds {
    IEnumerable<ItemVariantInventoryDimension^>^ get ();
    private: void set (IEnumerable<ItemVariantInventoryDimension^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[UnableToDetermineQuantityNotification Class](unabletodeterminequantitynotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

