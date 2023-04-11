---
title: GetNextReceiptIdServiceRequest.TransactionType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TransactionType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNextReceiptIdServiceRequest.TransactionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getnextreceiptidservicerequest.transactiontype(v=AX.60)
ms:contentKeyID: 62209266
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNextReceiptIdServiceRequest.TransactionType
dev_langs:
- CSharp
- C++
- VB
---

# TransactionType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales transaction type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property TransactionType As SalesTransactionType
    Get
    Set
'Usage
Dim instance As GetNextReceiptIdServiceRequest
Dim value As SalesTransactionType

value = instance.TransactionType

instance.TransactionType = value
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public SalesTransactionType TransactionType { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property SalesTransactionType TransactionType {
    SalesTransactionType get ();
    void set (SalesTransactionType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType](salestransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesTransactionType](salestransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetNextReceiptIdServiceRequest Class](getnextreceiptidservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

