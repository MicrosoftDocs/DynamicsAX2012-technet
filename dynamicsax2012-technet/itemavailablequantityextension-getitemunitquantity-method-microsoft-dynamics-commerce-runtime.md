---
title: ItemAvailableQuantityExtension.GetItemUnitQuantity Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetItemUnitQuantity Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ItemAvailableQuantityExtension.GetItemUnitQuantity(Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailableQuantity)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.itemavailablequantityextension.getitemunitquantity(v=AX.60)
ms:contentKeyID: 65315816
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ItemAvailableQuantityExtension.GetItemUnitQuantity
dev_langs:
- CSharp
- C++
- VB
---

# GetItemUnitQuantity Method

Gets the item unit quantity given the item available quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetItemUnitQuantity ( _
    itemAvailableQuantity As ItemAvailableQuantity _
) As ItemUnitQuantity
'Usage
Dim itemAvailableQuantity As ItemAvailableQuantity
Dim returnValue As ItemUnitQuantity

returnValue = itemAvailableQuantity.GetItemUnitQuantity()
```

``` csharp
public static ItemUnitQuantity GetItemUnitQuantity(
    this ItemAvailableQuantity itemAvailableQuantity
)
```

``` c++
[ExtensionAttribute]
public:
static ItemUnitQuantity^ GetItemUnitQuantity(
    ItemAvailableQuantity^ itemAvailableQuantity
)
```

#### Parameters

  - itemAvailableQuantity  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailableQuantity](itemavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitQuantity](itemunitquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The item unit quantity.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [ItemAvailableQuantity](itemavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[ItemAvailableQuantityExtension Class](itemavailablequantityextension-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

