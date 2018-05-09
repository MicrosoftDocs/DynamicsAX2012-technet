---
title: SaveTransferOrderServiceRequest.Commit Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Commit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveTransferOrderServiceRequest.Commit
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.savetransferorderservicerequest.commit(v=AX.60)
ms:contentKeyID: 62210809
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveTransferOrderServiceRequest.Commit
dev_langs:
- CSharp
- C++
- VB
---

# Commit Property

Gets a value indicating whether the order is to be committed to Ax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Commit As Boolean
    Get
    Private Set
'Usage
Dim instance As SaveTransferOrderServiceRequest
Dim value As Boolean

value = instance.Commit
```

``` csharp
[DataMemberAttribute]
public bool Commit { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool Commit {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SaveTransferOrderServiceRequest Class](savetransferorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

