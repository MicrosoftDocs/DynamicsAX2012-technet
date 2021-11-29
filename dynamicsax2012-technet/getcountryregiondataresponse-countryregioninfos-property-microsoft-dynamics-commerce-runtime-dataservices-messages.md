---
title: GetCountryRegionDataResponse.CountryRegionInfos Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CountryRegionInfos Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCountryRegionDataResponse.CountryRegionInfos
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcountryregiondataresponse.countryregioninfos(v=AX.60)
ms:contentKeyID: 65319324
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCountryRegionDataResponse.CountryRegionInfos
dev_langs:
- CSharp
- C++
- VB
---

# CountryRegionInfos Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the value of country region info collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CountryRegionInfos As ReadOnlyCollection(Of CountryRegionInfo)
    Get
    Private Set
'Usage
Dim instance As GetCountryRegionDataResponse
Dim value As ReadOnlyCollection(Of CountryRegionInfo)

value = instance.CountryRegionInfos
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<CountryRegionInfo> CountryRegionInfos { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<CountryRegionInfo^>^ CountryRegionInfos {
    ReadOnlyCollection<CountryRegionInfo^>^ get ();
    private: void set (ReadOnlyCollection<CountryRegionInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CountryRegionInfo](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetCountryRegionDataResponse Class](getcountryregiondataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

