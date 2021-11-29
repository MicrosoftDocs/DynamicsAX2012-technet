---
title: SubmitSalesTransactionRequest.ReceiptNumberSequence Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReceiptNumberSequence Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SubmitSalesTransactionRequest.ReceiptNumberSequence
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.submitsalestransactionrequest.receiptnumbersequence(v=AX.60)
ms:contentKeyID: 65315824
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SubmitSalesTransactionRequest.ReceiptNumberSequence
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptNumberSequence Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReceiptNumberSequence As String
    Get
    Set
'Usage
Dim instance As SubmitSalesTransactionRequest
Dim value As String

value = instance.ReceiptNumberSequence

instance.ReceiptNumberSequence = value
```

``` csharp
[DataMemberAttribute]
public string ReceiptNumberSequence { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReceiptNumberSequence {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[SubmitSalesTransactionRequest Class](submitsalestransactionrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

