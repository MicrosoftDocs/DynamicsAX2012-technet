---
title: SyncStockCountJournalsFromAxServiceResponse.StockCountJournals Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: StockCountJournals Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountJournalsFromAxServiceResponse.StockCountJournals
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.syncstockcountjournalsfromaxserviceresponse.stockcountjournals(v=AX.60)
ms:contentKeyID: 62210095
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountJournalsFromAxServiceResponse.StockCountJournals
dev_langs:
- CSharp
- C++
- VB
---

# StockCountJournals Property

Gets the StockCountJournals collection value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StockCountJournals As ReadOnlyCollection(Of StockCountJournal)
    Get
    Private Set
'Usage
Dim instance As SyncStockCountJournalsFromAxServiceResponse
Dim value As ReadOnlyCollection(Of StockCountJournal)

value = instance.StockCountJournals
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<StockCountJournal> StockCountJournals { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<StockCountJournal^>^ StockCountJournals {
    ReadOnlyCollection<StockCountJournal^>^ get ();
    private: void set (ReadOnlyCollection<StockCountJournal^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[SyncStockCountJournalsFromAxServiceResponse Class](syncstockcountjournalsfromaxserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

