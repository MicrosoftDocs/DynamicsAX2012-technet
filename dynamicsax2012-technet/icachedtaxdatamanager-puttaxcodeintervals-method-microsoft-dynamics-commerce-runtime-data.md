---
title: ICachedTaxDataManager.PutTaxCodeIntervals Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutTaxCodeIntervals Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedTaxDataManager.PutTaxCodeIntervals(System.String,System.String,System.DateTimeOffset,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedtaxdatamanager.puttaxcodeintervals(v=AX.60)
ms:contentKeyID: 62207912
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedTaxDataManager.PutTaxCodeIntervals
dev_langs:
- CSharp
- C++
- VB
---

# PutTaxCodeIntervals Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax code intervals.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutTaxCodeIntervals ( _
    salesTaxGroupId As String, _
    itemTaxGroupId As String, _
    transactionDate As DateTimeOffset, _
    result As ReadOnlyCollection(Of TaxCodeInterval) _
)
'Usage
Dim instance As ICachedTaxDataManager
Dim salesTaxGroupId As String
Dim itemTaxGroupId As String
Dim transactionDate As DateTimeOffset
Dim result As ReadOnlyCollection(Of TaxCodeInterval)

instance.PutTaxCodeIntervals(salesTaxGroupId, _
    itemTaxGroupId, transactionDate, _
    result)
```

``` csharp
void PutTaxCodeIntervals(
    string salesTaxGroupId,
    string itemTaxGroupId,
    DateTimeOffset transactionDate,
    ReadOnlyCollection<TaxCodeInterval> result
)
```

``` c++
void PutTaxCodeIntervals(
    String^ salesTaxGroupId, 
    String^ itemTaxGroupId, 
    DateTimeOffset transactionDate, 
    ReadOnlyCollection<TaxCodeInterval^>^ result
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

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxCodeInterval](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedTaxDataManager Interface](icachedtaxdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

