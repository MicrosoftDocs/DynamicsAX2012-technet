---
title: GetPaymentRoundedValueServiceRequest.IsChange Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IsChange Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPaymentRoundedValueServiceRequest.IsChange
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpaymentroundedvalueservicerequest.ischange(v=AX.60)
ms:contentKeyID: 65316343
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPaymentRoundedValueServiceRequest.IsChange
dev_langs:
- CSharp
- C++
- VB
---

# IsChange Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsChange As Boolean
    Get
    Private Set
'Usage
Dim instance As GetPaymentRoundedValueServiceRequest
Dim value As Boolean

value = instance.IsChange
```

``` csharp
[DataMemberAttribute]
public bool IsChange { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsChange {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetPaymentRoundedValueServiceRequest Class](getpaymentroundedvalueservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

