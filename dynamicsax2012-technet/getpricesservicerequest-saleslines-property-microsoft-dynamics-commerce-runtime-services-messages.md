---
title: GetPricesServiceRequest.SalesLines Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SalesLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest.SalesLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpricesservicerequest.saleslines(v=AX.60)
ms:contentKeyID: 62209813
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest.SalesLines
dev_langs:
- CSharp
- C++
- VB
---

# SalesLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item lines which need to have their prices calculated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property SalesLines As IEnumerable(Of SalesLine)
    Get
    Private Set
'Usage
Dim instance As GetPricesServiceRequest
Dim value As IEnumerable(Of SalesLine)

value = instance.SalesLines
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public IEnumerable<SalesLine> SalesLines { get; private set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property IEnumerable<SalesLine^>^ SalesLines {
    IEnumerable<SalesLine^>^ get ();
    private: void set (IEnumerable<SalesLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetPricesServiceRequest Class](getpricesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

