---
title: GetTaxCodeIntervalsProcedure.GetTaxCodeIntervals Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite)
TOCTitle: GetTaxCodeIntervals Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.GetTaxCodeIntervalsProcedure.GetTaxCodeIntervals(System.String,System.String,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlite.gettaxcodeintervalsprocedure.gettaxcodeintervals(v=AX.60)
ms:contentKeyID: 65316510
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.GetTaxCodeIntervalsProcedure.GetTaxCodeIntervals
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxCodeIntervals Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxCodeIntervals ( _
    salesTaxGroup As String, _
    itemTaxGroup As String, _
    transactionDate As DateTimeOffset _
) As ReadOnlyCollection(Of TaxCodeInterval)
'Usage
Dim instance As GetTaxCodeIntervalsProcedure
Dim salesTaxGroup As String
Dim itemTaxGroup As String
Dim transactionDate As DateTimeOffset
Dim returnValue As ReadOnlyCollection(Of TaxCodeInterval)

returnValue = instance.GetTaxCodeIntervals(salesTaxGroup, _
    itemTaxGroup, transactionDate)
```

``` csharp
public ReadOnlyCollection<TaxCodeInterval> GetTaxCodeIntervals(
    string salesTaxGroup,
    string itemTaxGroup,
    DateTimeOffset transactionDate
)
```

``` c++
public:
ReadOnlyCollection<TaxCodeInterval^>^ GetTaxCodeIntervals(
    String^ salesTaxGroup, 
    String^ itemTaxGroup, 
    DateTimeOffset transactionDate
)
```

#### Parameters

  - salesTaxGroup  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemTaxGroup  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxCodeInterval](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetTaxCodeIntervalsProcedure Class](gettaxcodeintervalsprocedure-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)

