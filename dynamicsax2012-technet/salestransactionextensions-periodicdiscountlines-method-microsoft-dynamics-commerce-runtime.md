---
title: SalesTransactionExtensions.PeriodicDiscountLines Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: PeriodicDiscountLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.PeriodicDiscountLines(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.salestransactionextensions.periodicdiscountlines(v=AX.60)
ms:contentKeyID: 49855952
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.PeriodicDiscountLines
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicDiscountLines Method

A collection of all periodic discounts belonging to the sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function PeriodicDiscountLines ( _
    line As SalesLine _
) As ICollection(Of DiscountLine)
'Usage
Dim line As SalesLine
Dim returnValue As ICollection(Of DiscountLine)

returnValue = line.PeriodicDiscountLines()
```

``` csharp
public static ICollection<DiscountLine> PeriodicDiscountLines(
    this SalesLine line
)
```

``` c++
[ExtensionAttribute]
public:
static ICollection<DiscountLine^>^ PeriodicDiscountLines(
    SalesLine^ line
)
```

#### Parameters

  - line  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[DiscountLine](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of periodic discount lines.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[SalesTransactionExtensions Class](salestransactionextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

