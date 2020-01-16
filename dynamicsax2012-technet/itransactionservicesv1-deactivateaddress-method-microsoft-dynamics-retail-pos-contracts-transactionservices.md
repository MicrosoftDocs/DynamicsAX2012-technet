---
title: ITransactionServicesV1.DeactivateAddress Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: DeactivateAddress Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.DeactivateAddress(System.Boolean@,System.String@,System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.deactivateaddress(v=AX.60)
ms:contentKeyID: 49829633
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.DeactivateAddress
dev_langs:
- CSharp
- C++
- VB
---

# DeactivateAddress Method

Deactivates the address indicated by the Id (which maps to the Ax RecId) property of the address parameter.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub DeactivateAddress ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    addressId As Long, _
    customerId As Long _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim addressId As Long
Dim customerId As Long

instance.DeactivateAddress(retValue, _
    comment, addressId, customerId)
```

``` csharp
void DeactivateAddress(
    ref bool retValue,
    ref string comment,
    long addressId,
    long customerId
)
```

``` c++
void DeactivateAddress(
    bool% retValue, 
    String^% comment, 
    long long addressId, 
    long long customerId
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - addressId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

