---
title: CreateSalesOrderServiceRequest Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CreateSalesOrderServiceRequest Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateSalesOrderServiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.createsalesorderservicerequest.createsalesorderservicerequest(v=AX.60)
ms:contentKeyID: 65322777
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateSalesOrderServiceRequest Constructor (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cartId As String, _
    customerId As String _
)
'Usage
Dim cartId As String
Dim customerId As String

Dim instance As New CreateSalesOrderServiceRequest(cartId, _
    customerId)
```

``` csharp
public CreateSalesOrderServiceRequest(
    string cartId,
    string customerId
)
```

``` c++
public:
CreateSalesOrderServiceRequest(
    String^ cartId, 
    String^ customerId
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CreateSalesOrderServiceRequest Class](createsalesorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[CreateSalesOrderServiceRequest Overload](createsalesorderservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

