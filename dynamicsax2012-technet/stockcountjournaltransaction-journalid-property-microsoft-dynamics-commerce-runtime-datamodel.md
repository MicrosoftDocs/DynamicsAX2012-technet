---
title: StockCountJournalTransaction.JournalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: JournalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.JournalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournaltransaction.journalid(v=AX.60)
ms:contentKeyID: 62205377
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.JournalId
dev_langs:
- CSharp
- C++
- VB
---

# JournalId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the journal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("JOURNALID")> _
<DataMemberAttribute> _
Public Property JournalId As String
    Get
    Set
'Usage
Dim instance As StockCountJournalTransaction
Dim value As String

value = instance.JournalId

instance.JournalId = value
```

``` csharp
[ColumnAttribute("JOURNALID")]
[DataMemberAttribute]
public string JournalId { get; set; }
```

``` c++
[ColumnAttribute(L"JOURNALID")]
[DataMemberAttribute]
public:
property String^ JournalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[StockCountJournalTransaction Class](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

