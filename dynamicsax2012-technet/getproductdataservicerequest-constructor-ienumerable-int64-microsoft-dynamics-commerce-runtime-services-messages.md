---
title: GetProductDataServiceRequest Constructor (IEnumerable(Int64)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetProductDataServiceRequest Constructor (IEnumerable(Int64))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductDataServiceRequest.#ctor(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getproductdataservicerequest.getproductdataservicerequest(v=AX.60)
ms:contentKeyID: 65318080
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProductDataServiceRequest Constructor (IEnumerable(Int64))

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productIds As IEnumerable(Of Long) _
)
'Usage
Dim productIds As IEnumerable(Of Long)

Dim instance As New GetProductDataServiceRequest(productIds)
```

``` csharp
public GetProductDataServiceRequest(
    IEnumerable<long> productIds
)
```

``` c++
public:
GetProductDataServiceRequest(
    IEnumerable<long long>^ productIds
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[GetProductDataServiceRequest Class](getproductdataservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetProductDataServiceRequest Overload](getproductdataservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

