---
title: GetProductsServiceRequest.FetchProductsAvailableInFuture Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: FetchProductsAvailableInFuture Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductsServiceRequest.FetchProductsAvailableInFuture
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getproductsservicerequest.fetchproductsavailableinfuture(v=AX.60)
ms:contentKeyID: 65320804
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductsServiceRequest.FetchProductsAvailableInFuture
dev_langs:
- CSharp
- C++
- VB
---

# FetchProductsAvailableInFuture Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property FetchProductsAvailableInFuture As Boolean
    Get
    Private Set
'Usage
Dim instance As GetProductsServiceRequest
Dim value As Boolean

value = instance.FetchProductsAvailableInFuture
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public bool FetchProductsAvailableInFuture { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property bool FetchProductsAvailableInFuture {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetProductsServiceRequest Class](getproductsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

