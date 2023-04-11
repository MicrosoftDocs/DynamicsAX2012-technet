---
title: ITransactionServicesV1.GetSalesOrderList Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: GetSalesOrderList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetSalesOrderList(System.Boolean@,System.String@,System.Data.DataTable@,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.getsalesorderlist(v=AX.60)
ms:contentKeyID: 47128603
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetSalesOrderList
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesOrderList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetSalesOrderList ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef salesOrders As DataTable, _
    customerAccount As String, _
    forPrePayment As Boolean _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim salesOrders As DataTable
Dim customerAccount As String
Dim forPrePayment As Boolean

instance.GetSalesOrderList(retValue, _
    comment, salesOrders, customerAccount, _
    forPrePayment)
```

``` csharp
void GetSalesOrderList(
    ref bool retValue,
    ref string comment,
    ref DataTable salesOrders,
    string customerAccount,
    bool forPrePayment
)
```

``` c++
void GetSalesOrderList(
    bool% retValue, 
    String^% comment, 
    DataTable^% salesOrders, 
    String^ customerAccount, 
    bool forPrePayment
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - salesOrders  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - customerAccount  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - forPrePayment  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

