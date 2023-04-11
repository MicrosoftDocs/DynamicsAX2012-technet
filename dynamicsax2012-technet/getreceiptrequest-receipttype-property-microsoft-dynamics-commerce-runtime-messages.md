---
title: GetReceiptRequest.ReceiptType Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReceiptType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest.ReceiptType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreceiptrequest.receipttype(v=AX.60)
ms:contentKeyID: 62214427
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest.ReceiptType
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the specific receipt type that should be printed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReceiptType As ReceiptType
    Get
    Private Set
'Usage
Dim instance As GetReceiptRequest
Dim value As ReceiptType

value = instance.ReceiptType
```

``` csharp
[DataMemberAttribute]
public ReceiptType ReceiptType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReceiptType ReceiptType {
    ReceiptType get ();
    private: void set (ReceiptType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetReceiptRequest Class](getreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

