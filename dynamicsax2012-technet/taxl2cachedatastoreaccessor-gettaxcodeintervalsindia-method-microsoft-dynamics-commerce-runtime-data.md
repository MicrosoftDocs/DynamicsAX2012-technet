---
title: TaxL2CacheDataStoreAccessor.GetTaxCodeIntervalsIndia Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxCodeIntervalsIndia Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.GetTaxCodeIntervalsIndia(System.String,System.String,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.gettaxcodeintervalsindia(v=AX.60)
ms:contentKeyID: 62213713
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.GetTaxCodeIntervalsIndia
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxCodeIntervalsIndia Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax code intervals for India.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxCodeIntervalsIndia ( _
    salesTaxGroupId As String, _
    itemTaxGroupId As String, _
    transactionDate As DateTimeOffset _
) As ReadOnlyCollection(Of TaxCodeInterval)
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
Dim salesTaxGroupId As String
Dim itemTaxGroupId As String
Dim transactionDate As DateTimeOffset
Dim returnValue As ReadOnlyCollection(Of TaxCodeInterval)

returnValue = instance.GetTaxCodeIntervalsIndia(salesTaxGroupId, _
    itemTaxGroupId, transactionDate)
```

``` csharp
public ReadOnlyCollection<TaxCodeInterval> GetTaxCodeIntervalsIndia(
    string salesTaxGroupId,
    string itemTaxGroupId,
    DateTimeOffset transactionDate
)
```

``` c++
public:
ReadOnlyCollection<TaxCodeInterval^>^ GetTaxCodeIntervalsIndia(
    String^ salesTaxGroupId, 
    String^ itemTaxGroupId, 
    DateTimeOffset transactionDate
)
```

#### Parameters

  - salesTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxCodeInterval](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of tax code intervals.  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

