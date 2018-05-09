---
title: PricingSqliteDatabaseAccessor.GetQuantityDiscountLevelByQuantity Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite)
TOCTitle: GetQuantityDiscountLevelByQuantity Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.PricingSqliteDatabaseAccessor.GetQuantityDiscountLevelByQuantity(System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.sqlite.pricingsqlitedatabaseaccessor.getquantitydiscountlevelbyquantity(v=AX.60)
ms:contentKeyID: 65315973
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.PricingSqliteDatabaseAccessor.GetQuantityDiscountLevelByQuantity
dev_langs:
- CSharp
- C++
- VB
---

# GetQuantityDiscountLevelByQuantity Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function GetQuantityDiscountLevelByQuantity ( _
    offerId As String, _
    quantity As Decimal _
) As QuantityDiscountLevel
'Usage
Dim instance As PricingSqliteDatabaseAccessor
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
QuantityDiscountLevel^ GetQuantityDiscountLevelByQuantity(
    String^ offerId, 
    Decimal quantity
)
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[PricingSqliteDatabaseAccessor Class](pricingsqlitedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)

