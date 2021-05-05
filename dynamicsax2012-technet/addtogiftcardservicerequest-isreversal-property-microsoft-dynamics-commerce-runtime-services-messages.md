---
title: AddToGiftCardServiceRequest.IsReversal Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IsReversal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AddToGiftCardServiceRequest.IsReversal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.addtogiftcardservicerequest.isreversal(v=AX.60)
ms:contentKeyID: 62210780
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AddToGiftCardServiceRequest.IsReversal
dev_langs:
- CSharp
- C++
- VB
---

# IsReversal Property

Gets a value indicating whether this request is a reversal operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsReversal As Boolean
    Get
    Private Set
'Usage
Dim instance As AddToGiftCardServiceRequest
Dim value As Boolean

value = instance.IsReversal
```

``` csharp
[DataMemberAttribute]
public bool IsReversal { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsReversal {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[AddToGiftCardServiceRequest Class](addtogiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

