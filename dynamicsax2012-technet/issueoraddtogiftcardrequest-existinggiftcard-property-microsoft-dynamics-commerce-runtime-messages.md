---
title: IssueOrAddToGiftCardRequest.ExistingGiftCard Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ExistingGiftCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.IssueOrAddToGiftCardRequest.ExistingGiftCard
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.issueoraddtogiftcardrequest.existinggiftcard(v=AX.60)
ms:contentKeyID: 62202108
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.IssueOrAddToGiftCardRequest.ExistingGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# ExistingGiftCard Property

Gets a value indicating whether the gift card already exist.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExistingGiftCard As Boolean
    Get
    Private Set
'Usage
Dim instance As IssueOrAddToGiftCardRequest
Dim value As Boolean

value = instance.ExistingGiftCard
```

``` csharp
[DataMemberAttribute]
public bool ExistingGiftCard { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool ExistingGiftCard {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IssueOrAddToGiftCardRequest Class](issueoraddtogiftcardrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

