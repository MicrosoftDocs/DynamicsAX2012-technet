---
title: SyncStockCountResponse.StockCountJournals Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StockCountJournals Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SyncStockCountResponse.StockCountJournals
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.syncstockcountresponse.stockcountjournals(v=AX.60)
ms:contentKeyID: 62214648
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SyncStockCountResponse.StockCountJournals
dev_langs:
- CSharp
- C++
- VB
---

# StockCountJournals Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the StockCountjournal collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StockCountJournals As ReadOnlyCollection(Of StockCountJournal)
    Get
    Private Set
'Usage
Dim instance As SyncStockCountResponse
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

[SyncStockCountResponse Class](syncstockcountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

