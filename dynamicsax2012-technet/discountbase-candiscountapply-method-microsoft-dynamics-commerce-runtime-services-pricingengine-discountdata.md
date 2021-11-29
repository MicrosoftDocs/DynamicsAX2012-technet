---
title: DiscountBase.CanDiscountApply Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: CanDiscountApply Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.CanDiscountApply(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.Collections.Generic.IEnumerable{System.Int64},System.String,Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.candiscountapply(v=AX.60)
ms:contentKeyID: 62214580
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.CanDiscountApply
dev_langs:
- CSharp
- C++
- VB
---

# CanDiscountApply Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Determines if this discount can possibly apply to the specified transaction by examining all of the triggering rules not related to the actual line items on the transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Function CanDiscountApply ( _
    transaction As SalesTransaction, _
    storePriceGroups As IEnumerable(Of Long), _
    currencyCode As String, _
    pricingDataManager As IPricingDataManagerV2, _
    isReturn As Boolean, _
    priceContext As PriceContext _
) As Boolean
'Usage
Dim transaction As SalesTransaction
Dim storePriceGroups As IEnumerable(Of Long)
Dim currencyCode As String
Dim pricingDataManager As IPricingDataManagerV2
Dim isReturn As Boolean
Dim priceContext As PriceContext
Dim returnValue As Boolean

returnValue = Me.CanDiscountApply(transaction, _
    storePriceGroups, currencyCode, _
    pricingDataManager, isReturn, priceContext)
```

``` csharp
protected bool CanDiscountApply(
    SalesTransaction transaction,
    IEnumerable<long> storePriceGroups,
    string currencyCode,
    IPricingDataManagerV2 pricingDataManager,
    bool isReturn,
    PriceContext priceContext
)
```

``` c++
protected:
bool CanDiscountApply(
    SalesTransaction^ transaction, 
    IEnumerable<long long>^ storePriceGroups, 
    String^ currencyCode, 
    IPricingDataManagerV2^ pricingDataManager, 
    bool isReturn, 
    PriceContext^ priceContext
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - storePriceGroups  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - pricingDataManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - isReturn  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the discount could apply if the correct line items exist, false otherwise.  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

