---
title: PricingDataServiceManager.GetQuantityDiscountLevelByQuantity Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetQuantityDiscountLevelByQuantity Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetQuantityDiscountLevelByQuantity(System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getquantitydiscountlevelbyquantity(v=AX.60)
ms:contentKeyID: 65320796
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetQuantityDiscountLevelByQuantity
dev_langs:
- CSharp
- C++
- VB
---

# GetQuantityDiscountLevelByQuantity Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetQuantityDiscountLevelByQuantity ( _
    offerId As String, _
    quantity As Decimal _
) As QuantityDiscountLevel
'Usage
Dim instance As PricingDataServiceManager
Dim offerId As String
Dim quantity As Decimal
Dim returnValue As QuantityDiscountLevel

returnValue = instance.GetQuantityDiscountLevelByQuantity(offerId, _
    quantity)
```

``` csharp
public QuantityDiscountLevel GetQuantityDiscountLevelByQuantity(
    string offerId,
    decimal quantity
)
```

``` c++
public:
virtual QuantityDiscountLevel^ GetQuantityDiscountLevelByQuantity(
    String^ offerId, 
    Decimal quantity
) sealed
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Implements

[IPricingDataManager.GetQuantityDiscountLevelByQuantity(String, Decimal)](ipricingdatamanager-getquantitydiscountlevelbyquantity-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

