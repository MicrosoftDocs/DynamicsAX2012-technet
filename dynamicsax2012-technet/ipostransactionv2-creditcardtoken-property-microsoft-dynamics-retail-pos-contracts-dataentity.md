---
title: IPosTransactionV2.CreditCardToken Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CreditCardToken Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV2.CreditCardToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv2.creditcardtoken(v=AX.60)
ms:contentKeyID: 49854404
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV2.CreditCardToken
dev_langs:
- CSharp
- C++
- VB
---

# CreditCardToken Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Credit card token is created by the processor and represents the credit card number and is used within AX to process customer order securely

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CreditCardToken As String
    Get
    Set
'Usage
Dim instance As IPosTransactionV2
Dim value As String

value = instance.CreditCardToken

instance.CreditCardToken = value
```

``` csharp
string CreditCardToken { get; set; }
```

``` c++
property String^ CreditCardToken {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IPosTransactionV2 Interface](ipostransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

