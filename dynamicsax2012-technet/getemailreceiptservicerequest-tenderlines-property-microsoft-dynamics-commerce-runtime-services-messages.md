---
title: GetEmailReceiptServiceRequest.TenderLines Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TenderLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceRequest.TenderLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getemailreceiptservicerequest.tenderlines(v=AX.60)
ms:contentKeyID: 62207948
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceRequest.TenderLines
dev_langs:
- CSharp
- C++
- VB
---

# TenderLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tender lines associated with an order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderLines As ReadOnlyCollection(Of TenderLine)
    Get
    Private Set
'Usage
Dim instance As GetEmailReceiptServiceRequest
Dim value As ReadOnlyCollection(Of TenderLine)

value = instance.TenderLines
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<TenderLine> TenderLines { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<TenderLine^>^ TenderLines {
    ReadOnlyCollection<TenderLine^>^ get ();
    private: void set (ReadOnlyCollection<TenderLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetEmailReceiptServiceRequest Class](getemailreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

