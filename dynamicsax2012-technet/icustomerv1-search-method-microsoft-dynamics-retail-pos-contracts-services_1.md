---
title: ICustomerV1.Search Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Search Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.Search
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.search(v=AX.60)
ms:contentKeyID: 47344039
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Search Method

Searches for a customer and adds the customer to the current transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Search As ICustomer
'Usage
Dim instance As ICustomerV1
Dim returnValue As ICustomer

returnValue = instance.Search()
```

``` csharp
ICustomer Search()
```

``` c++
ICustomer^ Search()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The customer if found; otherwise, null.  

## Remarks

This method is triggered by the customer search operation

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Search Overload](icustomerv1-search-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

