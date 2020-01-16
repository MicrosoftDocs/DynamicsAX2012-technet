---
title: IPinPadV1.BeginTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: BeginTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPinPadV1.BeginTransaction(System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ipinpadv1.begintransaction(v=AX.60)
ms:contentKeyID: 47343857
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPinPadV1.BeginTransaction
dev_langs:
- CSharp
- C++
- VB
---

# BeginTransaction Method

Begins PinPad transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub BeginTransaction ( _
    amount As Decimal, _
    accountNumber As String _
)
'Usage
Dim instance As IPinPadV1
Dim amount As Decimal
Dim accountNumber As String

instance.BeginTransaction(amount, accountNumber)
```

``` csharp
void BeginTransaction(
    decimal amount,
    string accountNumber
)
```

``` c++
void BeginTransaction(
    Decimal amount, 
    String^ accountNumber
)
```

#### Parameters

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IPinPadV1 Interface](ipinpadv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

