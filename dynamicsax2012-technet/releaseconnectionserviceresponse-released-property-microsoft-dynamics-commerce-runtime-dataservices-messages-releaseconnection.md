---
title: ReleaseConnectionServiceResponse.Released Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseConnection)
TOCTitle: Released Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseConnection.ReleaseConnectionServiceResponse.Released
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.releaseconnection.releaseconnectionserviceresponse.released(v=AX.60)
ms:contentKeyID: 65318865
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseConnection.ReleaseConnectionServiceResponse.Released
dev_langs:
- CSharp
- C++
- VB
---

# Released Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the connection was released.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseConnection](microsoft-dynamics-commerce-runtime-dataservices-messages-releaseconnection-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Released As Boolean
    Get
    Private Set
'Usage
Dim instance As ReleaseConnectionServiceResponse
Dim value As Boolean

value = instance.Released
```

``` csharp
public bool Released { get; private set; }
```

``` c++
public:
property bool Released {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether the connection was released.  

## See Also

#### Reference

[ReleaseConnectionServiceResponse Class](releaseconnectionserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages-releaseconnection.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseConnection Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-releaseconnection-namespace.md)

