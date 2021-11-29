---
title: ValidateShippingAddressServiceResponse.RecommendedAddresses Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: RecommendedAddresses Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceResponse.RecommendedAddresses
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validateshippingaddressserviceresponse.recommendedaddresses(v=AX.60)
ms:contentKeyID: 49851934
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceResponse.RecommendedAddresses
dev_langs:
- CSharp
- C++
- VB
---

# RecommendedAddresses Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a collection of valid addresses that are recommended by the shipping carrier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RecommendedAddresses As ReadOnlyCollection(Of Address)
    Get
    Private Set
'Usage
Dim instance As ValidateShippingAddressServiceResponse
Dim value As ReadOnlyCollection(Of Address)

value = instance.RecommendedAddresses
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Address> RecommendedAddresses { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Address^>^ RecommendedAddresses {
    ReadOnlyCollection<Address^>^ get ();
    private: void set (ReadOnlyCollection<Address^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[ValidateShippingAddressServiceResponse Class](validateshippingaddressserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

