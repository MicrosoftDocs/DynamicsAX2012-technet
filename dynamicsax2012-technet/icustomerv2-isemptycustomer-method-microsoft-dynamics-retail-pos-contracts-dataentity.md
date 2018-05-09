---
title: ICustomerV2.IsEmptyCustomer Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IsEmptyCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV2.IsEmptyCustomer
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv2.isemptycustomer(v=AX.60)
ms:contentKeyID: 49843058
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV2.IsEmptyCustomer
dev_langs:
- CSharp
- C++
- VB
---

# IsEmptyCustomer Method

Is this an "empty" customer (e.g., has the customer been set)Use customerId as the primary basis to determine if customer is set. Other fields such as name may also be included

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function IsEmptyCustomer As Boolean
'Usage
Dim instance As ICustomerV2
Dim returnValue As Boolean

returnValue = instance.IsEmptyCustomer()
```

``` csharp
bool IsEmptyCustomer()
```

``` c++
bool IsEmptyCustomer()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if default customer from ctor  

## See Also

#### Reference

[ICustomerV2 Interface](icustomerv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

