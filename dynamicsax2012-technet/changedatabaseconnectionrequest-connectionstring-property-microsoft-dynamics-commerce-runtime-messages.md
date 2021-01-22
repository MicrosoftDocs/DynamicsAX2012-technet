---
title: ChangeDatabaseConnectionRequest.ConnectionString Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ConnectionString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeDatabaseConnectionRequest.ConnectionString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.changedatabaseconnectionrequest.connectionstring(v=AX.60)
ms:contentKeyID: 65322438
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeDatabaseConnectionRequest.ConnectionString
dev_langs:
- CSharp
- C++
- VB
---

# ConnectionString Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ConnectionString As String
    Get
    Private Set
'Usage
Dim instance As ChangeDatabaseConnectionRequest
Dim value As String

value = instance.ConnectionString
```

``` csharp
[DataMemberAttribute]
public string ConnectionString { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ConnectionString {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ChangeDatabaseConnectionRequest Class](changedatabaseconnectionrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

