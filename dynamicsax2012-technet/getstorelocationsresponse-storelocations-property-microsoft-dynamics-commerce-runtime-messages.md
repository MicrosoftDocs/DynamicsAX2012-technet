---
title: GetStoreLocationsResponse.StoreLocations Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StoreLocations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreLocationsResponse.StoreLocations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstorelocationsresponse.storelocations(v=AX.60)
ms:contentKeyID: 49843780
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreLocationsResponse.StoreLocations
dev_langs:
- CSharp
- C++
- VB
---

# StoreLocations Property

Gets the collection of store locations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StoreLocations As ReadOnlyCollection(Of OrgUnitLocation)
    Get
    Private Set
'Usage
Dim instance As GetStoreLocationsResponse
Dim value As ReadOnlyCollection(Of OrgUnitLocation)

value = instance.StoreLocations
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<OrgUnitLocation> StoreLocations { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<OrgUnitLocation^>^ StoreLocations {
    ReadOnlyCollection<OrgUnitLocation^>^ get ();
    private: void set (ReadOnlyCollection<OrgUnitLocation^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OrgUnitLocation](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetStoreLocationsResponse Class](getstorelocationsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

