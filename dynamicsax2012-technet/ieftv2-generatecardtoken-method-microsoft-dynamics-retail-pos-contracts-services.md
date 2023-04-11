---
title: IEFTV2.GenerateCardToken Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GenerateCardToken Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTV2.GenerateCardToken(System.Decimal,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ieftv2.generatecardtoken(v=AX.60)
ms:contentKeyID: 49839121
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTV2.GenerateCardToken
dev_langs:
- CSharp
- C++
- VB
---

# GenerateCardToken Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Generate Credit card token is created by a payment SDK processor and represents the credit card number and is used within AX to process customer order securely Needs to internally set the posTransaction.CreditCardToken

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GenerateCardToken ( _
    amount As Decimal, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IEFTV2
Dim amount As Decimal
Dim posTransaction As IPosTransaction

instance.GenerateCardToken(amount, posTransaction)
```

``` csharp
void GenerateCardToken(
    decimal amount,
    IPosTransaction posTransaction
)
```

``` c++
void GenerateCardToken(
    Decimal amount, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IEFTV2 Interface](ieftv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

