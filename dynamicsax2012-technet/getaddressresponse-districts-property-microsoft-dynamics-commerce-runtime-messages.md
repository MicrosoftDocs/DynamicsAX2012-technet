---
title: GetAddressResponse.Districts Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Districts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.Districts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressresponse.districts(v=AX.60)
ms:contentKeyID: 62213879
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.Districts
dev_langs:
- CSharp
- C++
- VB
---

# Districts Property

Gets the collection of District.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Districts As ReadOnlyCollection(Of DistrictInfo)
    Get
    Private Set
'Usage
Dim instance As GetAddressResponse
Dim value As ReadOnlyCollection(Of DistrictInfo)

value = instance.Districts
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<DistrictInfo> Districts { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<DistrictInfo^>^ Districts {
    ReadOnlyCollection<DistrictInfo^>^ get ();
    private: void set (ReadOnlyCollection<DistrictInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[DistrictInfo](districtinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetAddressResponse Class](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

