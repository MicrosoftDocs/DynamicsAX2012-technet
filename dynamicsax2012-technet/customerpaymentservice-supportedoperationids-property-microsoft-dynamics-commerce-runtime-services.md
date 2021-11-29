---
title: CustomerPaymentService.SupportedOperationIds Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: SupportedOperationIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerPaymentService.SupportedOperationIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerpaymentservice.supportedoperationids(v=AX.60)
ms:contentKeyID: 65319075
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerPaymentService.SupportedOperationIds
dev_langs:
- CSharp
- C++
- VB
---

# SupportedOperationIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property SupportedOperationIds As IEnumerable(Of Integer)
    Get
'Usage
Dim instance As CustomerPaymentService
Dim value As IEnumerable(Of Integer)

value = instance.SupportedOperationIds
```

``` csharp
public IEnumerable<int> SupportedOperationIds { get; }
```

``` c++
public:
virtual property IEnumerable<int>^ SupportedOperationIds {
    IEnumerable<int>^ get () sealed;
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))\>  

#### Implements

[IOperationRequestHandler.SupportedOperationIds](ioperationrequesthandler-supportedoperationids-property-microsoft-dynamics-commerce-runtime-handlers.md)  

## See Also

#### Reference

[CustomerPaymentService Class](customerpaymentservice-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

