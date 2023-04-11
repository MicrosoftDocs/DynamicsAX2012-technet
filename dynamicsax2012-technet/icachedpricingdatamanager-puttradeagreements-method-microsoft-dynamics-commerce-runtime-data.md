---
title: ICachedPricingDataManager.PutTradeAgreements Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutTradeAgreements Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutTradeAgreements(Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType,Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode,System.Collections.Generic.IEnumerable{System.String},System.String,System.String,System.Decimal,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant,System.DateTimeOffset,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.puttradeagreements(v=AX.60)
ms:contentKeyID: 62203247
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutTradeAgreements
dev_langs:
- CSharp
- C++
- VB
---

# PutTradeAgreements Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This function retrieves all possible price agreements for the given args (item, customer, currency, etc), item relation code (item/group/all), and account relation code (customer/price group/all).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutTradeAgreements ( _
    agreementType As PriceDiscountType, _
    itemCode As PriceDiscountItemCode, _
    itemRelation As String, _
    accountCode As PriceDiscountAccountCode, _
    accountRelations As IEnumerable(Of String), _
    unitId As String, _
    currencyCode As String, _
    quantity As Decimal, _
    variant As ProductVariant, _
    activeDate As DateTimeOffset, _
    result As ReadOnlyCollection(Of TradeAgreement) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim agreementType As PriceDiscountType
Dim itemCode As PriceDiscountItemCode
Dim itemRelation As String
Dim accountCode As PriceDiscountAccountCode
Dim accountRelations As IEnumerable(Of String)
Dim unitId As String
Dim currencyCode As String
Dim quantity As Decimal
Dim variant As ProductVariant
Dim activeDate As DateTimeOffset
Dim result As ReadOnlyCollection(Of TradeAgreement)

instance.PutTradeAgreements(agreementType, _
    itemCode, itemRelation, accountCode, _
    accountRelations, unitId, currencyCode, _
    quantity, variant, activeDate, result)
```

``` csharp
void PutTradeAgreements(
    PriceDiscountType agreementType,
    PriceDiscountItemCode itemCode,
    string itemRelation,
    PriceDiscountAccountCode accountCode,
    IEnumerable<string> accountRelations,
    string unitId,
    string currencyCode,
    decimal quantity,
    ProductVariant variant,
    DateTimeOffset activeDate,
    ReadOnlyCollection<TradeAgreement> result
)
```

``` c++
void PutTradeAgreements(
    PriceDiscountType agreementType, 
    PriceDiscountItemCode itemCode, 
    String^ itemRelation, 
    PriceDiscountAccountCode accountCode, 
    IEnumerable<String^>^ accountRelations, 
    String^ unitId, 
    String^ currencyCode, 
    Decimal quantity, 
    ProductVariant^ variant, 
    DateTimeOffset activeDate, 
    ReadOnlyCollection<TradeAgreement^>^ result
)
```

#### Parameters

  - agreementType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType](pricediscounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemCode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode](pricediscountitemcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemRelation  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - accountCode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode](pricediscountaccountcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - accountRelations  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - unitId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - variant  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - activeDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TradeAgreement](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

