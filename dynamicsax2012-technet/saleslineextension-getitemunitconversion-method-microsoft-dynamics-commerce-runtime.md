---
title: SalesLineExtension.GetItemUnitConversion Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetItemUnitConversion Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SalesLineExtension.GetItemUnitConversion(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.saleslineextension.getitemunitconversion(v=AX.60)
ms:contentKeyID: 62207708
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.SalesLineExtension.GetItemUnitConversion
dev_langs:
- CSharp
- C++
- VB
---

# GetItemUnitConversion Method

Gets the item unit conversion given the sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetItemUnitConversion ( _
    salesLine As SalesLine _
) As ItemUnitConversion
'Usage
Dim salesLine As SalesLine
Dim returnValue As ItemUnitConversion

returnValue = salesLine.GetItemUnitConversion()
```

``` csharp
public static ItemUnitConversion GetItemUnitConversion(
    this SalesLine salesLine
)
```

``` c++
[ExtensionAttribute]
public:
static ItemUnitConversion^ GetItemUnitConversion(
    SalesLine^ salesLine
)
```

#### Parameters

  - salesLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion](itemunitconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The item unit conversion.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[SalesLineExtension Class](saleslineextension-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

