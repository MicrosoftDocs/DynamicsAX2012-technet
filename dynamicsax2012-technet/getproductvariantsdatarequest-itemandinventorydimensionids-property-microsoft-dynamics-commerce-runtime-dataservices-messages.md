---
title: GetProductVariantsDataRequest.ItemAndInventoryDimensionIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ItemAndInventoryDimensionIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductVariantsDataRequest.ItemAndInventoryDimensionIds
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductvariantsdatarequest.itemandinventorydimensionids(v=AX.60)
ms:contentKeyID: 65320031
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductVariantsDataRequest.ItemAndInventoryDimensionIds
dev_langs:
- CSharp
- C++
- VB
---

# ItemAndInventoryDimensionIds Property

Gets the collection of item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property ItemAndInventoryDimensionIds As IEnumerable(Of ItemVariantInventoryDimension)
    Get
    Private Set
'Usage
Dim instance As GetProductVariantsDataRequest
Dim value As IEnumerable(Of ItemVariantInventoryDimension)

value = instance.ItemAndInventoryDimensionIds
```

``` csharp
public IEnumerable<ItemVariantInventoryDimension> ItemAndInventoryDimensionIds { get; private set; }
```

``` c++
public:
property IEnumerable<ItemVariantInventoryDimension^>^ ItemAndInventoryDimensionIds {
    IEnumerable<ItemVariantInventoryDimension^>^ get ();
    private: void set (IEnumerable<ItemVariantInventoryDimension^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetProductVariantsDataRequest Class](getproductvariantsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

