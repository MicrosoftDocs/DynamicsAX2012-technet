---
title: SaveCartRequest.IsGiftCardOperation Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsGiftCardOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest.IsGiftCardOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecartrequest.isgiftcardoperation(v=AX.60)
ms:contentKeyID: 62204548
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest.IsGiftCardOperation
dev_langs:
- CSharp
- C++
- VB
---

# IsGiftCardOperation Property

Gets a value indicating whether this request is a result of gift card operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsGiftCardOperation As Boolean
    Get
    Private Set
'Usage
Dim instance As SaveCartRequest
Dim value As Boolean

value = instance.IsGiftCardOperation
```

``` csharp
[DataMemberAttribute]
public bool IsGiftCardOperation { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsGiftCardOperation {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SaveCartRequest Class](savecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

