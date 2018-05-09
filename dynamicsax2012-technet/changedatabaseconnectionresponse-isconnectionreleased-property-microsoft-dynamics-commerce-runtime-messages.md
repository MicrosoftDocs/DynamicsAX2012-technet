---
title: ChangeDatabaseConnectionResponse.IsConnectionReleased Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsConnectionReleased Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeDatabaseConnectionResponse.IsConnectionReleased
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.changedatabaseconnectionresponse.isconnectionreleased(v=AX.60)
ms:contentKeyID: 65322381
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeDatabaseConnectionResponse.IsConnectionReleased
dev_langs:
- CSharp
- C++
- VB
---

# IsConnectionReleased Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsConnectionReleased As Boolean
    Get
    Private Set
'Usage
Dim instance As ChangeDatabaseConnectionResponse
Dim value As Boolean

value = instance.IsConnectionReleased
```

``` csharp
[DataMemberAttribute]
public bool IsConnectionReleased { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsConnectionReleased {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ChangeDatabaseConnectionResponse Class](changedatabaseconnectionresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

