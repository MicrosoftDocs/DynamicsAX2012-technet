---
title: GetReceiptRequest.IsCopy Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsCopy Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest.IsCopy
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreceiptrequest.iscopy(v=AX.60)
ms:contentKeyID: 62214236
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest.IsCopy
dev_langs:
- CSharp
- C++
- VB
---

# IsCopy Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the receipt is a duplicate or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsCopy As Boolean
    Get
    Private Set
'Usage
Dim instance As GetReceiptRequest
Dim value As Boolean

value = instance.IsCopy
```

``` csharp
[DataMemberAttribute]
public bool IsCopy { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsCopy {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetReceiptRequest Class](getreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

