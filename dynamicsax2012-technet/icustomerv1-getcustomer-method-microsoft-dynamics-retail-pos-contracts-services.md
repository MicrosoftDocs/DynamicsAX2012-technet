---
title: ICustomerV1.GetCustomer Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.GetCustomer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.getcustomer(v=AX.60)
ms:contentKeyID: 47344453
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.GetCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Shows UI to select a customer.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetCustomer As ICustomer
'Usage
Dim instance As ICustomerV1
Dim returnValue As ICustomer

returnValue = instance.GetCustomer()
```

``` csharp
ICustomer GetCustomer()
```

``` c++
ICustomer^ GetCustomer()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The customer if found; otherwise, null.  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

