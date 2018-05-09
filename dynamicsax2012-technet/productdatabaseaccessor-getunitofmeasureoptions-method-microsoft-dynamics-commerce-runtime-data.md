---
title: ProductDatabaseAccessor.GetUnitOfMeasureOptions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetUnitOfMeasureOptions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.GetUnitOfMeasureOptions(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.productdatabaseaccessor.getunitofmeasureoptions(v=AX.60)
ms:contentKeyID: 65318924
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.GetUnitOfMeasureOptions
dev_langs:
- CSharp
- C++
- VB
---

# GetUnitOfMeasureOptions Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetUnitOfMeasureOptions ( _
    productIds As IEnumerable(Of Long) _
) As ReadOnlyCollection(Of UnitOfMeasureConversion)
'Usage
Dim instance As ProductDatabaseAccessor
Dim productIds As IEnumerable(Of Long)
Dim returnValue As ReadOnlyCollection(Of UnitOfMeasureConversion)

returnValue = instance.GetUnitOfMeasureOptions(productIds)
```

``` csharp
public ReadOnlyCollection<UnitOfMeasureConversion> GetUnitOfMeasureOptions(
    IEnumerable<long> productIds
)
```

``` c++
public:
ReadOnlyCollection<UnitOfMeasureConversion^>^ GetUnitOfMeasureOptions(
    IEnumerable<long long>^ productIds
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[UnitOfMeasureConversion](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductDatabaseAccessor Class](productdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

