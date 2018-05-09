---
title: ValidateShippingAddressServiceResponse Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ValidateShippingAddressServiceResponse Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceResponse
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.validateshippingaddressserviceresponse(v=AX.60)
ms:contentKeyID: 49825241
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceResponse
dev_langs:
- CSharp
- C++
- VB
---

# ValidateShippingAddressServiceResponse Class

ValidateAddressResponse class that provides feedback if the provided address was valid, and provides list of recommended address if the flag was set in the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public NotInheritable Class ValidateShippingAddressServiceResponse _
    Inherits Response
'Usage
Dim instance As ValidateShippingAddressServiceResponse
```

``` csharp
[DataContractAttribute]
public sealed class ValidateShippingAddressServiceResponse : Response
```

``` c++
[DataContractAttribute]
public ref class ValidateShippingAddressServiceResponse sealed : public Response
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceResponse  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

