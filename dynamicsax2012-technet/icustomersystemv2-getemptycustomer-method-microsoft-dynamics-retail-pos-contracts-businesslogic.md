---
title: ICustomerSystemV2.GetEmptyCustomer Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: GetEmptyCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV2.GetEmptyCustomer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.icustomersystemv2.getemptycustomer(v=AX.60)
ms:contentKeyID: 49855961
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV2.GetEmptyCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetEmptyCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get a blank/empty customer with the proper Store settings for PriceGroup and TaxGroup

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetEmptyCustomer As ICustomer
'Usage
Dim instance As ICustomerSystemV2
Dim returnValue As ICustomer

returnValue = instance.GetEmptyCustomer()
```

``` csharp
ICustomer GetEmptyCustomer()
```

``` c++
ICustomer^ GetEmptyCustomer()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerSystemV2 Interface](icustomersystemv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

