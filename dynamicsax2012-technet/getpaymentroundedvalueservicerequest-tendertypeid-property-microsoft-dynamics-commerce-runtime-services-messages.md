---
title: GetPaymentRoundedValueServiceRequest.TenderTypeId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TenderTypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPaymentRoundedValueServiceRequest.TenderTypeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpaymentroundedvalueservicerequest.tendertypeid(v=AX.60)
ms:contentKeyID: 65322292
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPaymentRoundedValueServiceRequest.TenderTypeId
dev_langs:
- CSharp
- C++
- VB
---

# TenderTypeId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property TenderTypeId As String
    Get
    Private Set
'Usage
Dim instance As GetPaymentRoundedValueServiceRequest
Dim value As String

value = instance.TenderTypeId
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public string TenderTypeId { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property String^ TenderTypeId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetPaymentRoundedValueServiceRequest Class](getpaymentroundedvalueservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

