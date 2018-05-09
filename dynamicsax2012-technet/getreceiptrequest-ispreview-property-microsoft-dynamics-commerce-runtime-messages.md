---
title: GetReceiptRequest.IsPreview Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsPreview Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest.IsPreview
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getreceiptrequest.ispreview(v=AX.60)
ms:contentKeyID: 65322760
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest.IsPreview
dev_langs:
- CSharp
- C++
- VB
---

# IsPreview Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsPreview As Boolean
    Get
    Private Set
'Usage
Dim instance As GetReceiptRequest
Dim value As Boolean

value = instance.IsPreview
```

``` csharp
[DataMemberAttribute]
public bool IsPreview { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsPreview {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetReceiptRequest Class](getreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

