---
title: GetNextReceiptIdServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetNextReceiptIdServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNextReceiptIdServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType,System.Decimal,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getnextreceiptidservicerequest.getnextreceiptidservicerequest(v=AX.60)
ms:contentKeyID: 65321529
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNextReceiptIdServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetNextReceiptIdServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transactionType As SalesTransactionType, _
    netAmountWithNoTax As Decimal, _
    receiptNumberSequence As String, _
    customerOrderMode As CustomerOrderMode _
)
'Usage
Dim transactionType As SalesTransactionType
Dim netAmountWithNoTax As Decimal
Dim receiptNumberSequence As String
Dim customerOrderMode As CustomerOrderMode

Dim instance As New GetNextReceiptIdServiceRequest(transactionType, _
    netAmountWithNoTax, receiptNumberSequence, _
    customerOrderMode)
```

``` csharp
public GetNextReceiptIdServiceRequest(
    SalesTransactionType transactionType,
    decimal netAmountWithNoTax,
    string receiptNumberSequence,
    CustomerOrderMode customerOrderMode
)
```

``` c++
public:
GetNextReceiptIdServiceRequest(
    SalesTransactionType transactionType, 
    Decimal netAmountWithNoTax, 
    String^ receiptNumberSequence, 
    CustomerOrderMode customerOrderMode
)
```

#### Parameters

  - transactionType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType](salestransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - netAmountWithNoTax  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - receiptNumberSequence  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerOrderMode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode](customerordermode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetNextReceiptIdServiceRequest Class](getnextreceiptidservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

