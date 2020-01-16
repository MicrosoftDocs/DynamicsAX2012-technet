---
title: ITransactionServicesV1.GetSalesInvoiceList Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: GetSalesInvoiceList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetSalesInvoiceList(System.Boolean@,System.String@,System.Data.DataTable@,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.getsalesinvoicelist(v=AX.60)
ms:contentKeyID: 47128233
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetSalesInvoiceList
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesInvoiceList Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetSalesInvoiceList ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef salesInvoices As DataTable, _
    customerAccount As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim salesInvoices As DataTable
Dim customerAccount As String

instance.GetSalesInvoiceList(retValue, _
    comment, salesInvoices, customerAccount)
```

``` csharp
void GetSalesInvoiceList(
    ref bool retValue,
    ref string comment,
    ref DataTable salesInvoices,
    string customerAccount
)
```

``` c++
void GetSalesInvoiceList(
    bool% retValue, 
    String^% comment, 
    DataTable^% salesInvoices, 
    String^ customerAccount
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - salesInvoices  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - customerAccount  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

