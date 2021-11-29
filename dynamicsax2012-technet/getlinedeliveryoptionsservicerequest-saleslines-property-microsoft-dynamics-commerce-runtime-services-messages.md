---
title: GetLineDeliveryOptionsServiceRequest.SalesLines Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SalesLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLineDeliveryOptionsServiceRequest.SalesLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getlinedeliveryoptionsservicerequest.saleslines(v=AX.60)
ms:contentKeyID: 62207800
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLineDeliveryOptionsServiceRequest.SalesLines
dev_langs:
- CSharp
- C++
- VB
---

# SalesLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales lines to get the delivery options for.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesLines As ICollection(Of SalesLine)
    Get
    Private Set
'Usage
Dim instance As GetLineDeliveryOptionsServiceRequest
Dim value As ICollection(Of SalesLine)

value = instance.SalesLines
```

``` csharp
[DataMemberAttribute]
public ICollection<SalesLine> SalesLines { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<SalesLine^>^ SalesLines {
    ICollection<SalesLine^>^ get ();
    private: void set (ICollection<SalesLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## Remarks

If null or empty, all sales lines in the transaction will be used.

## See Also

#### Reference

[GetLineDeliveryOptionsServiceRequest Class](getlinedeliveryoptionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

