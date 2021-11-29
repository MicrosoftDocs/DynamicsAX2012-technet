---
title: ItemAvailableQuantityExtension.GetItem Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetItem Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ItemAvailableQuantityExtension.GetItem(Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailableQuantity)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.itemavailablequantityextension.getitem(v=AX.60)
ms:contentKeyID: 65321240
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ItemAvailableQuantityExtension.GetItem
dev_langs:
- CSharp
- C++
- VB
---

# GetItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item variant inventory dimension given the item available quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetItem ( _
    itemAvailableQuantity As ItemAvailableQuantity _
) As ItemVariantInventoryDimension
'Usage
Dim itemAvailableQuantity As ItemAvailableQuantity
Dim returnValue As ItemVariantInventoryDimension

returnValue = itemAvailableQuantity.GetItem()
```

``` csharp
public static ItemVariantInventoryDimension GetItem(
    this ItemAvailableQuantity itemAvailableQuantity
)
```

``` c++
[ExtensionAttribute]
public:
static ItemVariantInventoryDimension^ GetItem(
    ItemAvailableQuantity^ itemAvailableQuantity
)
```

#### Parameters

  - itemAvailableQuantity  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailableQuantity](itemavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The item variant inventory dimension.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [ItemAvailableQuantity](itemavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[ItemAvailableQuantityExtension Class](itemavailablequantityextension-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

