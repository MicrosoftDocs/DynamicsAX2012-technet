---
title: ReceiptService.SupportedRequestTypes Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: SupportedRequestTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.ReceiptService.SupportedRequestTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.receiptservice.supportedrequesttypes(v=AX.60)
ms:contentKeyID: 65320443
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.ReceiptService.SupportedRequestTypes
dev_langs:
- CSharp
- C++
- VB
---

# SupportedRequestTypes Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property SupportedRequestTypes As IEnumerable(Of Type)
    Get
'Usage
Dim instance As ReceiptService
Dim value As IEnumerable(Of Type)

value = instance.SupportedRequestTypes
```

``` csharp
public IEnumerable<Type> SupportedRequestTypes { get; }
```

``` c++
public:
virtual property IEnumerable<Type^>^ SupportedRequestTypes {
    IEnumerable<Type^>^ get () sealed;
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))\>  

#### Implements

[IRequestHandler.SupportedRequestTypes](irequesthandler-supportedrequesttypes-property-microsoft-dynamics-commerce-runtime-workflow.md)  

## See Also

#### Reference

[ReceiptService Class](receiptservice-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

