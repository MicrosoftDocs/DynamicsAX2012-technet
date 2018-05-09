---
title: SaveCustomerOrderRequest.ReceiptNumberSequence Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReceiptNumberSequence Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCustomerOrderRequest.ReceiptNumberSequence
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.savecustomerorderrequest.receiptnumbersequence(v=AX.60)
ms:contentKeyID: 65318339
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCustomerOrderRequest.ReceiptNumberSequence
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptNumberSequence Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReceiptNumberSequence As String
    Get
    Private Set
'Usage
Dim instance As SaveCustomerOrderRequest
Dim value As String

value = instance.ReceiptNumberSequence
```

``` csharp
[DataMemberAttribute]
public string ReceiptNumberSequence { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReceiptNumberSequence {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[SaveCustomerOrderRequest Class](savecustomerorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

