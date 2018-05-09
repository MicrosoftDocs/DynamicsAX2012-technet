---
title: GetReceiptServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetReceiptServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.Receipt})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getreceiptserviceresponse.getreceiptserviceresponse(v=AX.60)
ms:contentKeyID: 62210962
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetReceiptServiceResponse Constructor

Initializes a new instance of the GetReceiptServiceResponse class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    receipts As ReadOnlyCollection(Of Receipt) _
)
'Usage
Dim receipts As ReadOnlyCollection(Of Receipt)

Dim instance As New GetReceiptServiceResponse(receipts)
```

``` csharp
public GetReceiptServiceResponse(
    ReadOnlyCollection<Receipt> receipts
)
```

``` c++
public:
GetReceiptServiceResponse(
    ReadOnlyCollection<Receipt^>^ receipts
)
```

#### Parameters

  - receipts  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Receipt](receipt-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetReceiptServiceResponse Class](getreceiptserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

