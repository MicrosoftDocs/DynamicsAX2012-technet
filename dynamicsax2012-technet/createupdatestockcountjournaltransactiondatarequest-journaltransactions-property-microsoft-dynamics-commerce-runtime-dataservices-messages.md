---
title: CreateUpdateStockCountJournalTransactionDataRequest.JournalTransactions Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: JournalTransactions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateUpdateStockCountJournalTransactionDataRequest.JournalTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.createupdatestockcountjournaltransactiondatarequest.journaltransactions(v=AX.60)
ms:contentKeyID: 65321338
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateUpdateStockCountJournalTransactionDataRequest.JournalTransactions
dev_langs:
- CSharp
- C++
- VB
---

# JournalTransactions Property

Gets the list of journal transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property JournalTransactions As IEnumerable(Of StockCountJournalTransaction)
    Get
    Private Set
'Usage
Dim instance As CreateUpdateStockCountJournalTransactionDataRequest
Dim value As IEnumerable(Of StockCountJournalTransaction)

value = instance.JournalTransactions
```

``` csharp
[DataMemberAttribute]
public IEnumerable<StockCountJournalTransaction> JournalTransactions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<StockCountJournalTransaction^>^ JournalTransactions {
    IEnumerable<StockCountJournalTransaction^>^ get ();
    private: void set (IEnumerable<StockCountJournalTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[CreateUpdateStockCountJournalTransactionDataRequest Class](createupdatestockcountjournaltransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

