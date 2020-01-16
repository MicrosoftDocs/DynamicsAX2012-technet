---
title: TaxL2CacheDataStoreAccessor.PutTaxCodeIntervals Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutTaxCodeIntervals Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.PutTaxCodeIntervals(System.String,System.String,System.DateTimeOffset,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.puttaxcodeintervals(v=AX.60)
ms:contentKeyID: 62210742
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.PutTaxCodeIntervals
dev_langs:
- CSharp
- C++
- VB
---

# PutTaxCodeIntervals Method

Gets the tax code intervals.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutTaxCodeIntervals ( _
    salesTaxGroupId As String, _
    itemTaxGroupId As String, _
    transactionDate As DateTimeOffset, _
    result As ReadOnlyCollection(Of TaxCodeInterval) _
)
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
Dim salesTaxGroupId As String
Dim itemTaxGroupId As String
Dim transactionDate As DateTimeOffset
Dim result As ReadOnlyCollection(Of TaxCodeInterval)

instance.PutTaxCodeIntervals(salesTaxGroupId, _
    itemTaxGroupId, transactionDate, _
    result)
```

``` csharp
public void PutTaxCodeIntervals(
    string salesTaxGroupId,
    string itemTaxGroupId,
    DateTimeOffset transactionDate,
    ReadOnlyCollection<TaxCodeInterval> result
)
```

``` c++
public:
virtual void PutTaxCodeIntervals(
    String^ salesTaxGroupId, 
    String^ itemTaxGroupId, 
    DateTimeOffset transactionDate, 
    ReadOnlyCollection<TaxCodeInterval^>^ result
) sealed
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

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxCodeInterval](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[ICachedTaxDataManager.PutTaxCodeIntervals(String, String, DateTimeOffset, ReadOnlyCollection\<TaxCodeInterval\>)](icachedtaxdatamanager-puttaxcodeintervals-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

