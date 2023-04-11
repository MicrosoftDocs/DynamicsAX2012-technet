---
title: GetStoreProductAvailabilityRequest Constructor (QueryResultSettings, IEnumerable(ItemUnit), SearchArea) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetStoreProductAvailabilityRequest Constructor (QueryResultSettings, IEnumerable(ItemUnit), SearchArea)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit},Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoreproductavailabilityrequest.getstoreproductavailabilityrequest(v=AX.60)
ms:contentKeyID: 65318825
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoreProductAvailabilityRequest Constructor (QueryResultSettings, IEnumerable(ItemUnit), SearchArea)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    settings As QueryResultSettings, _
    items As IEnumerable(Of ItemUnit), _
    searchArea As SearchArea _
)
'Usage
Dim settings As QueryResultSettings
Dim items As IEnumerable(Of ItemUnit)
Dim searchArea As SearchArea

Dim instance As New GetStoreProductAvailabilityRequest(settings, _
    items, searchArea)
```

``` csharp
public GetStoreProductAvailabilityRequest(
    QueryResultSettings settings,
    IEnumerable<ItemUnit> items,
    SearchArea searchArea
)
```

``` c++
public:
GetStoreProductAvailabilityRequest(
    QueryResultSettings^ settings, 
    IEnumerable<ItemUnit^>^ items, 
    SearchArea^ searchArea
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemUnit](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - searchArea  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetStoreProductAvailabilityRequest Class](getstoreproductavailabilityrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetStoreProductAvailabilityRequest Overload](getstoreproductavailabilityrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

