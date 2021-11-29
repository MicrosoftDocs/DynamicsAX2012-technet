---
title: SaveDropAndDeclareServiceRequest.TenderDetails Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TenderDetails Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveDropAndDeclareServiceRequest.TenderDetails
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savedropanddeclareservicerequest.tenderdetails(v=AX.60)
ms:contentKeyID: 62210748
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveDropAndDeclareServiceRequest.TenderDetails
dev_langs:
- CSharp
- C++
- VB
---

# TenderDetails Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tender details of the transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderDetails As IEnumerable(Of TenderDetail)
    Get
    Set
'Usage
Dim instance As SaveDropAndDeclareServiceRequest
Dim value As IEnumerable(Of TenderDetail)

value = instance.TenderDetails

instance.TenderDetails = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<TenderDetail> TenderDetails { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<TenderDetail^>^ TenderDetails {
    IEnumerable<TenderDetail^>^ get ();
    void set (IEnumerable<TenderDetail^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TenderDetail](tenderdetail-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[SaveDropAndDeclareServiceRequest Class](savedropanddeclareservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

