---
title: GetReceiptRequest Constructor (String, Boolean, ReceiptType, Boolean, Nullable(Int64), Boolean, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetReceiptRequest Constructor (String, Boolean, ReceiptType, Boolean, Nullable(Int64), Boolean, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest.#ctor(System.String,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType,System.Boolean,System.Nullable{System.Int64},System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreceiptrequest.getreceiptrequest(v=AX.60)
ms:contentKeyID: 65317302
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReceiptRequest Constructor (String, Boolean, ReceiptType, Boolean, Nullable(Int64), Boolean, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transactionId As String, _
    isCopy As Boolean, _
    receiptType As ReceiptType, _
    isRemoteOrder As Boolean, _
    shiftId As Nullable(Of Long), _
    isPreview As Boolean, _
    queryBySalesId As Boolean _
)
'Usage
Dim transactionId As String
Dim isCopy As Boolean
Dim receiptType As ReceiptType
Dim isRemoteOrder As Boolean
Dim shiftId As Nullable(Of Long)
Dim isPreview As Boolean
Dim queryBySalesId As Boolean

Dim instance As New GetReceiptRequest(transactionId, _
    isCopy, receiptType, isRemoteOrder, _
    shiftId, isPreview, queryBySalesId)
```

``` csharp
public GetReceiptRequest(
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
GetReceiptRequest(
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

## See Also

#### Reference

[GetReceiptRequest Class](getreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetReceiptRequest Overload](getreceiptrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

