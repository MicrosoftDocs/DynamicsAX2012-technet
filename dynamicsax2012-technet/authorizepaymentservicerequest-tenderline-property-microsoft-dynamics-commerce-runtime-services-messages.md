---
title: AuthorizePaymentServiceRequest.TenderLine Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TenderLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceRequest.TenderLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.authorizepaymentservicerequest.tenderline(v=AX.60)
ms:contentKeyID: 62215082
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceRequest.TenderLine
dev_langs:
- CSharp
- C++
- VB
---

# TenderLine Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tender line associated with the card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderLine As TenderLine
    Get
    Set
'Usage
Dim instance As AuthorizePaymentServiceRequest
Dim value As TenderLine

value = instance.TenderLine

instance.TenderLine = value
```

``` csharp
[DataMemberAttribute]
public TenderLine TenderLine { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property TenderLine^ TenderLine {
    TenderLine^ get ();
    void set (TenderLine^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[AuthorizePaymentServiceRequest Class](authorizepaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

