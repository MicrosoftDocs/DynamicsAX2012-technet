---
title: SalesTransactionExtensions.IsEligibleForDiscount Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: IsEligibleForDiscount Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.IsEligibleForDiscount(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.salestransactionextensions.iseligiblefordiscount(v=AX.60)
ms:contentKeyID: 49832784
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions.IsEligibleForDiscount
dev_langs:
- CSharp
- C++
- VB
---

# IsEligibleForDiscount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

True if this sales line may be valid for discounting (i.e. hasn't been voided or had a price override).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function IsEligibleForDiscount ( _
    line As SalesLine _
) As Boolean
'Usage
Dim line As SalesLine
Dim returnValue As Boolean

returnValue = line.IsEligibleForDiscount()
```

``` csharp
public static bool IsEligibleForDiscount(
    this SalesLine line
)
```

``` c++
[ExtensionAttribute]
public:
static bool IsEligibleForDiscount(
    SalesLine^ line
)
```

#### Parameters

  - line  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether the sales line may be valid for discounting.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[SalesTransactionExtensions Class](salestransactionextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

