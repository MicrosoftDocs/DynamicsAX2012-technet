---
title: GetStoresServiceResponse.Stores Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Stores Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoresServiceResponse.Stores
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstoresserviceresponse.stores(v=AX.60)
ms:contentKeyID: 62214018
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoresServiceResponse.Stores
dev_langs:
- CSharp
- C++
- VB
---

# Stores Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the enumerable list of stores.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Stores As ReadOnlyCollection(Of OrgUnitLocation)
    Get
    Private Set
'Usage
Dim instance As GetStoresServiceResponse
Dim value As ReadOnlyCollection(Of OrgUnitLocation)

value = instance.Stores
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<OrgUnitLocation> Stores { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<OrgUnitLocation^>^ Stores {
    ReadOnlyCollection<OrgUnitLocation^>^ get ();
    private: void set (ReadOnlyCollection<OrgUnitLocation^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OrgUnitLocation](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetStoresServiceResponse Class](getstoresserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

