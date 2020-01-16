---
title: GetXAndZReportReceiptRequest Constructor (ReceiptType, String, String, Nullable(Int64)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetXAndZReportReceiptRequest Constructor (ReceiptType, String, String, Nullable(Int64))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetXAndZReportReceiptRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType,System.String,System.String,System.Nullable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getxandzreportreceiptrequest.getxandzreportreceiptrequest(v=AX.60)
ms:contentKeyID: 65317559
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetXAndZReportReceiptRequest Constructor (ReceiptType, String, String, Nullable(Int64))

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    receiptType As ReceiptType, _
    transactionId As String, _
    terminalId As String, _
    shiftId As Nullable(Of Long) _
)
'Usage
Dim receiptType As ReceiptType
Dim transactionId As String
Dim terminalId As String
Dim shiftId As Nullable(Of Long)

Dim instance As New GetXAndZReportReceiptRequest(receiptType, _
    transactionId, terminalId, shiftId)
```

``` csharp
public GetXAndZReportReceiptRequest(
    ReceiptType receiptType,
    string transactionId,
    string terminalId,
    Nullable<long> shiftId
)
```

``` c++
public:
GetXAndZReportReceiptRequest(
    ReceiptType receiptType, 
    String^ transactionId, 
    String^ terminalId, 
    Nullable<long long> shiftId
)
```

#### Parameters

  - receiptType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[GetXAndZReportReceiptRequest Class](getxandzreportreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetXAndZReportReceiptRequest Overload](getxandzreportreceiptrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

