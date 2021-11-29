---
title: SalesTransactionExtensions.NetAmountWithNoTax Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: NetAmountWithNoTax Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.NetAmountWithNoTax(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.salestransactionextensions.netamountwithnotax(v=AX.60)
ms:contentKeyID: 49829062
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.NetAmountWithNoTax
dev_langs:
- CSharp
- C++
- VB
---

# NetAmountWithNoTax Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The line amount not including tax (whether tax-exclusive or inclusive scenario).

Any inclusive tax is subtracted from NetAmount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function NetAmountWithNoTax ( _
    line As SalesLine _
) As Decimal
'Usage
Dim line As SalesLine
Dim returnValue As Decimal

returnValue = line.NetAmountWithNoTax()
```

``` csharp
public static decimal NetAmountWithNoTax(
    this SalesLine line
)
```

``` c++
[ExtensionAttribute]
public:
static Decimal NetAmountWithNoTax(
    SalesLine^ line
)
```

#### Parameters

  - line  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The net amount excluding taxes.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[SalesTransactionExtensions Class](salestransactionextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

