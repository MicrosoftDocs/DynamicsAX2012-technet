---
title: ValidateShippingAddressServiceRequest.SuggestAddress Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SuggestAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceRequest.SuggestAddress
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.validateshippingaddressservicerequest.suggestaddress(v=AX.60)
ms:contentKeyID: 49850327
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceRequest.SuggestAddress
dev_langs:
- CSharp
- C++
- VB
---

# SuggestAddress Property

Gets a value indicating whether the receiver is expected to suggest addresses.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SuggestAddress As Boolean
    Get
    Private Set
'Usage
Dim instance As ValidateShippingAddressServiceRequest
Dim value As Boolean

value = instance.SuggestAddress
```

``` csharp
[DataMemberAttribute]
public bool SuggestAddress { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool SuggestAddress {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ValidateShippingAddressServiceRequest Class](validateshippingaddressservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

