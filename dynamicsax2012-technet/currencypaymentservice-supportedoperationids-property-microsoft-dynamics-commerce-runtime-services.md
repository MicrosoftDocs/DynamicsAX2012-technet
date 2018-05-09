---
title: CurrencyPaymentService.SupportedOperationIds Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: SupportedOperationIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CurrencyPaymentService.SupportedOperationIds
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.currencypaymentservice.supportedoperationids(v=AX.60)
ms:contentKeyID: 65319458
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CurrencyPaymentService.SupportedOperationIds
dev_langs:
- CSharp
- C++
- VB
---

# SupportedOperationIds Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property SupportedOperationIds As IEnumerable(Of Integer)
    Get
'Usage
Dim instance As CurrencyPaymentService
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

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))\>  

#### Implements

[IOperationRequestHandler.SupportedOperationIds](ioperationrequesthandler-supportedoperationids-property-microsoft-dynamics-commerce-runtime-handlers.md)  

## See Also

#### Reference

[CurrencyPaymentService Class](currencypaymentservice-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

