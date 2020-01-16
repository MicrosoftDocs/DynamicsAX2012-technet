---
title: ICustomerV1.SearchShippingAddress Method (IPosTransaction) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SearchShippingAddress Method (IPosTransaction)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.SearchShippingAddress(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.searchshippingaddress(v=AX.60)
ms:contentKeyID: 47344107
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SearchShippingAddress Method (IPosTransaction)

Searches for the customer shipping address and add it to the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SearchShippingAddress ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ICustomerV1
Dim posTransaction As IPosTransaction

instance.SearchShippingAddress(posTransaction)
```

``` csharp
void SearchShippingAddress(
    IPosTransaction posTransaction
)
```

``` c++
void SearchShippingAddress(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[SearchShippingAddress Overload](icustomerv1-searchshippingaddress-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

