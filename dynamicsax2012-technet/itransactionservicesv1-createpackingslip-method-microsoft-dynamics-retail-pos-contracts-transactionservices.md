---
title: ITransactionServicesV1.CreatePackingSlip Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: CreatePackingSlip Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.CreatePackingSlip(System.Boolean@,System.String@,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.createpackingslip(v=AX.60)
ms:contentKeyID: 47128879
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.CreatePackingSlip
dev_langs:
- CSharp
- C++
- VB
---

# CreatePackingSlip Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CreatePackingSlip ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    salesId As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim salesId As String

instance.CreatePackingSlip(retValue, _
    comment, salesId)
```

``` csharp
void CreatePackingSlip(
    ref bool retValue,
    ref string comment,
    string salesId
)
```

``` c++
void CreatePackingSlip(
    bool% retValue, 
    String^% comment, 
    String^ salesId
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

