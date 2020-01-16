---
title: ITransactionServicesV1.StaffLogOn Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: StaffLogOn Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.StaffLogOn(System.Boolean@,System.String@,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.stafflogon(v=AX.60)
ms:contentKeyID: 47128974
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.StaffLogOn
dev_langs:
- CSharp
- C++
- VB
---

# StaffLogOn Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub StaffLogOn ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    staffId As String, _
    storeId As String, _
    terminalId As String, _
    password As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim staffId As String
Dim storeId As String
Dim terminalId As String
Dim password As String

instance.StaffLogOn(retValue, comment, _
    staffId, storeId, terminalId, password)
```

``` csharp
void StaffLogOn(
    ref bool retValue,
    ref string comment,
    string staffId,
    string storeId,
    string terminalId,
    string password
)
```

``` c++
void StaffLogOn(
    bool% retValue, 
    String^% comment, 
    String^ staffId, 
    String^ storeId, 
    String^ terminalId, 
    String^ password
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - password  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

