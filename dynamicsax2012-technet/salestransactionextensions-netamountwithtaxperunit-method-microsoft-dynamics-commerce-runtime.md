---
title: SalesTransactionExtensions.NetAmountWithTaxPerUnit Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: NetAmountWithTaxPerUnit Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.NetAmountWithTaxPerUnit(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.salestransactionextensions.netamountwithtaxperunit(v=AX.60)
ms:contentKeyID: 62206688
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.NetAmountWithTaxPerUnit
dev_langs:
- CSharp
- C++
- VB
---

# NetAmountWithTaxPerUnit Method

The line amount including tax (whether tax-exclusive or inclusive scenario) per unit.

Add exclusive taxes to NetAmount, inclusive taxes are already included in NetAmount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function NetAmountWithTaxPerUnit ( _
    line As SalesLine _
) As Decimal
'Usage
Dim line As SalesLine
Dim returnValue As Decimal

returnValue = line.NetAmountWithTaxPerUnit()
```

``` csharp
public static decimal NetAmountWithTaxPerUnit(
    this SalesLine line
)
```

``` c++
[ExtensionAttribute]
public:
static Decimal NetAmountWithTaxPerUnit(
    SalesLine^ line
)
```

#### Parameters

  - line  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The net amount including taxes.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[SalesTransactionExtensions Class](salestransactionextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

