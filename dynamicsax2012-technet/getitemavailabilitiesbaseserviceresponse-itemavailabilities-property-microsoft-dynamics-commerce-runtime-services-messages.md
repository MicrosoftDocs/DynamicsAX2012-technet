---
title: GetItemAvailabilitiesBaseServiceResponse.ItemAvailabilities Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ItemAvailabilities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesBaseServiceResponse.ItemAvailabilities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailabilitiesbaseserviceresponse.itemavailabilities(v=AX.60)
ms:contentKeyID: 62211711
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesBaseServiceResponse.ItemAvailabilities
dev_langs:
- CSharp
- C++
- VB
---

# ItemAvailabilities Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item availabilities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemAvailabilities As ReadOnlyCollection(Of ItemAvailability)
    Get
    Private Set
'Usage
Dim instance As GetItemAvailabilitiesBaseServiceResponse
Dim value As ReadOnlyCollection(Of ItemAvailability)

value = instance.ItemAvailabilities
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ItemAvailability> ItemAvailabilities { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ItemAvailability^>^ ItemAvailabilities {
    ReadOnlyCollection<ItemAvailability^>^ get ();
    private: void set (ReadOnlyCollection<ItemAvailability^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetItemAvailabilitiesBaseServiceResponse Class](getitemavailabilitiesbaseserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

