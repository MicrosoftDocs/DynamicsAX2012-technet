---
title: GetAddressResponse.Cities Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Cities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.Cities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressresponse.cities(v=AX.60)
ms:contentKeyID: 62209683
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.Cities
dev_langs:
- CSharp
- C++
- VB
---

# Cities Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of cities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Cities As ReadOnlyCollection(Of CityInfo)
    Get
    Private Set
'Usage
Dim instance As GetAddressResponse
Dim value As ReadOnlyCollection(Of CityInfo)

value = instance.Cities
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<CityInfo> Cities { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<CityInfo^>^ Cities {
    ReadOnlyCollection<CityInfo^>^ get ();
    private: void set (ReadOnlyCollection<CityInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CityInfo](cityinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetAddressResponse Class](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

