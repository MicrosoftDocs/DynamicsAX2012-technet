---
title: PricingSqliteDatabaseAccessor.ReadPriceTradeAgreements Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite)
TOCTitle: ReadPriceTradeAgreements Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.PricingSqliteDatabaseAccessor.ReadPriceTradeAgreements(System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.ISet{System.String},System.String,System.DateTimeOffset,System.DateTimeOffset,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlite.pricingsqlitedatabaseaccessor.readpricetradeagreements(v=AX.60)
ms:contentKeyID: 65320056
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.PricingSqliteDatabaseAccessor.ReadPriceTradeAgreements
dev_langs:
- CSharp
- C++
- VB
---

# ReadPriceTradeAgreements Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function ReadPriceTradeAgreements ( _
    itemIds As IEnumerable(Of String), _
    priceGroups As ISet(Of String), _
    customerAccount As String, _
    minActiveDate As DateTimeOffset, _
    maxActiveDate As DateTimeOffset, _
    currencyCode As String _
) As ReadOnlyCollection(Of TradeAgreement)
'Usage
Dim instance As PricingSqliteDatabaseAccessor
Dim itemIds As IEnumerable(Of String)
Dim priceGroups As ISet(Of String)
Dim customerAccount As String
Dim minActiveDate As DateTimeOffset
Dim maxActiveDate As DateTimeOffset
Dim currencyCode As String
Dim returnValue As ReadOnlyCollection(Of TradeAgreement)

returnValue = instance.ReadPriceTradeAgreements(itemIds, _
    priceGroups, customerAccount, minActiveDate, _
    maxActiveDate, currencyCode)
```

``` csharp
public ReadOnlyCollection<TradeAgreement> ReadPriceTradeAgreements(
    IEnumerable<string> itemIds,
    ISet<string> priceGroups,
    string customerAccount,
    DateTimeOffset minActiveDate,
    DateTimeOffset maxActiveDate,
    string currencyCode
)
```

``` c++
public:
ReadOnlyCollection<TradeAgreement^>^ ReadPriceTradeAgreements(
    IEnumerable<String^>^ itemIds, 
    ISet<String^>^ priceGroups, 
    String^ customerAccount, 
    DateTimeOffset minActiveDate, 
    DateTimeOffset maxActiveDate, 
    String^ currencyCode
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - priceGroups  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - customerAccount  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - minActiveDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - maxActiveDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TradeAgreement](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[PricingSqliteDatabaseAccessor Class](pricingsqlitedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)

