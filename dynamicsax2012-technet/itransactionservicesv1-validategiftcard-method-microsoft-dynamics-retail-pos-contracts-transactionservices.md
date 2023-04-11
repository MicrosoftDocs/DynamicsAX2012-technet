---
title: ITransactionServicesV1.ValidateGiftCard Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: ValidateGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.ValidateGiftCard(System.Boolean@,System.String@,System.String@,System.Decimal@,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.validategiftcard(v=AX.60)
ms:contentKeyID: 47128687
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.ValidateGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# ValidateGiftCard Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ValidateGiftCard ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef currencyCode As String, _
    ByRef balance As Decimal, _
    id As String, _
    storeId As String, _
    terminalId As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim currencyCode As String
Dim balance As Decimal
Dim id As String
Dim storeId As String
Dim terminalId As String

instance.ValidateGiftCard(retValue, comment, _
    currencyCode, balance, id, storeId, _
    terminalId)
```

``` csharp
void ValidateGiftCard(
    ref bool retValue,
    ref string comment,
    ref string currencyCode,
    ref decimal balance,
    string id,
    string storeId,
    string terminalId
)
```

``` c++
void ValidateGiftCard(
    bool% retValue, 
    String^% comment, 
    String^% currencyCode, 
    Decimal% balance, 
    String^ id, 
    String^ storeId, 
    String^ terminalId
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - balance  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - id  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

