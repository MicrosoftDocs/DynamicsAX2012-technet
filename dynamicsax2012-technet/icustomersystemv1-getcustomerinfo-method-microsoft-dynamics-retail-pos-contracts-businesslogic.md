---
title: ICustomerSystemV1.GetCustomerInfo Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: GetCustomerInfo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV1.GetCustomerInfo(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.icustomersystemv1.getcustomerinfo(v=AX.60)
ms:contentKeyID: 47129042
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV1.GetCustomerInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerInfo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer information.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetCustomerInfo ( _
    customerId As String _
) As ICustomer
'Usage
Dim instance As ICustomerSystemV1
Dim customerId As String
Dim returnValue As ICustomer

returnValue = instance.GetCustomerInfo(customerId)
```

``` csharp
ICustomer GetCustomerInfo(
    string customerId
)
```

``` c++
ICustomer^ GetCustomerInfo(
    String^ customerId
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The customer information.  

## See Also

#### Reference

[ICustomerSystemV1 Interface](icustomersystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

