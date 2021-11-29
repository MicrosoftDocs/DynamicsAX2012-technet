---
title: ICustomerV1.AddNew Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddNew Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.AddNew
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.addnew(v=AX.60)
ms:contentKeyID: 47344303
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.AddNew
dev_langs:
- CSharp
- C++
- VB
---

# AddNew Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Registers information about a new customer into the database.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AddNew As ICustomer
'Usage
Dim instance As ICustomerV1
Dim returnValue As ICustomer

returnValue = instance.AddNew()
```

``` csharp
ICustomer AddNew()
```

``` c++
ICustomer^ AddNew()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The new customer if it is successful; otherwise, null  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

