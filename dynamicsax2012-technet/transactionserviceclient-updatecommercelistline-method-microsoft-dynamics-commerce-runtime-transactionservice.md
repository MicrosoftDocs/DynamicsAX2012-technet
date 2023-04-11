---
title: TransactionServiceClient.UpdateCommerceListLine Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: UpdateCommerceListLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UpdateCommerceListLine(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.updatecommercelistline(v=AX.60)
ms:contentKeyID: 62207243
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UpdateCommerceListLine
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCommerceListLine Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Update a commerce list line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateCommerceListLine ( _
    commerceListLine As CommerceListLine _
) As CommerceListLine
'Usage
Dim instance As TransactionServiceClient
Dim commerceListLine As CommerceListLine
Dim returnValue As CommerceListLine

returnValue = instance.UpdateCommerceListLine(commerceListLine)
```

``` csharp
public CommerceListLine UpdateCommerceListLine(
    CommerceListLine commerceListLine
)
```

``` c++
public:
CommerceListLine^ UpdateCommerceListLine(
    CommerceListLine^ commerceListLine
)
```

#### Parameters

  - commerceListLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the commerce list line object with a record id.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

