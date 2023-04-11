---
title: GetCountryRegionDataResponse.AddressFormattingInfos Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: AddressFormattingInfos Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCountryRegionDataResponse.AddressFormattingInfos
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcountryregiondataresponse.addressformattinginfos(v=AX.60)
ms:contentKeyID: 65321019
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCountryRegionDataResponse.AddressFormattingInfos
dev_langs:
- CSharp
- C++
- VB
---

# AddressFormattingInfos Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the value of address formatting info collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AddressFormattingInfos As ReadOnlyCollection(Of AddressFormattingInfo)
    Get
    Private Set
'Usage
Dim instance As GetCountryRegionDataResponse
Dim value As ReadOnlyCollection(Of AddressFormattingInfo)

value = instance.AddressFormattingInfos
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<AddressFormattingInfo> AddressFormattingInfos { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<AddressFormattingInfo^>^ AddressFormattingInfos {
    ReadOnlyCollection<AddressFormattingInfo^>^ get ();
    private: void set (ReadOnlyCollection<AddressFormattingInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[AddressFormattingInfo](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetCountryRegionDataResponse Class](getcountryregiondataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

