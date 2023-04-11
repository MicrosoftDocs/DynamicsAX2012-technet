---
title: ICustomerV1.SearchShippingAddress Method (ICustomer) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SearchShippingAddress Method (ICustomer)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.SearchShippingAddress(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.searchshippingaddress(v=AX.60)
ms:contentKeyID: 47344195
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SearchShippingAddress Method (ICustomer)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Searches for the customer shipping address.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function SearchShippingAddress ( _
    customer As ICustomer _
) As IAddress
'Usage
Dim instance As ICustomerV1
Dim customer As ICustomer
Dim returnValue As IAddress

returnValue = instance.SearchShippingAddress(customer)
```

``` csharp
IAddress SearchShippingAddress(
    ICustomer customer
)
```

``` c++
IAddress^ SearchShippingAddress(
    ICustomer^ customer
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddress](iaddress-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The customer shipping address.  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[SearchShippingAddress Overload](icustomerv1-searchshippingaddress-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

