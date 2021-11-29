---
title: ValidateShippingAddressServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ValidateShippingAddressServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validateshippingaddressservicerequest(v=AX.60)
ms:contentKeyID: 49856540
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# ValidateShippingAddressServiceRequest Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

ValidateAddressRequest class for shipping service.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<KnownTypeAttribute(GetType(Address))> _
<DataContractAttribute> _
Public NotInheritable Class ValidateShippingAddressServiceRequest _
    Inherits ServiceRequest
'Usage
Dim instance As ValidateShippingAddressServiceRequest
```

``` csharp
[KnownTypeAttribute(typeof(Address))]
[DataContractAttribute]
public sealed class ValidateShippingAddressServiceRequest : ServiceRequest
```

``` c++
[KnownTypeAttribute(typeof(Address))]
[DataContractAttribute]
public ref class ValidateShippingAddressServiceRequest sealed : public ServiceRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest](servicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceRequest  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

