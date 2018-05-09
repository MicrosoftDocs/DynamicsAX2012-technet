---
title: ICachedPricingDataManager.PutQuantityDiscountLevelByQuantity Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutQuantityDiscountLevelByQuantity Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutQuantityDiscountLevelByQuantity(System.String,System.Decimal,Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putquantitydiscountlevelbyquantity(v=AX.60)
ms:contentKeyID: 62209333
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutQuantityDiscountLevelByQuantity
dev_langs:
- CSharp
- C++
- VB
---

# PutQuantityDiscountLevelByQuantity Method

Get the quantity discount threshold level which the given quantity qualifies for on the given offer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutQuantityDiscountLevelByQuantity ( _
    offerId As String, _
    quantity As Decimal, _
    result As QuantityDiscountLevel _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim offerId As String
Dim quantity As Decimal
Dim result As QuantityDiscountLevel

instance.PutQuantityDiscountLevelByQuantity(offerId, _
    quantity, result)
```

``` csharp
void PutQuantityDiscountLevelByQuantity(
    string offerId,
    decimal quantity,
    QuantityDiscountLevel result
)
```

``` c++
void PutQuantityDiscountLevelByQuantity(
    String^ offerId, 
    Decimal quantity, 
    QuantityDiscountLevel^ result
)
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

