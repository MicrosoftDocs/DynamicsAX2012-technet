---
title: ICustomerV1.Transactions Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Transactions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.Transactions(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.transactions(v=AX.60)
ms:contentKeyID: 47344514
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.Transactions
dev_langs:
- CSharp
- C++
- VB
---

# Transactions Method

Prints customer transaction this method is triggered by the customer transaction operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub Transactions ( _
    customerId As String _
)
'Usage
Dim instance As ICustomerV1
Dim customerId As String

instance.Transactions(customerId)
```

``` csharp
void Transactions(
    string customerId
)
```

``` c++
void Transactions(
    String^ customerId
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

