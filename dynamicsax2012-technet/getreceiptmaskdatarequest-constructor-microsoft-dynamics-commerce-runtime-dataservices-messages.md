---
title: GetReceiptMaskDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetReceiptMaskDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReceiptMaskDataRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getreceiptmaskdatarequest.getreceiptmaskdatarequest(v=AX.60)
ms:contentKeyID: 65317694
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReceiptMaskDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetReceiptMaskDataRequest Constructor

Initializes a new instance of the [GetReceiptMaskDataRequest](getreceiptmaskdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    functionalityProfileId As String, _
    receiptTransactionType As ReceiptTransactionType _
)
'Usage
Dim functionalityProfileId As String
Dim receiptTransactionType As ReceiptTransactionType

Dim instance As New GetReceiptMaskDataRequest(functionalityProfileId, _
    receiptTransactionType)
```

``` csharp
public GetReceiptMaskDataRequest(
    string functionalityProfileId,
    ReceiptTransactionType receiptTransactionType
)
```

``` c++
public:
GetReceiptMaskDataRequest(
    String^ functionalityProfileId, 
    ReceiptTransactionType receiptTransactionType
)
```

#### Parameters

  - functionalityProfileId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptTransactionType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType](receipttransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetReceiptMaskDataRequest Class](getreceiptmaskdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

