---
title: ITransactionServicesV1.VoidCreditMemoPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: VoidCreditMemoPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.VoidCreditMemoPayment(System.Boolean@,System.String@,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.voidcreditmemopayment(v=AX.60)
ms:contentKeyID: 47128190
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.VoidCreditMemoPayment
dev_langs:
- CSharp
- C++
- VB
---

# VoidCreditMemoPayment Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub VoidCreditMemoPayment ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    id As String, _
    storeId As String, _
    terminalId As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim id As String
Dim storeId As String
Dim terminalId As String

instance.VoidCreditMemoPayment(retValue, _
    comment, id, storeId, terminalId)
```

``` csharp
void VoidCreditMemoPayment(
    ref bool retValue,
    ref string comment,
    string id,
    string storeId,
    string terminalId
)
```

``` c++
void VoidCreditMemoPayment(
    bool% retValue, 
    String^% comment, 
    String^ id, 
    String^ storeId, 
    String^ terminalId
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

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

