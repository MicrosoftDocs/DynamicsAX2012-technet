---
title: GetReceiptMaskDataRequest.ReceiptTransactionType Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ReceiptTransactionType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReceiptMaskDataRequest.ReceiptTransactionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getreceiptmaskdatarequest.receipttransactiontype(v=AX.60)
ms:contentKeyID: 65321819
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReceiptMaskDataRequest.ReceiptTransactionType
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptTransactionType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Receipt Transaction Type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReceiptTransactionType As ReceiptTransactionType
    Get
    Private Set
'Usage
Dim instance As GetReceiptMaskDataRequest
Dim value As ReceiptTransactionType

value = instance.ReceiptTransactionType
```

``` csharp
[DataMemberAttribute]
public ReceiptTransactionType ReceiptTransactionType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReceiptTransactionType ReceiptTransactionType {
    ReceiptTransactionType get ();
    private: void set (ReceiptTransactionType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType](receipttransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ReceiptTransactionType](receipttransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetReceiptMaskDataRequest Class](getreceiptmaskdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

