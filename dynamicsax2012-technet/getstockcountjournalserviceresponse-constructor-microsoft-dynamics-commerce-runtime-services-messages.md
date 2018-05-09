---
title: GetStockCountJournalServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetStockCountJournalServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getstockcountjournalserviceresponse.getstockcountjournalserviceresponse(v=AX.60)
ms:contentKeyID: 62211724
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetStockCountJournalServiceResponse Constructor

Initializes a new instance of the [GetStockCountJournalServiceResponse](getstockcountjournalserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    journals As IEnumerable(Of StockCountJournal) _
)
'Usage
Dim journals As IEnumerable(Of StockCountJournal)

Dim instance As New GetStockCountJournalServiceResponse(journals)
```

``` csharp
public GetStockCountJournalServiceResponse(
    IEnumerable<StockCountJournal> journals
)
```

``` c++
public:
GetStockCountJournalServiceResponse(
    IEnumerable<StockCountJournal^>^ journals
)
```

#### Parameters

  - journals  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetStockCountJournalServiceResponse Class](getstockcountjournalserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

