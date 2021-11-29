---
title: SalesTransactionExtensions.ChargesTotal Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ChargesTotal Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.ChargesTotal(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.salestransactionextensions.chargestotal(v=AX.60)
ms:contentKeyID: 49848679
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.ChargesTotal
dev_langs:
- CSharp
- C++
- VB
---

# ChargesTotal Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the sum of all charges on transaction and lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ChargesTotal ( _
    transaction As SalesTransaction _
) As Decimal
'Usage
Dim transaction As SalesTransaction
Dim returnValue As Decimal

returnValue = transaction.ChargesTotal()
```

``` csharp
public static decimal ChargesTotal(
    this SalesTransaction transaction
)
```

``` c++
[ExtensionAttribute]
public:
static Decimal ChargesTotal(
    SalesTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The charges total.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[SalesTransactionExtensions Class](salestransactionextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

