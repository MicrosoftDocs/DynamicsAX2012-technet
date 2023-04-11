---
title: ValidateShippingAddressCarrierServiceResponse.IsAddressValid Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IsAddressValid Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressCarrierServiceResponse.IsAddressValid
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validateshippingaddresscarrierserviceresponse.isaddressvalid(v=AX.60)
ms:contentKeyID: 49840675
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressCarrierServiceResponse.IsAddressValid
dev_langs:
- CSharp
- C++
- VB
---

# IsAddressValid Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the address that was passed in the request was valid.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsAddressValid As Boolean
    Get
    Private Set
'Usage
Dim instance As ValidateShippingAddressCarrierServiceResponse
Dim value As Boolean

value = instance.IsAddressValid
```

``` csharp
[DataMemberAttribute]
public bool IsAddressValid { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsAddressValid {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ValidateShippingAddressCarrierServiceResponse Class](validateshippingaddresscarrierserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

