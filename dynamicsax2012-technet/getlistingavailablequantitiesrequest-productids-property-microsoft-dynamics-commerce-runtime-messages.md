---
title: GetListingAvailableQuantitiesRequest.ProductIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ProductIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetListingAvailableQuantitiesRequest.ProductIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getlistingavailablequantitiesrequest.productids(v=AX.60)
ms:contentKeyID: 62207784
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetListingAvailableQuantitiesRequest.ProductIds
dev_langs:
- CSharp
- C++
- VB
---

# ProductIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the product identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductIds As ReadOnlyCollection(Of Long)
    Get
    Private Set
'Usage
Dim instance As GetListingAvailableQuantitiesRequest
Dim value As ReadOnlyCollection(Of Long)

value = instance.ProductIds
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<long> ProductIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<long long>^ ProductIds {
    ReadOnlyCollection<long long>^ get ();
    private: void set (ReadOnlyCollection<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetListingAvailableQuantitiesRequest Class](getlistingavailablequantitiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

