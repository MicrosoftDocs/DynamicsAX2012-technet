---
title: ITransactionServicesV1.GetSalesOrder Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: GetSalesOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetSalesOrder(System.Boolean@,System.String@,System.String@,System.Decimal@,System.Decimal@,System.Decimal@,System.String@,System.String@,System.String@,System.String@,System.DateTime@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.getsalesorder(v=AX.60)
ms:contentKeyID: 47129050
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetSalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesOrder Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetSalesOrder ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef salesId As String, _
    ByRef prePayAmount As Decimal, _
    ByRef prePaidAmount As Decimal, _
    ByRef totalAmount As Decimal, _
    ByRef customerAccount As String, _
    ByRef customerName As String, _
    ByRef orderType As String, _
    ByRef status As String, _
    ByRef creationDate As DateTime _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim salesId As String
Dim prePayAmount As Decimal
Dim prePaidAmount As Decimal
Dim totalAmount As Decimal
Dim customerAccount As String
Dim customerName As String
Dim orderType As String
Dim status As String
Dim creationDate As DateTime

instance.GetSalesOrder(retValue, comment, _
    salesId, prePayAmount, prePaidAmount, _
    totalAmount, customerAccount, customerName, _
    orderType, status, creationDate)
```

``` csharp
void GetSalesOrder(
    ref bool retValue,
    ref string comment,
    ref string salesId,
    ref decimal prePayAmount,
    ref decimal prePaidAmount,
    ref decimal totalAmount,
    ref string customerAccount,
    ref string customerName,
    ref string orderType,
    ref string status,
    ref DateTime creationDate
)
```

``` c++
void GetSalesOrder(
    bool% retValue, 
    String^% comment, 
    String^% salesId, 
    Decimal% prePayAmount, 
    Decimal% prePaidAmount, 
    Decimal% totalAmount, 
    String^% customerAccount, 
    String^% customerName, 
    String^% orderType, 
    String^% status, 
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

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - prePayAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - prePaidAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - totalAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - customerAccount  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - orderType  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - status  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - creationDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

