---
title: GetChangePaymentServiceRequest.ChangeTenderTypeId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ChangeTenderTypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangePaymentServiceRequest.ChangeTenderTypeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getchangepaymentservicerequest.changetendertypeid(v=AX.60)
ms:contentKeyID: 62212160
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangePaymentServiceRequest.ChangeTenderTypeId
dev_langs:
- CSharp
- C++
- VB
---

# ChangeTenderTypeId Property

Gets or sets the tender type identifier of the change.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChangeTenderTypeId As String
    Get
    Set
'Usage
Dim instance As GetChangePaymentServiceRequest
Dim value As String

value = instance.ChangeTenderTypeId

instance.ChangeTenderTypeId = value
```

``` csharp
[DataMemberAttribute]
public string ChangeTenderTypeId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ChangeTenderTypeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetChangePaymentServiceRequest Class](getchangepaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

