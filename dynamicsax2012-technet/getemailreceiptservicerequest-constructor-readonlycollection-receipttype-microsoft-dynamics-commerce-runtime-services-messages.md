---
title: GetEmailReceiptServiceRequest Constructor (ReadOnlyCollection(ReceiptType)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetEmailReceiptServiceRequest Constructor (ReadOnlyCollection(ReceiptType))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceRequest.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getemailreceiptservicerequest.getemailreceiptservicerequest(v=AX.60)
ms:contentKeyID: 65319848
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetEmailReceiptServiceRequest Constructor (ReadOnlyCollection(ReceiptType))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    receiptTypes As ReadOnlyCollection(Of ReceiptType) _
)
'Usage
Dim receiptTypes As ReadOnlyCollection(Of ReceiptType)

Dim instance As New GetEmailReceiptServiceRequest(receiptTypes)
```

``` csharp
public GetEmailReceiptServiceRequest(
    ReadOnlyCollection<ReceiptType> receiptTypes
)
```

``` c++
public:
GetEmailReceiptServiceRequest(
    ReadOnlyCollection<ReceiptType>^ receiptTypes
)
```

#### Parameters

  - receiptTypes  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetEmailReceiptServiceRequest Class](getemailreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetEmailReceiptServiceRequest Overload](getemailreceiptservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

