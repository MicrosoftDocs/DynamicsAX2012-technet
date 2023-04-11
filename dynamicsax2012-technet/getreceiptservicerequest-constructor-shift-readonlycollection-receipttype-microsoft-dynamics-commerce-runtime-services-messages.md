---
title: GetReceiptServiceRequest Constructor (Shift, ReadOnlyCollection(ReceiptType)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetReceiptServiceRequest Constructor (Shift, ReadOnlyCollection(ReceiptType))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreceiptservicerequest.getreceiptservicerequest(v=AX.60)
ms:contentKeyID: 65317379
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReceiptServiceRequest Constructor (Shift, ReadOnlyCollection(ReceiptType))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    shiftDetails As Shift, _
    receiptTypes As ReadOnlyCollection(Of ReceiptType) _
)
'Usage
Dim shiftDetails As Shift
Dim receiptTypes As ReadOnlyCollection(Of ReceiptType)

Dim instance As New GetReceiptServiceRequest(shiftDetails, _
    receiptTypes)
```

``` csharp
public GetReceiptServiceRequest(
    Shift shiftDetails,
    ReadOnlyCollection<ReceiptType> receiptTypes
)
```

``` c++
public:
GetReceiptServiceRequest(
    Shift^ shiftDetails, 
    ReadOnlyCollection<ReceiptType>^ receiptTypes
)
```

#### Parameters

  - shiftDetails  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - receiptTypes  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetReceiptServiceRequest Class](getreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetReceiptServiceRequest Overload](getreceiptservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

