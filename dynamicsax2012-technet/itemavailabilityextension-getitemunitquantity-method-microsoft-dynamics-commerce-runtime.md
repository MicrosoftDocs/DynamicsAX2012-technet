---
title: ItemAvailabilityExtension.GetItemUnitQuantity Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetItemUnitQuantity Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ItemAvailabilityExtension.GetItemUnitQuantity(Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.itemavailabilityextension.getitemunitquantity(v=AX.60)
ms:contentKeyID: 65322448
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ItemAvailabilityExtension.GetItemUnitQuantity
dev_langs:
- CSharp
- C++
- VB
---

# GetItemUnitQuantity Method

Gets the item unit quantity given the item availability.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetItemUnitQuantity ( _
    itemAvailability As ItemAvailability _
) As ItemUnitQuantity
'Usage
Dim itemAvailability As ItemAvailability
Dim returnValue As ItemUnitQuantity

returnValue = itemAvailability.GetItemUnitQuantity()
```

``` csharp
public static ItemUnitQuantity GetItemUnitQuantity(
    this ItemAvailability itemAvailability
)
```

``` c++
[ExtensionAttribute]
public:
static ItemUnitQuantity^ GetItemUnitQuantity(
    ItemAvailability^ itemAvailability
)
```

#### Parameters

  - itemAvailability  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitQuantity](itemunitquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The item unit quantity.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[ItemAvailabilityExtension Class](itemavailabilityextension-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

