---
title: TaxL2CacheDataStoreAccessor.GetTaxCodeIntervals Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxCodeIntervals Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.GetTaxCodeIntervals(System.String,System.String,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.gettaxcodeintervals(v=AX.60)
ms:contentKeyID: 62211736
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.GetTaxCodeIntervals
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxCodeIntervals Method

Gets the tax code intervals.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxCodeIntervals ( _
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

returnValue = instance.GetTaxCodeIntervals(salesTaxGroupId, _
    itemTaxGroupId, transactionDate)
```

``` csharp
public ReadOnlyCollection<TaxCodeInterval> GetTaxCodeIntervals(
    string salesTaxGroupId,
    string itemTaxGroupId,
    DateTimeOffset transactionDate
)
```

``` c++
public:
ReadOnlyCollection<TaxCodeInterval^>^ GetTaxCodeIntervals(
    String^ salesTaxGroupId, 
    String^ itemTaxGroupId, 
    DateTimeOffset transactionDate
)
```

#### Parameters

  - salesTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[TaxCodeInterval](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of tax code intervals.  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

