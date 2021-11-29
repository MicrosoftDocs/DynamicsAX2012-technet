---
title: PickupAtStoreRequest.ReceiptEmailAddress Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReceiptEmailAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.PickupAtStoreRequest.ReceiptEmailAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.pickupatstorerequest.receiptemailaddress(v=AX.60)
ms:contentKeyID: 62210867
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.PickupAtStoreRequest.ReceiptEmailAddress
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptEmailAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the receipt email.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReceiptEmailAddress As String
    Get
    Private Set
'Usage
Dim instance As PickupAtStoreRequest
Dim value As String

value = instance.ReceiptEmailAddress
```

``` csharp
[DataMemberAttribute]
public string ReceiptEmailAddress { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReceiptEmailAddress {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The email.  

## See Also

#### Reference

[PickupAtStoreRequest Class](pickupatstorerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

