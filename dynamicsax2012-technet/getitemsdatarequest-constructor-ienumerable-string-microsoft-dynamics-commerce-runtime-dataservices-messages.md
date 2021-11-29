---
title: GetItemsDataRequest Constructor (IEnumerable(String)) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetItemsDataRequest Constructor (IEnumerable(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemsDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getitemsdatarequest.getitemsdatarequest(v=AX.60)
ms:contentKeyID: 65320526
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItemsDataRequest Constructor (IEnumerable(String))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetItemsDataRequest](getitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemIds As IEnumerable(Of String) _
)
'Usage
Dim itemIds As IEnumerable(Of String)

Dim instance As New GetItemsDataRequest(itemIds)
```

``` csharp
public GetItemsDataRequest(
    IEnumerable<string> itemIds
)
```

``` c++
public:
GetItemsDataRequest(
    IEnumerable<String^>^ itemIds
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[GetItemsDataRequest Class](getitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetItemsDataRequest Overload](getitemsdatarequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

