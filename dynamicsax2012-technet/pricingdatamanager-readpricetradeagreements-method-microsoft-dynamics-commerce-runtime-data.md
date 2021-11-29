---
title: PricingDataManager.ReadPriceTradeAgreements Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ReadPriceTradeAgreements Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.ReadPriceTradeAgreements(System.Collections.Generic.ISet{System.String},System.Collections.Generic.ISet{System.String},System.String,System.DateTimeOffset,System.DateTimeOffset,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatamanager.readpricetradeagreements(v=AX.60)
ms:contentKeyID: 62210818
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.ReadPriceTradeAgreements
dev_langs:
- CSharp
- C++
- VB
---

# ReadPriceTradeAgreements Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Fetch the superset of trade agreements which could apply to all of these items and customer for the given date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function ReadPriceTradeAgreements ( _
    itemIds As ISet(Of String), _
    priceGroups As ISet(Of String), _
    customerAccount As String, _
    minActiveDate As DateTimeOffset, _
    maxActiveDate As DateTimeOffset, _
    currencyCode As String _
) As ReadOnlyCollection(Of TradeAgreement)
'Usage
Dim instance As PricingDataManager
Dim itemIds As ISet(Of String)
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
    ISet<string> itemIds,
    ISet<string> priceGroups,
    string customerAccount,
    DateTimeOffset minActiveDate,
    DateTimeOffset maxActiveDate,
    string currencyCode
)
```

``` c++
public:
virtual ReadOnlyCollection<TradeAgreement^>^ ReadPriceTradeAgreements(
    ISet<String^>^ itemIds, 
    ISet<String^>^ priceGroups, 
    String^ customerAccount, 
    DateTimeOffset minActiveDate, 
    DateTimeOffset maxActiveDate, 
    String^ currencyCode
) sealed
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

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
Collection of trade agreements which may be applied to the given items.  

#### Implements

[IPricingDataManagerV2.ReadPriceTradeAgreements(ISet\<String\>, ISet\<String\>, String, DateTimeOffset, DateTimeOffset, String)](ipricingdatamanagerv2-readpricetradeagreements-method-microsoft-dynamics-commerce-runtime-data.md)  

## Remarks

This method may be called in a publishing context, when it may deal with thousands of items. Caching is suspended for these scenarios.

## See Also

#### Reference

[PricingDataManager Class](pricingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

