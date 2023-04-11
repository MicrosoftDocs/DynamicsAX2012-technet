---
title: OrderManager.GetReceipts Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetReceipts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetReceipts(System.String,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType,System.Boolean,System.Nullable{System.Int64},System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getreceipts(v=AX.60)
ms:contentKeyID: 65319634
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetReceipts
dev_langs:
- CSharp
- C++
- VB
---

# GetReceipts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetReceipts ( _
    transactionId As String, _
    isCopy As Boolean, _
    receiptType As ReceiptType, _
    isRemoteOrder As Boolean, _
    shiftId As Nullable(Of Long), _
    isPreview As Boolean, _
    queryBySalesId As Boolean _
) As ReadOnlyCollection(Of Receipt)
'Usage
Dim instance As OrderManager
Dim transactionId As String
Dim isCopy As Boolean
Dim receiptType As ReceiptType
Dim isRemoteOrder As Boolean
Dim shiftId As Nullable(Of Long)
Dim isPreview As Boolean
Dim queryBySalesId As Boolean
Dim returnValue As ReadOnlyCollection(Of Receipt)

returnValue = instance.GetReceipts(transactionId, _
    isCopy, receiptType, isRemoteOrder, _
    shiftId, isPreview, queryBySalesId)
```

``` csharp
public ReadOnlyCollection<Receipt> GetReceipts(
    string transactionId,
    bool isCopy,
    ReceiptType receiptType,
    bool isRemoteOrder,
    Nullable<long> shiftId,
    bool isPreview,
    bool queryBySalesId
)
```

``` c++
public:
ReadOnlyCollection<Receipt^>^ GetReceipts(
    String^ transactionId, 
    bool isCopy, 
    ReceiptType receiptType, 
    bool isRemoteOrder, 
    Nullable<long long> shiftId, 
    bool isPreview, 
    bool queryBySalesId
)
```

#### Parameters

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isCopy  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - receiptType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - isRemoteOrder  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - isPreview  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - queryBySalesId  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Receipt](receipt-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

