---
title: ItemQuantityExtensions.GetItem Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetItem Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ItemQuantityExtensions.GetItem(Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemQuantity)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.itemquantityextensions.getitem(v=AX.60)
ms:contentKeyID: 49853583
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ItemQuantityExtensions.GetItem
dev_langs:
- CSharp
- C++
- VB
---

# GetItem Method

Gets the item variant inventory dimension given the item quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetItem ( _
    itemQuantity As ItemQuantity _
) As ItemVariantInventoryDimension
'Usage
Dim itemQuantity As ItemQuantity
Dim returnValue As ItemVariantInventoryDimension

returnValue = itemQuantity.GetItem()
```

``` csharp
public static ItemVariantInventoryDimension GetItem(
    this ItemQuantity itemQuantity
)
```

``` c++
[ExtensionAttribute]
public:
static ItemVariantInventoryDimension^ GetItem(
    ItemQuantity^ itemQuantity
)
```

#### Parameters

  - itemQuantity  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemQuantity](itemquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The item variant inventory dimension.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [ItemQuantity](itemquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[ItemQuantityExtensions Class](itemquantityextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

