---
title: GetChannelCategoryAttributesDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetChannelCategoryAttributesDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelCategoryAttributesDataRequest.#ctor(System.Int64,System.Collections.Generic.IEnumerable{System.Int64},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getchannelcategoryattributesdatarequest.getchannelcategoryattributesdatarequest(v=AX.60)
ms:contentKeyID: 65320547
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelCategoryAttributesDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelCategoryAttributesDataRequest Constructor

Initializes a new instance of the [GetChannelCategoryAttributesDataRequest](getchannelcategoryattributesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    categoryIds As IEnumerable(Of Long), _
    settings As QueryResultSettings _
)
'Usage
Dim channelId As Long
Dim categoryIds As IEnumerable(Of Long)
Dim settings As QueryResultSettings

Dim instance As New GetChannelCategoryAttributesDataRequest(channelId, _
    categoryIds, settings)
```

``` csharp
public GetChannelCategoryAttributesDataRequest(
    long channelId,
    IEnumerable<long> categoryIds,
    QueryResultSettings settings
)
```

``` c++
public:
GetChannelCategoryAttributesDataRequest(
    long long channelId, 
    IEnumerable<long long>^ categoryIds, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - categoryIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetChannelCategoryAttributesDataRequest Class](getchannelcategoryattributesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

