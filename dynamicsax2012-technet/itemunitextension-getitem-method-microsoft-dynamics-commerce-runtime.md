---
title: ItemUnitExtension.GetItem Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetItem Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ItemUnitExtension.GetItem(Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.itemunitextension.getitem(v=AX.60)
ms:contentKeyID: 65318902
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ItemUnitExtension.GetItem
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
    itemUnit As ItemUnit _
) As ItemVariantInventoryDimension
'Usage
Dim itemUnit As ItemUnit
Dim returnValue As ItemVariantInventoryDimension

returnValue = itemUnit.GetItem()
```

``` csharp
public static ItemVariantInventoryDimension GetItem(
    this ItemUnit itemUnit
)
```

``` c++
[ExtensionAttribute]
public:
static ItemVariantInventoryDimension^ GetItem(
    ItemUnit^ itemUnit
)
```

#### Parameters

  - itemUnit  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The item variant inventory dimension.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [ItemUnit](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[ItemUnitExtension Class](itemunitextension-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

