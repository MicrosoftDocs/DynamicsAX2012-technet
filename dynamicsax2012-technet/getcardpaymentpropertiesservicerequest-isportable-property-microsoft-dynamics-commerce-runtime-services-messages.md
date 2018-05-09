---
title: GetCardPaymentPropertiesServiceRequest.IsPortable Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IsPortable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCardPaymentPropertiesServiceRequest.IsPortable
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getcardpaymentpropertiesservicerequest.isportable(v=AX.60)
ms:contentKeyID: 65317014
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCardPaymentPropertiesServiceRequest.IsPortable
dev_langs:
- CSharp
- C++
- VB
---

# IsPortable Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsPortable As Boolean
    Get
    Private Set
'Usage
Dim instance As GetCardPaymentPropertiesServiceRequest
Dim value As Boolean

value = instance.IsPortable
```

``` csharp
[DataMemberAttribute]
public bool IsPortable { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsPortable {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetCardPaymentPropertiesServiceRequest Class](getcardpaymentpropertiesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

