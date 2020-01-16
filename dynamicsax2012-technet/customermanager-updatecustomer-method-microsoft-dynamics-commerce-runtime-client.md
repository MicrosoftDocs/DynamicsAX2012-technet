---
title: CustomerManager.UpdateCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.UpdateCustomer(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.customermanager.updatecustomer(v=AX.60)
ms:contentKeyID: 49856245
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.UpdateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCustomer Method

Updates the customer record.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateCustomer ( _
    customer As Customer _
) As Customer
'Usage
Dim instance As CustomerManager
Dim customer As Customer
Dim returnValue As Customer

returnValue = instance.UpdateCustomer(customer)
```

``` csharp
public Customer UpdateCustomer(
    Customer customer
)
```

``` c++
public:
Customer^ UpdateCustomer(
    Customer^ customer
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated customer record.  

## See Also

#### Reference

[CustomerManager Class](customermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

