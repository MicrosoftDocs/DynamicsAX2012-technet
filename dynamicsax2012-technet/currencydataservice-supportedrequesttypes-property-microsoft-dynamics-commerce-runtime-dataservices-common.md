---
title: CurrencyDataService.SupportedRequestTypes Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Common)
TOCTitle: SupportedRequestTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CurrencyDataService.SupportedRequestTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.common.currencydataservice.supportedrequesttypes(v=AX.60)
ms:contentKeyID: 65321008
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CurrencyDataService.SupportedRequestTypes
dev_langs:
- CSharp
- C++
- VB
---

# SupportedRequestTypes Property

Gets the collection of supported request types by this handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common](microsoft-dynamics-commerce-runtime-dataservices-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices (in Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property SupportedRequestTypes As IEnumerable(Of Type)
    Get
'Usage
Dim instance As CurrencyDataService
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
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

#### Implements

[IRequestHandler.SupportedRequestTypes](irequesthandler-supportedrequesttypes-property-microsoft-dynamics-commerce-runtime-workflow.md)  

## See Also

#### Reference

[CurrencyDataService Class](currencydataservice-class-microsoft-dynamics-commerce-runtime-dataservices-common.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Common Namespace](microsoft-dynamics-commerce-runtime-dataservices-common-namespace.md)

