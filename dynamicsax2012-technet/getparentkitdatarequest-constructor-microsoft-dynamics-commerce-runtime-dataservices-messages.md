---
title: GetParentKitDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetParentKitDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetParentKitDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.Int64},System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getparentkitdatarequest.getparentkitdatarequest(v=AX.60)
ms:contentKeyID: 65319605
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetParentKitDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetParentKitDataRequest Constructor

Initializes a new instance of the [GetParentKitDataRequest](getparentkitdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productIds As IEnumerable(Of Long), _
    masterProductIds As IEnumerable(Of Long) _
)
'Usage
Dim productIds As IEnumerable(Of Long)
Dim masterProductIds As IEnumerable(Of Long)

Dim instance As New GetParentKitDataRequest(productIds, _
    masterProductIds)
```

``` csharp
public GetParentKitDataRequest(
    IEnumerable<long> productIds,
    IEnumerable<long> masterProductIds
)
```

``` c++
public:
GetParentKitDataRequest(
    IEnumerable<long long>^ productIds, 
    IEnumerable<long long>^ masterProductIds
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - masterProductIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[GetParentKitDataRequest Class](getparentkitdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

