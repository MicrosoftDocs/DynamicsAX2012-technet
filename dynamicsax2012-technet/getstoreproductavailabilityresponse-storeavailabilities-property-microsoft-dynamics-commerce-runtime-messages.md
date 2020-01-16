---
title: GetStoreProductAvailabilityResponse.StoreAvailabilities Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StoreAvailabilities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityResponse.StoreAvailabilities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoreproductavailabilityresponse.storeavailabilities(v=AX.60)
ms:contentKeyID: 49855923
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityResponse.StoreAvailabilities
dev_langs:
- CSharp
- C++
- VB
---

# StoreAvailabilities Property

Gets the collection of stores.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StoreAvailabilities As ReadOnlyCollection(Of OrgUnitAvailability)
    Get
    Private Set
'Usage
Dim instance As GetStoreProductAvailabilityResponse
Dim value As ReadOnlyCollection(Of OrgUnitAvailability)

value = instance.StoreAvailabilities
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<OrgUnitAvailability> StoreAvailabilities { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<OrgUnitAvailability^>^ StoreAvailabilities {
    ReadOnlyCollection<OrgUnitAvailability^>^ get ();
    private: void set (ReadOnlyCollection<OrgUnitAvailability^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OrgUnitAvailability](orgunitavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetStoreProductAvailabilityResponse Class](getstoreproductavailabilityresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

