---
title: ValidateShippingAddressCarrierServiceResponse Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ValidateShippingAddressCarrierServiceResponse Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressCarrierServiceResponse
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validateshippingaddresscarrierserviceresponse(v=AX.60)
ms:contentKeyID: 49837937
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressCarrierServiceResponse
dev_langs:
- CSharp
- C++
- VB
---

# ValidateShippingAddressCarrierServiceResponse Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

ValidateAddressResponse class that provides feedback if the provided address was valid, and provides list of recommended address if the flag was set in the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public NotInheritable Class ValidateShippingAddressCarrierServiceResponse _
    Inherits Response
'Usage
Dim instance As ValidateShippingAddressCarrierServiceResponse
```

``` csharp
[DataContractAttribute]
public sealed class ValidateShippingAddressCarrierServiceResponse : Response
```

``` c++
[DataContractAttribute]
public ref class ValidateShippingAddressCarrierServiceResponse sealed : public Response
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressCarrierServiceResponse  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

