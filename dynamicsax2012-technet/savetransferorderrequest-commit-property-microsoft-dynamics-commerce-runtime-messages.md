---
title: SaveTransferOrderRequest.Commit Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Commit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTransferOrderRequest.Commit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savetransferorderrequest.commit(v=AX.60)
ms:contentKeyID: 62214477
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTransferOrderRequest.Commit
dev_langs:
- CSharp
- C++
- VB
---

# Commit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the document is to be committed to Ax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Commit As Boolean
    Get
    Set
'Usage
Dim instance As SaveTransferOrderRequest
Dim value As Boolean

value = instance.Commit

instance.Commit = value
```

``` csharp
[DataMemberAttribute]
public bool Commit { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool Commit {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SaveTransferOrderRequest Class](savetransferorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

