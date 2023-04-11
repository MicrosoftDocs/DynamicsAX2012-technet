---
title: DataValidationErrors.DepositOverrideMustNotBeGreaterThanTotalAmount Field (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DepositOverrideMustNotBeGreaterThanTotalAmount Field
ms:assetid: F:Microsoft.Dynamics.Commerce.Runtime.DataValidationErrors.DepositOverrideMustNotBeGreaterThanTotalAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datavalidationerrors.depositoverridemustnotbegreaterthantotalamount(v=AX.60)
ms:contentKeyID: 62208937
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataValidationErrors.DepositOverrideMustNotBeGreaterThanTotalAmount
dev_langs:
- CSharp
- C++
- VB
---

# DepositOverrideMustNotBeGreaterThanTotalAmount Field


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates that the provided deposit override amount on order creation/edition is not valid. It must be less or equal than the transaction total.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly DepositOverrideMustNotBeGreaterThanTotalAmount As String
'Usage
Dim value As String

value = DataValidationErrors.DepositOverrideMustNotBeGreaterThanTotalAmount
```

``` csharp
public static readonly string DepositOverrideMustNotBeGreaterThanTotalAmount
```

``` c++
public:
static initonly String^ DepositOverrideMustNotBeGreaterThanTotalAmount
```

## See Also

#### Reference

[DataValidationErrors Class](datavalidationerrors-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

