---
title: ICustomerV1.AddShippingAddress Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddShippingAddress Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.AddShippingAddress(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.addshippingaddress(v=AX.60)
ms:contentKeyID: 47344194
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.AddShippingAddress
dev_langs:
- CSharp
- C++
- VB
---

# AddShippingAddress Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds a new shipping address for the current customer on the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddShippingAddress ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ICustomerV1
Dim posTransaction As IPosTransaction

instance.AddShippingAddress(posTransaction)
```

``` csharp
void AddShippingAddress(
    IPosTransaction posTransaction
)
```

``` c++
void AddShippingAddress(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

