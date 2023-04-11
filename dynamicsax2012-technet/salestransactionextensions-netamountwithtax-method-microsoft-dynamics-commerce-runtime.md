---
title: SalesTransactionExtensions.NetAmountWithTax Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: NetAmountWithTax Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.NetAmountWithTax(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.salestransactionextensions.netamountwithtax(v=AX.60)
ms:contentKeyID: 49828495
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.NetAmountWithTax
dev_langs:
- CSharp
- C++
- VB
---

# NetAmountWithTax Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The line amount including tax (whether tax-exclusive or inclusive scenario).

Add exclusive taxes to NetAmount, inclusive taxes are already included in NetAmount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function NetAmountWithTax ( _
    line As SalesLine _
) As Decimal
'Usage
Dim line As SalesLine
Dim returnValue As Decimal

returnValue = line.NetAmountWithTax()
```

``` csharp
public static decimal NetAmountWithTax(
    this SalesLine line
)
```

``` c++
[ExtensionAttribute]
public:
static Decimal NetAmountWithTax(
    SalesLine^ line
)
```

#### Parameters

  - line  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The net amount including taxes.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[SalesTransactionExtensions Class](salestransactionextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

