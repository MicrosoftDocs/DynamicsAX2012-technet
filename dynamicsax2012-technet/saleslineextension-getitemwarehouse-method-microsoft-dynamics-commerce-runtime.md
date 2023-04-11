---
title: SalesLineExtension.GetItemWarehouse Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetItemWarehouse Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SalesLineExtension.GetItemWarehouse(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.saleslineextension.getitemwarehouse(v=AX.60)
ms:contentKeyID: 62212137
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.SalesLineExtension.GetItemWarehouse
dev_langs:
- CSharp
- C++
- VB
---

# GetItemWarehouse Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item warehouse combination given the sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetItemWarehouse ( _
    salesLine As SalesLine _
) As ItemWarehouse
'Usage
Dim salesLine As SalesLine
Dim returnValue As ItemWarehouse

returnValue = salesLine.GetItemWarehouse()
```

``` csharp
public static ItemWarehouse GetItemWarehouse(
    this SalesLine salesLine
)
```

``` c++
[ExtensionAttribute]
public:
static ItemWarehouse^ GetItemWarehouse(
    SalesLine^ salesLine
)
```

#### Parameters

  - salesLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemWarehouse](itemwarehouse-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The item warehouse combination.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[SalesLineExtension Class](saleslineextension-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

