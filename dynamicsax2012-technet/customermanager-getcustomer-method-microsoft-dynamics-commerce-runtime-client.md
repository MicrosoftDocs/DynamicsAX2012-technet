---
title: CustomerManager.GetCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.GetCustomer(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.customermanager.getcustomer(v=AX.60)
ms:contentKeyID: 49854467
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.GetCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer using the specified customer account number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomer ( _
    customerAccountNumber As String _
) As Customer
'Usage
Dim instance As CustomerManager
Dim customerAccountNumber As String
Dim returnValue As Customer

returnValue = instance.GetCustomer(customerAccountNumber)
```

``` csharp
public Customer GetCustomer(
    string customerAccountNumber
)
```

``` c++
public:
Customer^ GetCustomer(
    String^ customerAccountNumber
)
```

#### Parameters

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The customer record or NULL when no matching record was found.  

## See Also

#### Reference

[CustomerManager Class](customermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

