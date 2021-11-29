---
title: AddressCollectionResponse.Addresses Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: Addresses Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.AddressCollectionResponse.Addresses
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.addresscollectionresponse.addresses(v=AX.60)
ms:contentKeyID: 65316143
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.AddressCollectionResponse.Addresses
dev_langs:
- CSharp
- C++
- VB
---

# Addresses Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Addresses As Collection(Of Address)
    Get
    Friend Set
'Usage
Dim instance As AddressCollectionResponse
Dim value As Collection(Of Address)

value = instance.Addresses
```

``` csharp
[DataMemberAttribute]
public Collection<Address> Addresses { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<Address^>^ Addresses {
    Collection<Address^>^ get ();
    internal: void set (Collection<Address^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[Address](address-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[AddressCollectionResponse Class](addresscollectionresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

