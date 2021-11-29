---
title: GetEmailReceiptServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetEmailReceiptServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Receipt})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getemailreceiptserviceresponse.getemailreceiptserviceresponse(v=AX.60)
ms:contentKeyID: 62204767
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetEmailReceiptServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the GetEmailReceiptServiceResponse class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    receipts As IEnumerable(Of Receipt) _
)
'Usage
Dim receipts As IEnumerable(Of Receipt)

Dim instance As New GetEmailReceiptServiceResponse(receipts)
```

``` csharp
public GetEmailReceiptServiceResponse(
    IEnumerable<Receipt> receipts
)
```

``` c++
public:
GetEmailReceiptServiceResponse(
    IEnumerable<Receipt^>^ receipts
)
```

#### Parameters

  - receipts  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Receipt](receipt-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetEmailReceiptServiceResponse Class](getemailreceiptserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

