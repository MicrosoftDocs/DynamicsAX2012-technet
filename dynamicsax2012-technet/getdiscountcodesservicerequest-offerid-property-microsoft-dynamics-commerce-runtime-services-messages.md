---
title: GetDiscountCodesServiceRequest.OfferId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: OfferId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceRequest.OfferId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getdiscountcodesservicerequest.offerid(v=AX.60)
ms:contentKeyID: 62211747
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceRequest.OfferId
dev_langs:
- CSharp
- C++
- VB
---

# OfferId Property

Gets the offer id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OfferId As String
    Get
    Private Set
'Usage
Dim instance As GetDiscountCodesServiceRequest
Dim value As String

value = instance.OfferId
```

``` csharp
[DataMemberAttribute]
public string OfferId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ OfferId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetDiscountCodesServiceRequest Class](getdiscountcodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

