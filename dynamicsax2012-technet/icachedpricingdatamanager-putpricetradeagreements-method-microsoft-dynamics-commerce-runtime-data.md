---
title: ICachedPricingDataManager.PutPriceTradeAgreements Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutPriceTradeAgreements Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutPriceTradeAgreements(System.Collections.Generic.ISet{System.String},System.Collections.Generic.ISet{System.String},System.String,System.DateTimeOffset,System.DateTimeOffset,System.String,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putpricetradeagreements(v=AX.60)
ms:contentKeyID: 62212512
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutPriceTradeAgreements
dev_langs:
- CSharp
- C++
- VB
---

# PutPriceTradeAgreements Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Store the superset of price trade agreements which could apply to all of these items and customer for the given date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutPriceTradeAgreements ( _
    itemIds As ISet(Of String), _
    priceGroups As ISet(Of String), _
    customerAccount As String, _
    minActiveDate As DateTimeOffset, _
    maxActiveDate As DateTimeOffset, _
    currencyCode As String, _
    result As ReadOnlyCollection(Of TradeAgreement) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim itemIds As ISet(Of String)
Dim priceGroups As ISet(Of String)
Dim customerAccount As String
Dim minActiveDate As DateTimeOffset
Dim maxActiveDate As DateTimeOffset
Dim currencyCode As String
Dim result As ReadOnlyCollection(Of TradeAgreement)

instance.PutPriceTradeAgreements(itemIds, _
    priceGroups, customerAccount, minActiveDate, _
    maxActiveDate, currencyCode, result)
```

``` csharp
void PutPriceTradeAgreements(
    ISet<string> itemIds,
    ISet<string> priceGroups,
    string customerAccount,
    DateTimeOffset minActiveDate,
    DateTimeOffset maxActiveDate,
    string currencyCode,
    ReadOnlyCollection<TradeAgreement> result
)
```

``` c++
void PutPriceTradeAgreements(
    ISet<String^>^ itemIds, 
    ISet<String^>^ priceGroups, 
    String^ customerAccount, 
    DateTimeOffset minActiveDate, 
    DateTimeOffset maxActiveDate, 
    String^ currencyCode, 
    ReadOnlyCollection<TradeAgreement^>^ result
)
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

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TradeAgreement](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

