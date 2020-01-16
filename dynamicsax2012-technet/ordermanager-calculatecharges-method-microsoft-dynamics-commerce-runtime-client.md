---
title: OrderManager.CalculateCharges Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: CalculateCharges Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.CalculateCharges(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.calculatecharges(v=AX.60)
ms:contentKeyID: 62207644
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.CalculateCharges
dev_langs:
- CSharp
- C++
- VB
---

# CalculateCharges Method

Calculate charges for a sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function CalculateCharges ( _
    transaction As SalesTransaction _
) As SalesTransaction
'Usage
Dim instance As OrderManager
Dim transaction As SalesTransaction
Dim returnValue As SalesTransaction

returnValue = instance.CalculateCharges(transaction)
```

``` csharp
public SalesTransaction CalculateCharges(
    SalesTransaction transaction
)
```

``` c++
public:
SalesTransaction^ CalculateCharges(
    SalesTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The sales transaction with calculated charges.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

