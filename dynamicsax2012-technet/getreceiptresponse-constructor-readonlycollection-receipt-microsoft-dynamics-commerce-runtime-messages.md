---
title: GetReceiptResponse Constructor (ReadOnlyCollection(Receipt)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetReceiptResponse Constructor (ReadOnlyCollection(Receipt))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.Receipt})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreceiptresponse.getreceiptresponse(v=AX.60)
ms:contentKeyID: 62202721
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReceiptResponse Constructor (ReadOnlyCollection(Receipt))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the GetReceiptResponse class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    receipts As ReadOnlyCollection(Of Receipt) _
)
'Usage
Dim receipts As ReadOnlyCollection(Of Receipt)

Dim instance As New GetReceiptResponse(receipts)
```

``` csharp
public GetReceiptResponse(
    ReadOnlyCollection<Receipt> receipts
)
```

``` c++
public:
GetReceiptResponse(
    ReadOnlyCollection<Receipt^>^ receipts
)
```

#### Parameters

  - receipts  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Receipt](receipt-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetReceiptResponse Class](getreceiptresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetReceiptResponse Overload](getreceiptresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

