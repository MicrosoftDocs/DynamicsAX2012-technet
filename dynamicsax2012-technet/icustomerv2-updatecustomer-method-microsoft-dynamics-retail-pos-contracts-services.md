---
title: ICustomerV2.UpdateCustomer Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: UpdateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV2.UpdateCustomer(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv2.updatecustomer(v=AX.60)
ms:contentKeyID: 50496970
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV2.UpdateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the customer information in the database

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function UpdateCustomer ( _
    customerId As String _
) As ICustomer
'Usage
Dim instance As ICustomerV2
Dim customerId As String
Dim returnValue As ICustomer

returnValue = instance.UpdateCustomer(customerId)
```

``` csharp
ICustomer UpdateCustomer(
    string customerId
)
```

``` c++
ICustomer^ UpdateCustomer(
    String^ customerId
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns the updated customer if operations is successful. Null otherwise  

## See Also

#### Reference

[ICustomerV2 Interface](icustomerv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

