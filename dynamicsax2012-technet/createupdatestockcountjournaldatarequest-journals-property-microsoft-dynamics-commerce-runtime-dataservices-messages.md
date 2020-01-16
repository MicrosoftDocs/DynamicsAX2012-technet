---
title: CreateUpdateStockCountJournalDataRequest.Journals Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Journals Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateUpdateStockCountJournalDataRequest.Journals
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.createupdatestockcountjournaldatarequest.journals(v=AX.60)
ms:contentKeyID: 65315730
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateUpdateStockCountJournalDataRequest.Journals
dev_langs:
- CSharp
- C++
- VB
---

# Journals Property

Gets the list of journals.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Journals As IEnumerable(Of StockCountJournal)
    Get
    Private Set
'Usage
Dim instance As CreateUpdateStockCountJournalDataRequest
Dim value As IEnumerable(Of StockCountJournal)

value = instance.Journals
```

``` csharp
[DataMemberAttribute]
public IEnumerable<StockCountJournal> Journals { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<StockCountJournal^>^ Journals {
    IEnumerable<StockCountJournal^>^ get ();
    private: void set (IEnumerable<StockCountJournal^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[CreateUpdateStockCountJournalDataRequest Class](createupdatestockcountjournaldatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

