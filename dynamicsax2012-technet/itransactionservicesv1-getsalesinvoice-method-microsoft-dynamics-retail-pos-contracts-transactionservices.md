---
title: ITransactionServicesV1.GetSalesInvoice Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: GetSalesInvoice Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetSalesInvoice(System.Boolean@,System.String@,System.String@,System.Decimal@,System.Decimal@,System.String@,System.String@,System.DateTime@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.getsalesinvoice(v=AX.60)
ms:contentKeyID: 47129151
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetSalesInvoice
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesInvoice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetSalesInvoice ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef invoiceId As String, _
    ByRef totalPaidAmount As Decimal, _
    ByRef totalInvoiceAmount As Decimal, _
    ByRef customerAccount As String, _
    ByRef customerName As String, _
    ByRef creationDate As DateTime _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim invoiceId As String
Dim totalPaidAmount As Decimal
Dim totalInvoiceAmount As Decimal
Dim customerAccount As String
Dim customerName As String
Dim creationDate As DateTime

instance.GetSalesInvoice(retValue, comment, _
    invoiceId, totalPaidAmount, totalInvoiceAmount, _
    customerAccount, customerName, creationDate)
```

``` csharp
void GetSalesInvoice(
    ref bool retValue,
    ref string comment,
    ref string invoiceId,
    ref decimal totalPaidAmount,
    ref decimal totalInvoiceAmount,
    ref string customerAccount,
    ref string customerName,
    ref DateTime creationDate
)
```

``` c++
void GetSalesInvoice(
    bool% retValue, 
    String^% comment, 
    String^% invoiceId, 
    Decimal% totalPaidAmount, 
    Decimal% totalInvoiceAmount, 
    String^% customerAccount, 
    String^% customerName, 
    DateTime% creationDate
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - invoiceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - totalPaidAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - totalInvoiceAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - customerAccount  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - creationDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

