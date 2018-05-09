---
title: GetCardPaymentPropertiesServiceResponse.ApprovalCode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ApprovalCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCardPaymentPropertiesServiceResponse.ApprovalCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getcardpaymentpropertiesserviceresponse.approvalcode(v=AX.60)
ms:contentKeyID: 65319175
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCardPaymentPropertiesServiceResponse.ApprovalCode
dev_langs:
- CSharp
- C++
- VB
---

# ApprovalCode Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ApprovalCode As String
    Get
    Private Set
'Usage
Dim instance As GetCardPaymentPropertiesServiceResponse
Dim value As String

value = instance.ApprovalCode
```

``` csharp
[DataMemberAttribute]
public string ApprovalCode { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ApprovalCode {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetCardPaymentPropertiesServiceResponse Class](getcardpaymentpropertiesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

