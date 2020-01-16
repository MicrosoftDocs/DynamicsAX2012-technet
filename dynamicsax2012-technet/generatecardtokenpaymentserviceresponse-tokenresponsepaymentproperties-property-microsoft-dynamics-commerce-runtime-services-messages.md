---
title: GenerateCardTokenPaymentServiceResponse.TokenResponsePaymentProperties Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TokenResponsePaymentProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GenerateCardTokenPaymentServiceResponse.TokenResponsePaymentProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.generatecardtokenpaymentserviceresponse.tokenresponsepaymentproperties(v=AX.60)
ms:contentKeyID: 65322954
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GenerateCardTokenPaymentServiceResponse.TokenResponsePaymentProperties
dev_langs:
- CSharp
- C++
- VB
---

# TokenResponsePaymentProperties Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TokenResponsePaymentProperties As String
    Get
    Private Set
'Usage
Dim instance As GenerateCardTokenPaymentServiceResponse
Dim value As String

value = instance.TokenResponsePaymentProperties
```

``` csharp
[DataMemberAttribute]
public string TokenResponsePaymentProperties { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TokenResponsePaymentProperties {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GenerateCardTokenPaymentServiceResponse Class](generatecardtokenpaymentserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

