---
title: CustomerServiceBase.UpdateAddresses Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: UpdateAddresses Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase.UpdateAddresses(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Address})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.customerservicebase.updateaddresses(v=AX.60)
ms:contentKeyID: 65316437
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerServiceBase.UpdateAddresses
dev_langs:
- CSharp
- C++
- VB
---

# UpdateAddresses Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function UpdateAddresses ( _
    addresses As IEnumerable(Of Address) _
) As NullResponse
'Usage
Dim instance As CustomerServiceBase
Dim addresses As IEnumerable(Of Address)
Dim returnValue As NullResponse

returnValue = instance.UpdateAddresses(addresses)
```

``` csharp
public virtual NullResponse UpdateAddresses(
    IEnumerable<Address> addresses
)
```

``` c++
public:
virtual NullResponse^ UpdateAddresses(
    IEnumerable<Address^>^ addresses
)
```

#### Parameters

  - addresses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Address](address-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.NullResponse](nullresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[ICustomerService.UpdateAddresses(IEnumerable\<Address\>)](icustomerservice-updateaddresses-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[CustomerServiceBase Class](customerservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

