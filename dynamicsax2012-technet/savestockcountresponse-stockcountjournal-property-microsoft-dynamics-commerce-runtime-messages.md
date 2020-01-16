---
title: SaveStockCountResponse.StockCountJournal Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StockCountJournal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStockCountResponse.StockCountJournal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savestockcountresponse.stockcountjournal(v=AX.60)
ms:contentKeyID: 62213246
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStockCountResponse.StockCountJournal
dev_langs:
- CSharp
- C++
- VB
---

# StockCountJournal Property

Gets the StockCountJournal value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StockCountJournal As StockCountJournal
    Get
    Private Set
'Usage
Dim instance As SaveStockCountResponse
Dim value As StockCountJournal

value = instance.StockCountJournal
```

``` csharp
[DataMemberAttribute]
public StockCountJournal StockCountJournal { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property StockCountJournal^ StockCountJournal {
    StockCountJournal^ get ();
    private: void set (StockCountJournal^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveStockCountResponse Class](savestockcountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

