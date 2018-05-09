---
title: GetStockCountJournalServiceResponse.StockCountJournals Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: StockCountJournals Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalServiceResponse.StockCountJournals
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getstockcountjournalserviceresponse.stockcountjournals(v=AX.60)
ms:contentKeyID: 62209406
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalServiceResponse.StockCountJournals
dev_langs:
- CSharp
- C++
- VB
---

# StockCountJournals Property

Gets the collection of stock count journals.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StockCountJournals As IEnumerable(Of StockCountJournal)
    Get
    Private Set
'Usage
Dim instance As GetStockCountJournalServiceResponse
Dim value As IEnumerable(Of StockCountJournal)

value = instance.StockCountJournals
```

``` csharp
[DataMemberAttribute]
public IEnumerable<StockCountJournal> StockCountJournals { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<StockCountJournal^>^ StockCountJournals {
    IEnumerable<StockCountJournal^>^ get ();
    private: void set (IEnumerable<StockCountJournal^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetStockCountJournalServiceResponse Class](getstockcountjournalserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

