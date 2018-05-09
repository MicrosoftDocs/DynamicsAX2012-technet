---
title: ITransactionServicesV3.GiftCardRelease Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: GiftCardRelease Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV3.GiftCardRelease(System.Boolean@,System.String@,System.String@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv3.giftcardrelease(v=AX.60)
ms:contentKeyID: 62203686
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV3.GiftCardRelease
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardRelease Method

Releases (unlocks) the gift card.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GiftCardRelease ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef id As String _
)
'Usage
Dim instance As ITransactionServicesV3
Dim retValue As Boolean
Dim comment As String
Dim id As String

instance.GiftCardRelease(retValue, comment, _
    id)
```

``` csharp
void GiftCardRelease(
    ref bool retValue,
    ref string comment,
    ref string id
)
```

``` c++
void GiftCardRelease(
    bool% retValue, 
    String^% comment, 
    String^% id
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - id  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV3 Interface](itransactionservicesv3-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

