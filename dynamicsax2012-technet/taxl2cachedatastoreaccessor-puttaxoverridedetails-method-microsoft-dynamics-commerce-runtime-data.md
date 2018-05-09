---
title: TaxL2CacheDataStoreAccessor.PutTaxOverrideDetails Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutTaxOverrideDetails Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.PutTaxOverrideDetails(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.puttaxoverridedetails(v=AX.60)
ms:contentKeyID: 62204772
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.PutTaxOverrideDetails
dev_langs:
- CSharp
- C++
- VB
---

# PutTaxOverrideDetails Method

Puts the tax override detail.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutTaxOverrideDetails ( _
    taxOverrideCode As String, _
    columns As ColumnSet, _
    result As TaxOverride _
)
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
Dim taxOverrideCode As String
Dim columns As ColumnSet
Dim result As TaxOverride

instance.PutTaxOverrideDetails(taxOverrideCode, _
    columns, result)
```

``` csharp
public void PutTaxOverrideDetails(
    string taxOverrideCode,
    ColumnSet columns,
    TaxOverride result
)
```

``` c++
public:
virtual void PutTaxOverrideDetails(
    String^ taxOverrideCode, 
    ColumnSet^ columns, 
    TaxOverride^ result
) sealed
```

#### Parameters

  - taxOverrideCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Implements

[ICachedTaxDataManager.PutTaxOverrideDetails(String, ColumnSet, TaxOverride)](icachedtaxdatamanager-puttaxoverridedetails-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

