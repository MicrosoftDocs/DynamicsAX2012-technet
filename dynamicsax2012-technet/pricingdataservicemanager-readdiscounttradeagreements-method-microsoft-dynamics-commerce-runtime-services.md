---
title: PricingDataServiceManager.ReadDiscountTradeAgreements Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: ReadDiscountTradeAgreements Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.ReadDiscountTradeAgreements(System.Collections.Generic.ISet{System.String},System.String,System.DateTimeOffset,System.DateTimeOffset,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.readdiscounttradeagreements(v=AX.60)
ms:contentKeyID: 65315834
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.ReadDiscountTradeAgreements
dev_langs:
- CSharp
- C++
- VB
---

# ReadDiscountTradeAgreements Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function ReadDiscountTradeAgreements ( _
    itemIds As ISet(Of String), _
    customerAccount As String, _
    minActiveDate As DateTimeOffset, _
    maxActiveDate As DateTimeOffset, _
    currencyCode As String _
) As ReadOnlyCollection(Of TradeAgreement)
'Usage
Dim instance As PricingDataServiceManager
Dim itemIds As ISet(Of String)
Dim customerAccount As String
Dim minActiveDate As DateTimeOffset
Dim maxActiveDate As DateTimeOffset
Dim currencyCode As String
Dim returnValue As ReadOnlyCollection(Of TradeAgreement)

returnValue = instance.ReadDiscountTradeAgreements(itemIds, _
    customerAccount, minActiveDate, _
    maxActiveDate, currencyCode)
```

``` csharp
public ReadOnlyCollection<TradeAgreement> ReadDiscountTradeAgreements(
    ISet<string> itemIds,
    string customerAccount,
    DateTimeOffset minActiveDate,
    DateTimeOffset maxActiveDate,
    string currencyCode
)
```

``` c++
public:
virtual ReadOnlyCollection<TradeAgreement^>^ ReadDiscountTradeAgreements(
    ISet<String^>^ itemIds, 
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

#### Implements

[IPricingDataManagerV2.ReadDiscountTradeAgreements(ISet\<String\>, String, DateTimeOffset, DateTimeOffset, String)](ipricingdatamanagerv2-readdiscounttradeagreements-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

