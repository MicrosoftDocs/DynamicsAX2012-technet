---
title: GetExternalShippingRateServiceRequest.SalesLines Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SalesLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExternalShippingRateServiceRequest.SalesLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getexternalshippingrateservicerequest.saleslines(v=AX.60)
ms:contentKeyID: 49824813
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExternalShippingRateServiceRequest.SalesLines
dev_langs:
- CSharp
- C++
- VB
---

# SalesLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesLines As ReadOnlyCollection(Of SalesLine)
    Get
    Private Set
'Usage
Dim instance As GetExternalShippingRateServiceRequest
Dim value As ReadOnlyCollection(Of SalesLine)

value = instance.SalesLines
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<SalesLine> SalesLines { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<SalesLine^>^ SalesLines {
    ReadOnlyCollection<SalesLine^>^ get ();
    private: void set (ReadOnlyCollection<SalesLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetExternalShippingRateServiceRequest Class](getexternalshippingrateservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

