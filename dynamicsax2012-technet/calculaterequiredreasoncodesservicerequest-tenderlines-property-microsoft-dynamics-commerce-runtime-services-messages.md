---
title: CalculateRequiredReasonCodesServiceRequest.TenderLines Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TenderLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceRequest.TenderLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculaterequiredreasoncodesservicerequest.tenderlines(v=AX.60)
ms:contentKeyID: 62214524
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceRequest.TenderLines
dev_langs:
- CSharp
- C++
- VB
---

# TenderLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tender lines to calculate on.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderLines As IEnumerable(Of TenderLine)
    Get
    Private Set
'Usage
Dim instance As CalculateRequiredReasonCodesServiceRequest
Dim value As IEnumerable(Of TenderLine)

value = instance.TenderLines
```

``` csharp
[DataMemberAttribute]
public IEnumerable<TenderLine> TenderLines { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<TenderLine^>^ TenderLines {
    IEnumerable<TenderLine^>^ get ();
    private: void set (IEnumerable<TenderLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[CalculateRequiredReasonCodesServiceRequest Class](calculaterequiredreasoncodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

