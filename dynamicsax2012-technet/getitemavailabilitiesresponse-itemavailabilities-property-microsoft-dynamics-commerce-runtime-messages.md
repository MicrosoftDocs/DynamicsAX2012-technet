---
title: GetItemAvailabilitiesResponse.ItemAvailabilities Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ItemAvailabilities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailabilitiesResponse.ItemAvailabilities
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getitemavailabilitiesresponse.itemavailabilities(v=AX.60)
ms:contentKeyID: 49847478
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailabilitiesResponse.ItemAvailabilities
dev_langs:
- CSharp
- C++
- VB
---

# ItemAvailabilities Property

Gets the collection of item availabities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemAvailabilities As ReadOnlyCollection(Of ItemAvailability)
    Get
    Private Set
'Usage
Dim instance As GetItemAvailabilitiesResponse
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

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetItemAvailabilitiesResponse Class](getitemavailabilitiesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

