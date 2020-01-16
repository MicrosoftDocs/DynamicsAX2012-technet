---
title: ITransactionServicesV1.VoidGiftCard Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: VoidGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.VoidGiftCard(System.Boolean@,System.String@,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.voidgiftcard(v=AX.60)
ms:contentKeyID: 47129232
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.VoidGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# VoidGiftCard Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub VoidGiftCard ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    id As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim id As String

instance.VoidGiftCard(retValue, comment, _
    id)
```

``` csharp
void VoidGiftCard(
    ref bool retValue,
    ref string comment,
    string id
)
```

``` c++
void VoidGiftCard(
    bool% retValue, 
    String^% comment, 
    String^ id
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - id  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

