---
title: GetParentKitDataResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetParentKitDataResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetParentKitDataResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getparentkitdataresponse.getparentkitdataresponse(v=AX.60)
ms:contentKeyID: 65320107
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetParentKitDataResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetParentKitDataResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetParentKitDataResponse](getparentkitdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    kitComponents As ReadOnlyCollection(Of KitComponent) _
)
'Usage
Dim kitComponents As ReadOnlyCollection(Of KitComponent)

Dim instance As New GetParentKitDataResponse(kitComponents)
```

``` csharp
public GetParentKitDataResponse(
    ReadOnlyCollection<KitComponent> kitComponents
)
```

``` c++
public:
GetParentKitDataResponse(
    ReadOnlyCollection<KitComponent^>^ kitComponents
)
```

#### Parameters

  - kitComponents  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitComponent](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetParentKitDataResponse Class](getparentkitdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

