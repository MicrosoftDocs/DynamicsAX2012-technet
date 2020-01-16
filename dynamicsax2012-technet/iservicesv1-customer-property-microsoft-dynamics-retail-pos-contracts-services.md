---
title: IServicesV1.Customer Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Customer Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.Customer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iservicesv1.customer(v=AX.60)
ms:contentKeyID: 47344491
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.Customer
dev_langs:
- CSharp
- C++
- VB
---

# Customer Property

Customer service

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Customer As ICustomer
    Get
'Usage
Dim instance As IServicesV1
Dim value As ICustomer

value = instance.Customer
```

``` csharp
ICustomer Customer { get; }
```

``` c++
property ICustomer^ Customer {
    ICustomer^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-services.md) .  

## See Also

#### Reference

[IServicesV1 Interface](iservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

