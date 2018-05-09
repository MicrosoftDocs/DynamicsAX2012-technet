---
title: ItemAvailabilityExtension.GetItem Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetItem Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ItemAvailabilityExtension.GetItem(Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.itemavailabilityextension.getitem(v=AX.60)
ms:contentKeyID: 65319940
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ItemAvailabilityExtension.GetItem
dev_langs:
- CSharp
- C++
- VB
---

# GetItem Method

Gets the item variant inventory dimension given the item availability.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetItem ( _
    itemAvailability As ItemAvailability _
) As ItemVariantInventoryDimension
'Usage
Dim itemAvailability As ItemAvailability
Dim returnValue As ItemVariantInventoryDimension

returnValue = itemAvailability.GetItem()
```

``` csharp
public static ItemVariantInventoryDimension GetItem(
    this ItemAvailability itemAvailability
)
```

``` c++
[ExtensionAttribute]
public:
static ItemVariantInventoryDimension^ GetItem(
    ItemAvailability^ itemAvailability
)
```

#### Parameters

  - itemAvailability  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The item variant inventory dimension.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[ItemAvailabilityExtension Class](itemavailabilityextension-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

