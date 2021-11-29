---
title: SaveCustomerOrderRequest.ReceiptEmailAddress Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReceiptEmailAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCustomerOrderRequest.ReceiptEmailAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecustomerorderrequest.receiptemailaddress(v=AX.60)
ms:contentKeyID: 62215232
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCustomerOrderRequest.ReceiptEmailAddress
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptEmailAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the email.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReceiptEmailAddress As String
    Get
    Set
'Usage
Dim instance As SaveCustomerOrderRequest
Dim value As String

value = instance.ReceiptEmailAddress

instance.ReceiptEmailAddress = value
```

``` csharp
[DataMemberAttribute]
public string ReceiptEmailAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReceiptEmailAddress {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The email.  

## See Also

#### Reference

[SaveCustomerOrderRequest Class](savecustomerorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

