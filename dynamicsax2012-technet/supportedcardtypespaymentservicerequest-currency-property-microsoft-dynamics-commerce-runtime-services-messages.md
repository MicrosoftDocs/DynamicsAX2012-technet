---
title: SupportedCardTypesPaymentServiceRequest.Currency Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Currency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SupportedCardTypesPaymentServiceRequest.Currency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.supportedcardtypespaymentservicerequest.currency(v=AX.60)
ms:contentKeyID: 62210273
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SupportedCardTypesPaymentServiceRequest.Currency
dev_langs:
- CSharp
- C++
- VB
---

# Currency Property

Gets the currency to be used to get the supported card types.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Currency As String
    Get
    Private Set
'Usage
Dim instance As SupportedCardTypesPaymentServiceRequest
Dim value As String

value = instance.Currency
```

``` csharp
[DataMemberAttribute]
public string Currency { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Currency {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SupportedCardTypesPaymentServiceRequest Class](supportedcardtypespaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

