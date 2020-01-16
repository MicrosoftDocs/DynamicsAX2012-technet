---
title: SalesTransactionConverter.ConvertToData Method (IEnumerable(SalesTransaction)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ConvertToData Method (IEnumerable(SalesTransaction))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionConverter.ConvertToData(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salestransactionconverter.converttodata(v=AX.60)
ms:contentKeyID: 62208089
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ConvertToData Method (IEnumerable(SalesTransaction))

Converts a collection of sales transactions to a collection of their database representation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertToData ( _
    salesTransactions As IEnumerable(Of SalesTransaction) _
) As ReadOnlyCollection(Of SalesTransactionData)
'Usage
Dim salesTransactions As IEnumerable(Of SalesTransaction)
Dim returnValue As ReadOnlyCollection(Of SalesTransactionData)

returnValue = SalesTransactionConverter.ConvertToData(salesTransactions)
```

``` csharp
public static ReadOnlyCollection<SalesTransactionData> ConvertToData(
    IEnumerable<SalesTransaction> salesTransactions
)
```

``` c++
public:
static ReadOnlyCollection<SalesTransactionData^>^ ConvertToData(
    IEnumerable<SalesTransaction^>^ salesTransactions
)
```

#### Parameters

  - salesTransactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesTransactionData](salestransactiondata-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of sales transactions database representation.  

## See Also

#### Reference

[SalesTransactionConverter Class](salestransactionconverter-class-microsoft-dynamics-commerce-runtime-data.md)

[ConvertToData Overload](salestransactionconverter-converttodata-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

