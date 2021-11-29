---
title: GetAddressResponse Constructor (IEnumerable(ZipCodeInfo)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetAddressResponse Constructor (IEnumerable(ZipCodeInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ZipCodeInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressresponse.getaddressresponse(v=AX.60)
ms:contentKeyID: 62203474
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAddressResponse Constructor (IEnumerable(ZipCodeInfo))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetAddressResponse](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    zipCodes As IEnumerable(Of ZipCodeInfo) _
)
'Usage
Dim zipCodes As IEnumerable(Of ZipCodeInfo)

Dim instance As New GetAddressResponse(zipCodes)
```

``` csharp
public GetAddressResponse(
    IEnumerable<ZipCodeInfo> zipCodes
)
```

``` c++
public:
GetAddressResponse(
    IEnumerable<ZipCodeInfo^>^ zipCodes
)
```

#### Parameters

  - zipCodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ZipCodeInfo](zipcodeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetAddressResponse Class](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetAddressResponse Overload](getaddressresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

