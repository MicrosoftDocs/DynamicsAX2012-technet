---
title: GetAddressInfoServiceResponse(TAddressEntityInfo) Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetAddressInfoServiceResponse(TAddressEntityInfo) Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse`1.#ctor(System.Collections.Generic.IEnumerable{`0})
ms:mtpsurl: https://technet.microsoft.com/library/Dn696519(v=AX.60)
ms:contentKeyID: 62207919
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse`1.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetAddressInfoServiceResponse(TAddressEntityInfo) Constructor

Initializes a new instance of the [GetAddressInfoServiceResponse\<TAddressEntityInfo\>](getaddressinfoserviceresponse-taddressentityinfo-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    results As IEnumerable(Of TAddressEntityInfo) _
)
'Usage
Dim results As IEnumerable(Of TAddressEntityInfo)

Dim instance As New GetAddressInfoServiceResponse(results)
```

``` csharp
public GetAddressInfoServiceResponse(
    IEnumerable<TAddressEntityInfo> results
)
```

``` c++
public:
GetAddressInfoServiceResponse(
    IEnumerable<TAddressEntityInfo>^ results
)
```

#### Parameters

  - results  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TAddressEntityInfo](getaddressinfoserviceresponse-taddressentityinfo-class-microsoft-dynamics-commerce-runtime-services-messages.md)\>  

## See Also

#### Reference

[GetAddressInfoServiceResponse\<TAddressEntityInfo\> Class](getaddressinfoserviceresponse-taddressentityinfo-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

