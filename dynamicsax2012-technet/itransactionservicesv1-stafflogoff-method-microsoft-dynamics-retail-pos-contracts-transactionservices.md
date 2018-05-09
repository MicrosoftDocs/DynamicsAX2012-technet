---
title: ITransactionServicesV1.StaffLogOff Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: StaffLogOff Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.StaffLogOff(System.Boolean@,System.String@,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.stafflogoff(v=AX.60)
ms:contentKeyID: 47129206
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.StaffLogOff
dev_langs:
- CSharp
- C++
- VB
---

# StaffLogOff Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub StaffLogOff ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    staffId As String, _
    storeId As String, _
    terminalId As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim staffId As String
Dim storeId As String
Dim terminalId As String

instance.StaffLogOff(retValue, comment, _
    staffId, storeId, terminalId)
```

``` csharp
void StaffLogOff(
    ref bool retValue,
    ref string comment,
    string staffId,
    string storeId,
    string terminalId
)
```

``` c++
void StaffLogOff(
    bool% retValue, 
    String^% comment, 
    String^ staffId, 
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

  - staffId  
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

