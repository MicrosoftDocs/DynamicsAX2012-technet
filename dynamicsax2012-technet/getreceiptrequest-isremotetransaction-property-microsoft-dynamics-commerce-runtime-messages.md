---
title: GetReceiptRequest.IsRemoteTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsRemoteTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest.IsRemoteTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreceiptrequest.isremotetransaction(v=AX.60)
ms:contentKeyID: 65321038
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest.IsRemoteTransaction
dev_langs:
- CSharp
- C++
- VB
---

# IsRemoteTransaction Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsRemoteTransaction As Boolean
    Get
    Private Set
'Usage
Dim instance As GetReceiptRequest
Dim value As Boolean

value = instance.IsRemoteTransaction
```

``` csharp
[DataMemberAttribute]
public bool IsRemoteTransaction { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsRemoteTransaction {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetReceiptRequest Class](getreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

