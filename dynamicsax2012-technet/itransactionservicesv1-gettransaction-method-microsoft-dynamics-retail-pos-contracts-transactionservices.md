---
title: ITransactionServicesV1.GetTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: GetTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetTransaction(System.Boolean@,System.String@,System.Boolean@,System.Data.DataTable@,System.Data.DataTable@,System.Data.DataTable@,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.gettransaction(v=AX.60)
ms:contentKeyID: 47128385
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetTransaction
dev_langs:
- CSharp
- C++
- VB
---

# GetTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This method has been deprecated. Use the ITransactionServicesV3::GetTransaction method instead")> _
Sub GetTransaction ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef uniqueReceiptId As Boolean, _
    ByRef transHeader As DataTable, _
    ByRef transItems As DataTable, _
    ByRef transLoyalty As DataTable, _
    receiptId As String, _
    storeId As String, _
    terminalId As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim uniqueReceiptId As Boolean
Dim transHeader As DataTable
Dim transItems As DataTable
Dim transLoyalty As DataTable
Dim receiptId As String
Dim storeId As String
Dim terminalId As String

instance.GetTransaction(retValue, comment, _
    uniqueReceiptId, transHeader, transItems, _
    transLoyalty, receiptId, storeId, _
    terminalId)
```

``` csharp
[ObsoleteAttribute("This method has been deprecated. Use the ITransactionServicesV3::GetTransaction method instead")]
void GetTransaction(
    ref bool retValue,
    ref string comment,
    ref bool uniqueReceiptId,
    ref DataTable transHeader,
    ref DataTable transItems,
    ref DataTable transLoyalty,
    string receiptId,
    string storeId,
    string terminalId
)
```

``` c++
[ObsoleteAttribute(L"This method has been deprecated. Use the ITransactionServicesV3::GetTransaction method instead")]
void GetTransaction(
    bool% retValue, 
    String^% comment, 
    bool% uniqueReceiptId, 
    DataTable^% transHeader, 
    DataTable^% transItems, 
    DataTable^% transLoyalty, 
    String^ receiptId, 
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

  - uniqueReceiptId  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - transHeader  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - transItems  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - transLoyalty  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - receiptId  
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

