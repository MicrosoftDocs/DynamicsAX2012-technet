---
title: GetAddressResponse.CountryRegions Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CountryRegions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.CountryRegions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressresponse.countryregions(v=AX.60)
ms:contentKeyID: 62214196
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.CountryRegions
dev_langs:
- CSharp
- C++
- VB
---

# CountryRegions Property

Gets the collection of country regions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CountryRegions As ReadOnlyCollection(Of CountryRegionInfo)
    Get
    Private Set
'Usage
Dim instance As GetAddressResponse
Dim value As ReadOnlyCollection(Of CountryRegionInfo)

value = instance.CountryRegions
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<CountryRegionInfo> CountryRegions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<CountryRegionInfo^>^ CountryRegions {
    ReadOnlyCollection<CountryRegionInfo^>^ get ();
    private: void set (ReadOnlyCollection<CountryRegionInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CountryRegionInfo](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetAddressResponse Class](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

