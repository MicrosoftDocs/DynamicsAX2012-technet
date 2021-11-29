---
title: ICustomerSystemV3.CreateCustomerFromParty Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateCustomerFromParty Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV3.CreateCustomerFromParty(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.icustomersystemv3.createcustomerfromparty(v=AX.60)
ms:contentKeyID: 62203131
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV3.CreateCustomerFromParty
dev_langs:
- CSharp
- C++
- VB
---

# CreateCustomerFromParty Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer info cross company.

Creates customer from different company if it doesn't exist in the current one.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateCustomerFromParty ( _
    partyNumber As String _
) As ICustomer
'Usage
Dim instance As ICustomerSystemV3
Dim partyNumber As String
Dim returnValue As ICustomer

returnValue = instance.CreateCustomerFromParty(partyNumber)
```

``` csharp
ICustomer CreateCustomerFromParty(
    string partyNumber
)
```

``` c++
ICustomer^ CreateCustomerFromParty(
    String^ partyNumber
)
```

#### Parameters

  - partyNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The customer info.  

## See Also

#### Reference

[ICustomerSystemV3 Interface](icustomersystemv3-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

