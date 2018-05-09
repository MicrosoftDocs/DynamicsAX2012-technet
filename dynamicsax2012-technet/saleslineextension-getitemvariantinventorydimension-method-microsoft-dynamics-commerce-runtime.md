---
title: SalesLineExtension.GetItemVariantInventoryDimension Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetItemVariantInventoryDimension Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SalesLineExtension.GetItemVariantInventoryDimension(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.saleslineextension.getitemvariantinventorydimension(v=AX.60)
ms:contentKeyID: 62214526
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.SalesLineExtension.GetItemVariantInventoryDimension
dev_langs:
- CSharp
- C++
- VB
---

# GetItemVariantInventoryDimension Method

Gets the item variant inventory dimension given the sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetItemVariantInventoryDimension ( _
    salesLine As SalesLine _
) As ItemVariantInventoryDimension
'Usage
Dim salesLine As SalesLine
Dim returnValue As ItemVariantInventoryDimension

returnValue = salesLine.GetItemVariantInventoryDimension()
```

``` csharp
public static ItemVariantInventoryDimension GetItemVariantInventoryDimension(
    this SalesLine salesLine
)
```

``` c++
[ExtensionAttribute]
public:
static ItemVariantInventoryDimension^ GetItemVariantInventoryDimension(
    SalesLine^ salesLine
)
```

#### Parameters

  - salesLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The item variant inventory dimension.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[SalesLineExtension Class](saleslineextension-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

