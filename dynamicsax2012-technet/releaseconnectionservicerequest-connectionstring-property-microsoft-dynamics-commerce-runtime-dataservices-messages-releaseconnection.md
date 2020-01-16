---
title: ReleaseConnectionServiceRequest.ConnectionString Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseConnection)
TOCTitle: ConnectionString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseConnection.ReleaseConnectionServiceRequest.ConnectionString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.releaseconnection.releaseconnectionservicerequest.connectionstring(v=AX.60)
ms:contentKeyID: 65318297
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseConnection.ReleaseConnectionServiceRequest.ConnectionString
dev_langs:
- CSharp
- C++
- VB
---

# ConnectionString Property

Gets the connection string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseConnection](microsoft-dynamics-commerce-runtime-dataservices-messages-releaseconnection-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property ConnectionString As String
    Get
    Private Set
'Usage
Dim instance As ReleaseConnectionServiceRequest
Dim value As String

value = instance.ConnectionString
```

``` csharp
public string ConnectionString { get; private set; }
```

``` c++
public:
property String^ ConnectionString {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The connection string.  

## See Also

#### Reference

[ReleaseConnectionServiceRequest Class](releaseconnectionservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages-releaseconnection.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseConnection Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-releaseconnection-namespace.md)

