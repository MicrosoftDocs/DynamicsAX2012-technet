---
title: ITransactionServicesV1.UpdateIssuedLoyaltyPoints Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: UpdateIssuedLoyaltyPoints Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.UpdateIssuedLoyaltyPoints(System.Boolean@,System.String@,System.String,System.String,System.String,System.String,System.String,System.DateTime,System.Decimal,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.updateissuedloyaltypoints(v=AX.60)
ms:contentKeyID: 47128112
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.UpdateIssuedLoyaltyPoints
dev_langs:
- CSharp
- C++
- VB
---

# UpdateIssuedLoyaltyPoints Method

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This method has been deprecated.")> _
Sub UpdateIssuedLoyaltyPoints ( _
    ByRef valid As Boolean, _
    ByRef comment As String, _
    transactionId As String, _
    lineNum As String, _
    storeId As String, _
    terminalId As String, _
    cardNumber As String, _
    transDate As DateTime, _
    loyaltyPoints As Decimal, _
    receiptId As String, _
    staffId As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim valid As Boolean
Dim comment As String
Dim transactionId As String
Dim lineNum As String
Dim storeId As String
Dim terminalId As String
Dim cardNumber As String
Dim transDate As DateTime
Dim loyaltyPoints As Decimal
Dim receiptId As String
Dim staffId As String

instance.UpdateIssuedLoyaltyPoints(valid, _
    comment, transactionId, lineNum, _
    storeId, terminalId, cardNumber, _
    transDate, loyaltyPoints, receiptId, _
    staffId)
```

``` csharp
[ObsoleteAttribute("This method has been deprecated.")]
void UpdateIssuedLoyaltyPoints(
    ref bool valid,
    ref string comment,
    string transactionId,
    string lineNum,
    string storeId,
    string terminalId,
    string cardNumber,
    DateTime transDate,
    decimal loyaltyPoints,
    string receiptId,
    string staffId
)
```

``` c++
[ObsoleteAttribute(L"This method has been deprecated.")]
void UpdateIssuedLoyaltyPoints(
    bool% valid, 
    String^% comment, 
    String^ transactionId, 
    String^ lineNum, 
    String^ storeId, 
    String^ terminalId, 
    String^ cardNumber, 
    DateTime transDate, 
    Decimal loyaltyPoints, 
    String^ receiptId, 
    String^ staffId
)
```

#### Parameters

  - valid  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - lineNum  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - loyaltyPoints  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - receiptId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

